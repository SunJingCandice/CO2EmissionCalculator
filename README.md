﻿# CO2 emission calculator

This program is a command line tool that returns the amount of CO2-equivalent that will be caused when traveling a given distance using a given transportation method.

# Installation

Language: JAVA // test connection!!

Version: JDK1.8.0

Dependency management tool: Apache Maven 3.6.3

This program was generated by leveraging NetBeans 8.2 on Windows system.

# Introduction
Unzip the `co2_calculator_prj.zip` file.
The main program of this calculator is `co2_calculator.java` . Please find it in the path of `co2_calculator_prj/src/main/java/co2_calculator.java`.
The test program of this calculator is `TestCO2Calculator.java` . Please find it in the path of `co2_calculator_prj/src/test/java/TestCO2Calculator.java`.


# Compilation
Open your command-line interpreter, change directory to navigate to the folder `co2_calculator_prj`. 
Given commands `mvn compile` to compile Java code. 

# Execution
Open your command-line interpreter, change directory to navigate to the folder `co2_calculator_prj`. 
Give conditions and run the program by using commands `mvn exec:java -Dexec.args="conditions"`. The CO2 emission will be returned in the command-line interpreter. 
> For example, given commands `mvn exec:java -Dexec.args="--transportation-method medium-diesel-car --distance 15 --unit-of-distance km"`. 
> The results `Your trip caused 2.6kg of CO2-equivalent` will be returned.

# Test
Open your command-line interpreter, change directory to navigate to the folder `co2_calculator_prj`. 
Run the test script by using commands `mvn test`. It will return the number of test cases in failure, error, and skip. For example, the test results will be returned as follows if the program passes all the unit test cases.
> Running TestCO2Calculator
> Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.106 sec
> Results :
> Tests run: 1, Failures: 0, Errors: 0, Skipped: 0

There are four test cases in this test program. Please modify the script `co2_calculator_prj/src/test/java/TestCO2Calculator.java` if you want to test more cases.
