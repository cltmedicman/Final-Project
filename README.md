# Final-Project

3D Scene in OpenGL

This project demonstrates how to create a simple 3D scene in OpenGL. The scene consists of a teapot, ball, and apple. The user can navigate the scene by using the mouse and keyboard.
Requirements

    OpenGL
    GLUT
    A C++ compiler

Instructions

    Clone the repository.
    Compile the code using the following command:

g++ -o 3d_scene 3d_scene.cpp -lglut -lGLU -lGL
Code snippet


3. Run the code using the following command:

Use code with caution. Learn more

./3d_scene
Custom Functions

The project uses two custom functions:

    init(): This function is called once at the beginning of the program, and it is used to initialize the OpenGL environment.
    display(): This function is called repeatedly, and it is used to render the 3D scene.

These functions can be reused in other 3D scenes, which makes the code more maintainable and reusable.

License

This project is licensed under the MIT License.
