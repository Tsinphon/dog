class Dog():
 def __init__(self,name,age):
  self.name = name
  self.age = age
 def sit(self):
  print(self.name.title()+" is now sitting.")
 def roll_over(self):
  print(self.name.title()+" rolled over!")

my_dog = Dog('wllie',6)
print("My dog's name "+my_dog.name.title()+".")
print("My dog is "+str(my_dog.age)+" years old.")
my_dog.sit()
my_dog.roll_over()
your_dog = Dog('lucy',3)
print("My dog's name "+my_dog.name.title()+".")
print("My dog is "+str(my_dog.age)+" years old.")
my_dog.sit()
print("\nYour dog's name "+your_dog.name.title()+".")
print("\nYour dog is "+str(my_dog.age)+" years old.")
your_dog.sit()
