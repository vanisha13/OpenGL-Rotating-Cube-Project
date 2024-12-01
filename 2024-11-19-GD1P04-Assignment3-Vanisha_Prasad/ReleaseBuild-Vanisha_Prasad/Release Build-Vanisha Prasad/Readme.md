# OpenGL Rotating Cube Project

This project demonstrates a rotating 3D cube using OpenGL. The cube can be controlled using the arrow keys to rotate it along the X and Y axes. The project utilizes shaders and OpenGL core features, and it has been developed using Visual Studio with GLFW and GLEW libraries.

## Features:
- A 3D cube rendered using OpenGL.
- The cube rotates along the X and Y axes based on user input from the left and right arrow keys.
- The project uses shaders for rendering the cube with different colors.
- OpenGL version: 4.6 Compatibility Profile.

## Prerequisites:
Before running the project, you will need to set up the following dependencies:

1. **GLFW**: A library for creating windows with OpenGL contexts.
2. **GLEW**: A library for managing OpenGL extensions.
3. **Visual Studio**: The project has been developed and tested using Visual Studio 2022.

### Installing Dependencies:
You can use `vcpkg` or manually download and configure the libraries.

1. **Install GLFW**:
    - Download GLFW from [https://www.glfw.org/](https://www.glfw.org/).
    - Follow the installation instructions on the GLFW website.

2. **Install GLEW**:
    - Download GLEW from [https://glew.sourceforge.net/](https://glew.sourceforge.net/).
    - Follow the installation instructions on the GLEW website.

3. **Set up Visual Studio**:
    - Open the project in Visual Studio 2022.
    - Make sure to link the GLFW and GLEW libraries properly in the project settings.

## Project Structure:
/Technical Demo 3 │ ├── /src │ ├── main.cpp # Main program logic │ ├── shaders/ # Directory for shader source files │ │ ├── vertex.glsl # Vertex shader │ │ └── fragment.glsl # Fragment shader │ └── README.md # This readme file │ ├── /x64 │ ├── Technical Demo 3.exe # Compiled executable │ └── Debug/ # Debug information and log files │ └── /lib ├── glfw/ # External GLFW library files └── glew/ # External GLEW library files


## How to Build and Run:

### Build Instructions:

1. **Open the Solution**:
    - Open the `Technical Demo 3.sln` file in Visual Studio.

2. **Set up the Dependencies**:
    - In Visual Studio, make sure to configure the project to include the correct paths for GLFW and GLEW.
    - Add the necessary include directories and library directories for GLFW and GLEW in the project settings.

3. **Build the Project**:
    - Once the setup is complete, build the project by selecting `Build > Build Solution` in the Visual Studio menu.
    - This will compile the source code and generate an executable (`Technical Demo 3.exe`).

4. **Run the Application**:
    - After the build is successful, run the project by pressing `Ctrl + F5` or selecting `Debug > Start Without Debugging`.
    - The application window will open, showing the rotating cube.

### Controls:
- **Left Arrow**: Rotate the cube to the left along the Y-axis.
- **Right Arrow**: Rotate the cube to the right along the Y-axis.

## Troubleshooting:

- **GLFW or GLEW errors**: Make sure the paths to GLFW and GLEW are correctly set up in Visual Studio's properties.
- **Missing DLLs**: Ensure that `glew32.dll` and other dependencies are in the same directory as the executable or properly linked.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

