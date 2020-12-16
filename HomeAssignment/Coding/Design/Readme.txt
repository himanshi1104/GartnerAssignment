***Explanation***
Classes are designed using IOC pattern while keeping in mind SOLID principles of OOPS as per my knowledge. 

DesignClass.Docx contains 7 Classes:
BusinessLogic Class- which acts a Driver class. We use FileFactory to get a IFileType Object.
FileFactory Class 
IFileType Interface- common Interface so that inheriting classes implements its method and have their own way to read and import data. 
JsonFile and YamlFile classes - are inheriting IFileType to implement importFile() and fetching file parameter to DatabaseFunction class.
FileFactory File-to get type of Object we need of concrete class i.e. JsonFile and YamlFile
DatabaseFunction class - take file parameters from concrete class and call executeQuery() present in DatabaseConnection
DatabaseConnection class - to form connection with Database and execute query here Like INSERT.





 

