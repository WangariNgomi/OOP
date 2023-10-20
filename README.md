# OOP
Learning Object Oriented Programming
# Lists are mostly used to represent simple pieces of information
# in this example we are defining a software engineer object using a list that holds position, name, age, level and salary. 
# a list is not the ideal data structure to represent such a complex object, this is the reason why we have classes.
# classes represent complex objects, they contain functions that expalin the behaviour of our class. 
# basically a class is a blueprint how something should be defined
# instance attribute only belongs to a specific object created; in this case se and not the whole class
# class attribute is the same for every instance and can be  on the class itself

se1 = ["Software Engineer", "Miriam", 25, "Senior", 7000]
se2 = ["Software Engineer", "Marvin", 22, "Junior", 4000]

# defining a class
class SoftwareEngineer:
    # class attribute
    alias = "Tensor Girl"

    def __init__(self, name, age, level, salary):
        # instance attributes
        self.name = name
        self.age = age
        self.level = level
        self.salary = salary
    

# instance
se1 = SoftwareEngineer("Miriam", 25, "Senior", 7000)
print(se1.name, se1.age)

se2 = SoftwareEngineer("Marvin", 22, "Junior", 4000)
print (SoftwareEngineer.alias)