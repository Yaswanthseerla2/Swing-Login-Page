User Form Swing Application
Overview
This project is a simple Java Swing application that creates a graphical user interface (GUI) for a user form. The form consists of fields for username and password input, along with a submit button. This project demonstrates basic usage of Swing components to build a user interface.

Features
JFrame: The main window of the application, titled "User Form".
JLabel: Labels for the username and password fields.
JTextField: Text fields where users can input their username and password.
JButton: A button to submit the form.
Components Used
JFrame: A top-level container that provides a window on the screen.
FlowLayout: A layout manager that arranges components in a left-to-right flow, much like lines of text in a paragraph.
JLabel: A display area for a short text string or an image, or both.
JTextField: A lightweight component that allows the editing of a single line of text.
JButton: A button component that triggers an action when clicked.

Detailed Explanation
JFrame Initialization: A JFrame object named f is created with the title "User Form".
Visibility and Size: The frame is made visible with f.setVisible(true) and its size is set to 800x400 pixels.
Layout Manager: The layout manager is set to FlowLayout, which arranges components in a directional flow.
Components Addition:
JLabel for "Username" and corresponding JTextField are created and added to the frame.
JLabel for "Password" and corresponding JTextField are created and added to the frame.
A JButton labeled "Submit" is created and added to the frame.
