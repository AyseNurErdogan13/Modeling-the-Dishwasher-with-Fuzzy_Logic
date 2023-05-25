# Modeling the Dishwasher with Fuzzy Logic
- For this code, the article on fuzzy logic modeling with a dishwasher on https://mmo.org.tr/sites/default/files/deb1c54814305ca_ek.pdf was used.
 - In this project, a fuzzy logic modeling of a dishwasher was developed using several input parameters (e.g. the degree of soiling of dishes, type of dishes, amount of detergent, etc.) and an output parameter (e.g. washing time, water temperature, etc.). The fuzzy logic approach models many complex and uncertain relationships of a dishwasher based on its input parameters.
This project aims to create a fuzzy logic system to control a dishwasher. The code is written in Python and uses the scikit-fuzzy library.

## Introduction

- Fuzzy logic is a powerful tool for modeling systems that are difficult to describe mathematically. It allows us to deal with imprecise and uncertain information in a flexible and intuitive way.

- A dishwasher is an ideal candidate for fuzzy logic control. It has many variables that affect its performance, such as water temperature, detergent concentration, and the amount and type of dishes being washed.

- This project will create a fuzzy logic system that takes into account these variables and controls the dishwasher to achieve optimal cleaning performance.

## Installation

To run this project, you will need to have Python 3 installed on your computer. You will also need to install the scikit-fuzzy library. You can install it using pip:

Copy code
```
!pip install scikit-fuzzy
```
## Usage

To run the fuzzy logic system, simply run the `modeling_the_dishwasher_with_fuzzy_logic.ipynb` script:

Copy code
```
modeling_the_dishwasher_with_fuzzy_logic.ipynb
```
## Input

This will start the system and prompt you to enter the inputs for the system. These inputs include:

- Amount of dishes
- Degree of pollution
- Type of dishes (e.g. plates, glasses, silverware)

Once you enter these inputs, the system will use fuzzy logic to calculate the optimal wash cycle for the dishwasher. It will output the recommended wash cycle, as well as a graph of the membership functions used in the fuzzy logic system.

## Conclusion

- This project demonstrates the power of fuzzy logic in modeling complex systems. By using fuzzy logic to control a dishwasher, we can achieve optimal cleaning performance while taking into account a wide range of variables.

- The scikit-fuzzy library makes it easy to implement fuzzy logic systems in Python, and this project serves as a good starting point for anyone interested in using fuzzy logic to control real-world systems.
