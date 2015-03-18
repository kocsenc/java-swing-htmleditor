Team Two HTML Editor
=====================
**This project is not being actively maintained**

A simple editor for HTML files.

Basic Design can be found at

	`design.pdf`

	This design document is the formal detail documentation covering the
	overview requiements, UML Class diagrams, design pattern usage and others.


Building
--------
To build an executable Jar with Maven, run

	mvn clean package --log-file buildlog.txt

Then, to execute the jar

	java -jar target/HTMLEditor.jar

alternatively, the batch file can be executed

	start.bat
	//On windows machines
