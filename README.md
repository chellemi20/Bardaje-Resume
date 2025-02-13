print("Personal information:")
class BARDAJE:
    def __init__(self, name, age, occupation, hobbies):
        self.name = name
        self.age = age
        self.occupation = occupation
        # Hobbies are stored in a vertical array (list of lists)
        self.hobbies = hobbies

    def display_info(self):
        print(f"Name: {self.name}")
        print(f"Age: {self.age}")
        print(f"Occupation: {self.occupation}")
        print("Hobbies:")
        for hobby in self.hobbies:
            print(f"  - {hobby[0]}")

# Example usage
BARDAJE_hobbies = [["Hobby1:EATING"], ["Hobby2:WATCHING"], ["Hobby3:SLEEPING"]]
BARDAJE = BARDAJE(name="BARDAJE", age=20, occupation="STUDENT", hobbies=BARDAJE_hobbies)

BARDAJE.display_info()

print("")
print("")
