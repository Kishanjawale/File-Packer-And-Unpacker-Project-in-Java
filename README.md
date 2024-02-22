# Marvellous Packer Unpacker

## Overview
Marvellous Packer Unpacker is a Java-based graphical user interface (GUI) application that provides users with the ability to pack and unpack files. The application features a login system for secure access to the main functionalities.

## Login System:
Users can log in with a username and password.
Secure login with validation checks.

## Main Page:
After a successful login, users are directed to the main page.
Options to pack and unpack files are provided.

## Packing Feature:
Users can specify a directory name and destination file name for packing files.
The application creates a packed file containing the specified directory's contents.

## Unpacking Feature:
Users can specify the name of the packed file for unpacking.
The application extracts the original files from the packed file.

## Clock Display:
The GUI includes a clock displaying date, time, and day.

## Getting Started
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/marvellous-packer-unpacker.git
Open the project in your preferred Java development environment (IDE).
Build and run the MarvellousMain class to start the application.

## Usage
Launch the application and log in with your credentials.
On the main page, choose between packing or unpacking files.

## For packing:
Enter the directory name.
Enter the destination file name.
Click the "SUBMIT" button.

## For unpacking:
Enter the name of the packed file.
Click the "Extract Here" button.

## Project Structure
The project is organized into several classes, each responsible for specific functionalities:
MarvellousLogin: Handles the login system.
Template: Provides the basic structure for the GUI.
NextPage: Represents the main page after login.
MarvellousPackFront: Front-end for packing files.
MarvellousPacker: Handles the packing functionality.
MarvellousUnpackFront: Front-end for unpacking files.
MarvellousUnpack: Handles the unpacking functionality.

## Dependencies
The project uses Java's Swing library for GUI components. No external dependencies are required.
