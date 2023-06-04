
 Let's Eat - PDDL Instruction Manual

This repository contains the updated PDDL files for the "let's eat" planning problem.

 Prerequisites

To run the PDDL code, you need to have a PDDL planner installed on your machine. Choose a PDDL planner that supports the PDDL2.1 specification and follow the installation instructions provided by the respective project.

 Usage

1. Clone the repository:


   git clone https://github.com/your-username/lets-eat-pddl.git


2. Navigate to the cloned repository:


   cd PPDL-project


3. Run the planner with the domain and problem files:


   planner -d updated-domain.pddl -p updated-problem.pddl -o output.plan


   Replace `planner` with the command or executable for your chosen planner. Make sure to adjust the filenames accordingly if you've renamed the domain or problem files.

4. Check the planner output:

   After the planner finishes executing, it will generate an output file (e.g., `output.plan`) containing the solution plan.

## Additional Information

- The `updated-domain.pddl` file defines the actions, predicates, and types for the "let's eat" planning problem. Modify this file to extend or customize the domain.

- The `updated-problem.pddl` file defines the initial and goal states for the "let's eat" problem. Modify this file to experiment with different scenarios.

- Feel free to explore different PDDL planners and options to find the best planning solution for the "let's eat" problem.

## License

This project is licensed under the [MIT License](LICENSE).

