Multiline
=========

An implementation of multiline string literals in Java, using Javadoc comments. 

This project is a copy of https://github.com/benelog/multiline project, which 
originated from Adrian Walker's blog post ( <http://www.adrianwalker.org/2011/12/java-multiline-string.html> ).

This project removes eclipse support and removes the warning message.

*It is a work in progress.*

## Usage
You can use multiline string literals with javadoc comments and '@Multiline' annotation.

For example,

	/**
	DELETE
 	FROM post
 	*/
	@Multiline static String deleteFromPost;

is equivalent to the following expression in Groovy.

	static String deleteFromPost = """
	DELETE
	FROM post
	"""
