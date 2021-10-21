# About
This is all of the software and designs that went into developing the Prototype Mover Robot (PMR) between August 2021 and December 2021. This robot was developed as part of a project in the Unversity of Cininnati's Engineering Design & Thinking (ENED) 1100 course during the 2021 Fall Semester.

The goals for this project are to:
- Mock the locomotion of an animal for movement.
- Follow any preset route by following a thick line on the ground.
- Locate and move to various 'bins' full of various materials.
- Pick up and classify the 'bins' of material based on their weight
- Relocate the 'bins' of material based on their classificaiton

Our first iteration of the robot was nicknamed "Big Bertha". This design was promptly scrapped after Subtask 1 because of various issues.
The second iteration (current iteration) is nicknamed "Jiminy Cricket". This design proved to be far more reliable, mobile, and useful for our needs.

# Creation
The physical design(s) for the robot are located in the Robots/ subfolder in this repository. These can be loaded into Lego Digital Designer (LDD) with additional configuration for all of the models. See [this stackexchange post](https://bricks.stackexchange.com/questions/12715/ev3-specific-bricks-missing-from-lego-digital-designer-4-3-11-win) for more information on getting the EV3 Lego Bricks assets required to load the file.

These robots can also be digitally designed with any other program that can open LDD files, provided they have all of the assets.

# Setup
The code for the project was originally written in LabVIEW rev 2016. In the future these programs may be rewritten in Python.

## Prerequisites
You must have the following programs installed/configured:
- LabVIEW rev 2016

## Download the files
You should clone this repository in order to get all of the necessary files to run the robot. These are located in the LabVIEW/ subfolder in this repository. Please note, all of the Sub VIs are needed to run the project. These are indicated by a "sub_" prefix in the filename, followed by a short description of the function of the Sub VI.

The Project 2 LabVIEW.lvrbt and the robo_schema.bin are necessary files in order to define the programs of the project and specify the ports of the EV3 being used, respectively.

## Open LabVIEW
Open up LabVIEW rev 2016 and open the existing robot project that you downloaded earlier. This is the "Project 2 LabVIEW.lvrbt" file.

# Usage

## Run the program
Within LabVIEW, you may develop, open, run and/or deploy any of the existing LabVIEW programs onto the robot, provided it is built, plugged in, and the correct EV3 brick is targeted in the project overview.

# Additional Information / Contributors
University of Cincinnati

Engineering Design & Thinking

Project 2

Section 019

Team 270

August 2021 -> December 2021

## Contributors
Spencer Will, Brice Martinelli, Mitchell Fuller, Ethan Ratcliff
