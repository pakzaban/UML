# UML - 
The main method instantiates FileReader which then selects one of its siblings (JASONFileReader or DelimitedFileReader) based on the file extension.
The main method hands over two instances of the FileReader to the Processor's constructor as arguments.
The main method hands over the Processor instance to the Start method in the UserInterface.
