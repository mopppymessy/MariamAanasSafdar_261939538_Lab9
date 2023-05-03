class Person:
    def __init__(self,name, age):
        self.name=name
        self.age=age


class House:
    def __init__(self,address,no_rooms):
        self.address=address
        self.no_rooms= no_rooms
        self.occupant=[]

    def remove_occupant(self,people):
        self.occupant.remove(people)

        
    def add_occupant(self,people):
        self.occupant.append(people)

    def addresss(self):
        self.address
        
    def print_details(self):
        print(f"The people who live at {addresses.address} are:")
        for occupant in self.occupant:
            print(f"{occupant.name}, and they are {occupant.age} years old.")


occupant1=Person("Tehreem",20)
occupant2=Person("Areesha",22)
occupant3=Person("Fohal",23)
occupant4=Person("Faseeha",21)

addresses=House("22118 main boulevard rose lane", 5)

addresses.add_occupant(occupant1)
addresses.add_occupant(occupant2)
addresses.add_occupant(occupant3)
addresses.add_occupant(occupant4)

addresses.print_details()

addresses.remove_occupant(occupant3)

addresses.print_details()
