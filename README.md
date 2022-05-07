Stat_tools is a module that provide methods and attributes for descriptive statistics. 
The module consist of three classes that inherit each from another. 

Actually, I choose OOP because I wanted to instantiate the dataset just once and then calling only the methods without make it necessary to passed the dataset each time

The main class is Quantitative, the parent class for Discrete and Continuous variables. It actually defines the two main attributes that is shared with both classes.
The Discrete class contains methods and attributes useful for the study of discrete variable. 

The Continuous class inherit from discrete the method and the attributes they have in common such as mean, the standard deviation...
It also contains some methods and attributes that are specifics to the continuous variable.
