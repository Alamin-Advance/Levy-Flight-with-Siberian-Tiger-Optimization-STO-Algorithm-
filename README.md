# Levy Flight with Siberian Tiger Optimization (STO) Algorithm

This repository contains the implementation of the Levy-Flight-enhanced Siberian Tiger Optimization (STO) Algorithm, designed to tackle complex optimization problems. By integrating various Levy Flight (LF) strategies, this algorithm aims to enhance the balance between exploration and exploitation, and it has been benchmarked using CEC 2017 test functions.

## Overview

The Siberian Tiger Optimization Algorithm is inspired by the hunting strategies of Siberian tigers. This version incorporates multiple Levy Flight techniques to improve its performance, particularly in escaping local optima and exploring solution spaces effectively. The algorithm is especially suitable for high-dimensional and nonlinear optimization tasks.

## Features

- Levy Flight Integration: Utilizes various Levy Flight methods to enhance search capabilities and maintain solution diversity.
- CEC 2017 Benchmarking: Tested against a range of complex test functions from the CEC 2017 benchmark to evaluate performance.
- Versatile Applications: Ideal for optimization tasks like clustering, feature selection, and others in data mining and machine learning.
- Parameter Flexibility: Parameters can be easily tuned for specific applications or research needs.

## Requirements

This implementation is in Python and requires the following libraries:

numpy
scipy
matplotlib
pandas


Install these requirements with:

pip install numpy scipy matplotlib pandas

## Usage


### Example

The "sto.py, LFSTO-direct.py, LFSTO-Randprob.py, LFSTO-trial.py, and LFSTO-trial. py" files demonstrate the algorithm on various CEC 2017 benchmark functions. You can adjust this file's problem definition and algorithm parameters to test different LF methods and evaluate performance.

## Project Structure

- STO.py: Executes the STO Algorithm with various Levy Flight integrations.
- LFSTO-direct.py: Contains functions for different Levy Flight techniques.
- LFSTO-Randprob.py: Core implementation of the Siberian Tiger Optimization Algorithm.
- LFSTO-trial.py: Core implementation of the Siberian Tiger Optimization Algorithm.
- LFSTO-trap.py: Core implementation of the Siberian Tiger Optimization Algorithm.
- rank test: 
- benchmarks: Contains CEC 2017 benchmark functions for testing.
- examples: Additional problem definitions and test cases.



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or further information, please reach out or open an issue.
