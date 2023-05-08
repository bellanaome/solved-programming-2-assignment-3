Download Link: https://assignmentchef.com/product/solved-programming-2-assignment-3
<br>
<p class="ui header product-top-header" title="Programming 2 - Assignment 3 Solution">Please ensure that relevant java files are submitted in the correct assignment folder on AUT online by midnight on the due date. Only classes from the Java standard library may be used for this assignment. Best to zip up all java files and place into a folder with your full name and student ID.

Question 1)

Prepare an abstract class called Shape for representing a general shape that can be drawn on the screen, using the following UML diagram as a guide. It should have a default constructor as well as a constructor that specifies a starting point for the shape, accessor and mutator methods for the colour of the shape, a mutator method for specifying a control point which determines the size of the shape, and an abstract draw method for drawing the shape based on the starting and control points

Question 2)

Prepare an interface called EnclosesRegion for representing the property possessed by those shapes which enclose a region (and so have an interior). It should include a method setFilled for determining whether the shape is drawn with its interior filled in.

Question 3)

Design and implement classes Line, Oval, Circle, Rectangle, and Square for representing particular shapes. Pay careful attention to the hierarchy of these classes with respect to each other, and their relationship with Shape and EnclosesRegion. The Line class prepares a straight line between its start point and its control point. The classes Oval and Circle use the start point for their centre and the control point for the edge of the shape. However, Rectangle and Square use these points for opposite corners (the width of a Square is determined by the horizontal position of the control point).

Question 4)

Prepare a GUI panel called ShapeSketcher for drawing a collection of shapes. It should contain a set of five radio buttons for choosing the next shape to add to the sketch, a checkbox for whether or not the next shape should be filled in, a button for changing the colour used (the class JColorChooser might be useful), as well as a panel containing the sketch. Each shape is added to the sketch by rubberbanding, dragging the mouse from its start point to a control point, with the shape being resized while the mouse is dragged. Whenever the mouse is dragged in a horizontal or vertical direction, the user should be informed by the letter H or V appearing alongside the current mouse position. HINT: May be useful to create an innerclass which also extends JPanel of a fixed size to handle the drawing of shapes and listening for events. Also recommended to place your other ”J” components in another separate panel. Essentially ShapeSketcher should extend JPanel and contain two more panels, one for holding the components and one for drawing the shapes and listening for MouseEvent objects. Put all your JFrame setup inside the main method.

Question 5)

Further modify the ShapeSketcher class so that it also contains buttons for opening and saving sketches. Make the appropriate changes to Shape so that each shape can be serialized to a file using appropriate filtering streams. The user should be asked what file to open and save to using a JFileChooser. Make sure appropriate exceptions are handled and displayed to user with a JOptionPane.showMessageDialog method if the user tries to open an invalid file

5/5 - (3 votes)