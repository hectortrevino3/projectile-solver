<h1> Optimal Projectile Angle Solver </h1>

Live Demo: https://hectortrevino3.github.io/projectile-solver/

<img width="953" height="664" alt="image" src="https://github.com/user-attachments/assets/e76c8577-0dd4-440d-a01b-524627454ac6" />

<h2> Overview </h2>
Calculates the optimal launch angle for a projectile to achieve maximum range, accounting for air resistance. It allows you to customize all physical parameters (velocity, height, mass, drag, etc.) and test specific angles to see how real-world physics differs from the simplified 45° ideal.

<h2> How It Works </h2>
The solver uses a numerical integration simulation to model the projectile's flight step-by-step. At each interval, it applies the forces of gravity and drag, then a ternary search algorithm iterates through launch angles to find the one that produces the maximum range.

<h2> Usage </h2>
Adjust the parameters in the input fields and click Find Optimal Angle. To test a specific angle, use the dedicated section below.

To run this tool locally, simply download index.html and open it in your browser.

*This project was developed based on the physics equations and simulation logic originally modeled in Desmos.* https://www.desmos.com/calculator/yw6rvymseh
