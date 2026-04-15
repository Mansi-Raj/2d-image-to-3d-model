# 2D Image to 3D Model Rendering

A Python-based application that converts grayscale 2D images into 3D models using depth extraction and mesh generation techniques. The project utilizes computational geometry to generate STL files, making it suitable for 3D printing and visualization.

## Features

- Converts grayscale images to 3D models using pixel intensity as depth.
- Generates adaptive triangular meshes using NumPy for surface construction.
- Exports 3D models in STL format using `numpy-stl`.
- Visualizes models using Plotly.

## Tech Stack

- **Python**
- **NumPy**
- **Pillow**
- **numpy-stl**
- **Plotly**

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/2d-to-3d-model.git
    cd 2d-to-3d-model
    ```
2. Install dependencies:
    ```bash
    pip install numpy Pillow numpy-stl plotly
    ```

## Usage

1. Place your grayscale image in the project directory.
2. Run the script:
    ```bash
    python convert.py --image your-image.png
    ```
3. The generated STL file will be saved as `output.stl`.

## Visualization

For visualization, you can use tools like [MeshLab](https://www.meshlab.net/) or any other STL viewer.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License. See `LICENSE` for details.

---

**Happy Modeling!** 🦾

