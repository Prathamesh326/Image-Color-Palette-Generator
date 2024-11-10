# Image Color Palette Generator

This project allows you to upload an image and extract the top 10 most dominant colors along with their respective RGB or Hex codes. It uses Python and Flask for the backend and HTML, CSS for the frontend, with the PIL (Pillow) library for image processing.

## Features

- Upload an image and automatically generate the top 10 most frequent colors in the image.
- Display colors in either **RGB** or **Hex** format.
- Scalable image processing for large images.
- Stylish user interface with a responsive design.

## Requirements

To run this project locally, make sure you have the following dependencies installed:

- Python 3.6 or higher
- Flask
- Pillow (PIL)
- Numpy

You can install the required Python packages by running:

```bash
pip install -r requirements.txt
```

## Project Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Prathamesh326/Image-Color-Palette-Generator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Image-Color-Palette-Generator
   ```

3. Install the necessary dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:

   ```bash
   python main.py
   ```

5. Open your browser and go to `http://127.0.0.1:5000` to view the app.

## How It Works

- **Image Upload:** The user uploads an image via the form on the web interface.
- **Color Extraction:** The uploaded image is processed using the Pillow library, and the colors are extracted by counting the most frequent RGB values.
- **Scaling for Large Images:** The image is automatically scaled down for efficient processing if the image is too large.
- **Color Display:** The top 10 colors are displayed on the screen along with their RGB or Hex values.

## Usage

1. Navigate to the website.
2. Upload an image using the file input.
3. Select whether you'd like the color codes to be displayed in **RGB** or **Hex** format.
4. Click the **Generate Palette** button.
5. The app will display the top 10 dominant colors of the image, with their respective color boxes and codes.

## Project Structure

- `main.py`: The main Python script that runs the Flask application and handles image processing.
- `index.html`: The HTML template used for the frontend of the app.
- `static/`: Contains static assets like CSS and JS files (if added).
- `requirements.txt`: Contains a list of Python packages required for the project.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to open issues or submit pull requests if you encounter any bugs or wish to improve the project!

## Acknowledgments

- Pillow (PIL) for image processing
- Flask for the backend framework
- Numpy for handling image arrays
