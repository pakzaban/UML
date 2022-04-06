# UML - 
The main method instantiates FileReader which then selects one of its siblings (JASONFileReader or DelimitedFileReader) based on the file extension. Both of these Readers have methods for reading tweet files and state files.
