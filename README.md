# Optimization Problem Tasks

## Solving a Basic Optimization Problem Using PyGAD

### Task:

A van in a shop must be filled to transport household appliances. Its load must be optimized by maximizing the value of what is transported for a given volume. You are free to test for chosen free space (volume capacity) values between 1 and 5.

### Steps to Use PyGAD

To use the PyGAD module, here is a summary of the required steps:

1. **Preparing the fitness_func parameter**: Define how to evaluate the solutions based on their performance.
2. **Preparing Other Parameters**: Set up the parameters needed for the genetic algorithm.
3. **Import PyGAD**: Import the PyGAD library into your script.
4. **Create an Instance of the pygad.GA Class**: Instantiate the genetic algorithm class.
5. **Run the Genetic Algorithm**: Execute the algorithm to find the optimal solution.
6. **Plotting Results**: Visualize the results to analyze performance.
7. **Information about the Best Solution**: Retrieve and display information about the best solution found.
8. **Saving & Loading the Results**: Implement functionality to save and load results for future use.

### Life Cycle of PyGAD

The next figure lists the different stages in the lifecycle of an instance of the pygad.GA class. Note that PyGAD stops when either all generations are completed or when the function passed to the on_generation parameter returns the string stop.

![Life Cycle of PyGAD]([URL_TO_YOUR_IMAGE](https://github.com/SaifuliAnna/Optimization_Problem_Tasks/blob/main/life_cycle.jpg))

## References

If you used PyGAD, please consider citing its paper with the following details:

```bibtex
@article{gad2023pygad,
  title={Pygad: An intuitive genetic algorithm python library},
  author={Gad, Ahmed Fawzy},
  journal={Multimedia Tools and Applications},
  pages={1--14},
  year={2023},
  publisher={Springer}
}
