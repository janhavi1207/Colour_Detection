# Colour_Detection
<!DOCTYPE html>
<html>

<body>
  <h1>Color Detection with OpenCV</h1>

  <p>
    This Python script uses OpenCV to perform color detection on an image and get the name of the color based on the RGB values of the clicked point. It reads an image file, sets up an event listener to get the mouse double-click coordinates, and displays the color name along with its RGB values on the image.
  </p>

  <h2>Usage</h2>
  <p>
    To use this script, make sure you have Python and the required libraries installed. Run the script from the command line with the image path as an argument:
  </p>

  <pre>
    <code>
      python color_detection.py -i &lt;path_to_image&gt;
    </code>
  </pre>

  <h2>Dependencies</h2>
  <ul>
    <li>OpenCV</li>
    <li>NumPy</li>
    <li>Pandas</li>
    <li>Argparse</li>
  </ul>

  <h2>Implementation</h2>
  <p>
    The script uses OpenCV to read and display the image. It sets up a mouse event listener to get the mouse double-click coordinates and calculates the color name using the RGB values of the clicked point. The color names and corresponding RGB values are stored in a CSV file, which is read using Pandas.
  </p>

  <h2>Contributing</h2>
  <p>
    Contributions to this project are welcome! If you find any issues or have improvements to suggest, feel free to create a pull request or open an issue.
  </p>

  <h2>License</h2>
  <p>
    This project is licensed under the MIT License. See the LICENSE file for more details.
  </p>

</body>
</html>
