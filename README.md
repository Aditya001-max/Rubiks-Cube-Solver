# Rubiks-Cube-Solver
![](https://github.com/Aditya001-max/Rubiks-Cube-Solver/raw/main/assets/rubiks-cube-solver-small.png)

Rubik’s Cube
===
I am working on a Rubik’s Cube Solver project using **C++** and **OpenGL**.  
Initially, I focused on modeling the cube and handling user interaction.  
Now, I'm working on implementing the **solver algorithm** to solve scrambled cubes optimally.  
This is an exciting project that combines **graphics**, **algorithmic logic**, and **real-time interaction**.  
In the future, I plan to integrate **OpenCV** to scan a real cube using a camera and solve it virtually.

[GitHub](https://github.com/Aditya001-max/Rubiks-Cube-Solver)

Rubik's Cube Solver
===
Okay, it’s done. This Rubik’s Cube solver uses [Korf's Algorithm][korf], also known as [IDA*][ida], to find efficient solutions.  
The solver includes two viewing modes: a **3D interactive OpenGL cube** and a **flat face view**.  
The implementation is inspired by [Jaap Scherphuis' Cubie][cubie], solving the cube with a depth limit of 25.  
The cube can be scrambled and solved with a button, though full configuration options are still under development.  
All graphics are rendered using **OpenGL**.

![](https://github.com/Aditya001-max/Rubiks-Cube-Solver/raw/main/assets/rubiks-cube-solver-demo.png)

Download: [RubiksCube.zip][zip] (253 KB)

[korf]: http://en.wikipedia.org/wiki/Optimal_solutions_for_Rubik%27s_Cube#Korf.27s_Algorithm  
[ida]: http://en.wikipedia.org/wiki/IDA*  
[cubie]: http://www.jaapsch.net/puzzles/cubie.htm  
[zip]: https://github.com/Aditya001-max/Rubiks-Cube-Solver/raw/main/RubiksCube.zip

[GitHub](https://github.com/Aditya001-max/Rubiks-Cube-Solver)
