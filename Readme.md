The solution I followed to apply singleton design pattern concept;
to ensure that the "SwingCalendar" frame won't be instantiated more than once in the project
are these three steps : 
1-Declare a private swingcalender constructor to prevent others from instantiating the class.
2-Initialize a private static instance of swingcalender type.
3-Create the instance of the class on-demand in a static method(getSwingInstance()) that first checks whether the instance exists or not and creates a new one only if it doesn’t exist.  
