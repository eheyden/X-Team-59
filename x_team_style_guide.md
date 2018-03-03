# X-Team 59 Style Guide

Helps in keeping code consistent and helps develop good habits for the future as well.

## Naming conventions

using camel case for names - For example, camelCase

### Examples
* interfaces -- \<specifier\> Interface Foo {}
* classes -- \<specifier\> class Foo {}
* exception types -- \<specifier\> class FooExcepiton extends Exception {}
* fields -- \<specifier\> \<type\> fooField
* methods -- \<specifier\> \<type\> foo(\<params here\>) {}
* parameters -- \<type\> fooParameters
* local variables -- \<type\> fooLocalVariable
* instance constants -- \<type\> FOO_CONSTANT
* class constants -- \<specifier\> \<type\> FOO_CONSTANT

## Commenting style for public and private members of a class or interface:
Following the java doc pattern of commenting 
For example,
	/**
	 * @throws IllegalArgumentException
	 *             if null is passed
	 * @param item
	 *            is what needs to be looked up
	 * @return true if item is in BST, or returns false
	 */

### Examples

* classes 
	* class headers same as javadoc
* fields
	* use // after the variable explaining what it is doing
* constructors
	* javadoc
* methods
	* javadoc, include override
	* if method is split into sections, separate with empty lines
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  	* the bracket is on the first line, example: 
	if(){
		return;
	}
	* default setting for spacing
	* use tabs
	
  * switch statement
  	* always include a default case
	
  * while loops
  	* same as if statements
	* add comment of what this is doing
	
  * for loops
  	* same as if statements
	* add comment of what this is doing
	
  * enhanced for loops
  	* same as for loops
  	* add comment of what this is doing

