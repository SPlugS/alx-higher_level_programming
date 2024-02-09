			PYTHON - ALMOST A CIRCLE.
0. Tests - All files, classes and methods are to be unit tested and PEP 8 validated.

1. Base Class - The programme writes the first class Base.

2. Rectangle - The programme writes the class Rectangle that it inherits from Base. 

3. Validation - The programme updates the class Rectangle by adding validation of all setter methods and instation (id excluded)

4. Area - The programme updates the class Rectangle by adding the public method def area(self): that returns the area value of the Rectangle instance.

5. Displays - The programme updates the class Rectangle by adding the public method def display(self): that prints in stdout the Rectangle instance with the character #

6. __str__ - Programme updates the class Rectangle by overriding the __str__ method that it returns [Rectangle] (<id>) <x>/<y> - <width>/<height>

7.  Display - The programme Updates the class Rectangle by improving the public method def display(self): to print in stdout the Rectangle instance with the character # by taking care of x and y

8. Update -  Programme updates the class Rectangle by adding the public method def update(self, *args): that assigns an argument to each attribute:

9. Update - The programme Updates class Rectangle by updating the public method def update(self, *args): by changing the prototype to update(self, *args, **kwargs) that assigns a key/value argument to attributes

10. The Square - The programme writes the class Square that inherits from Rectangle.

11.  Square size -  Programme updates the class Square by adding the public getter and setter size

12. Square update - The programme Updates the class Square by adding the public method def update(self, *args, **kwargs) that assigns attributes

13. Rectangle instance to dictionary representation -  Programme updates  the class Rectangle by adding the public method def to_dictionary(self): that returns the dictionary representation of a Rectangle

14. Square instance to dictionary representation - The programme Updates the class Square by adding the public method def to_dictionary(self): that returns the dictionary representation of a Square

15. Dictionary to JSON string - JSON is one of the standard formats for sharing data representation.
	 Programme updates the class Base by adding the static method def to_json_string(list_dictionaries): that returns the JSON string representation of list_dictionaries

16. JSON string to file -  The programme Updates the class Base by adding the class method def save_to_file(cls, list_objs): that writes the JSON string representation of list_objs to a file

17. JSON string to dictionary - Programme updates he class Base by adding the static method def from_json_string(json_string): that returns the list of the JSON string representation json_string

18. Dictionary to Instance -  The programme Updates the class Base by adding the class method def create(cls, **dictionary): that returns an instance with all attributes already set

19. File to instances - The programme updates the class Base by adding the class method def load from file(cls): that returns a list of instances

20. JSON ok, but CSV? -  The programme updates the class Base by adding the class methods def save to file csv(cls, list objs): and def load from file csv(cls): that serializes and deserializes in CSV

21. Let us Draw - The programme updates the class Base by adding the static method def draw(list rectangles, list squares): that opens a window and draws all the Rectangles and Squares


