# training

class Vehicle:
    def __init__(self, mileage, cost):
        self.mileage = mileage
        self.cost = cost

    def show_vehicle_details(self):
        print("I am a vehicle")
        print("Mileage of the vehicle", self.mileage)
        print("Cost of the vehicle", self.cost)


v1 = Vehicle(300, 500000)
v1.show_vehicle_details()


class Car(Vehicle):

    def show_car_details(self):
        print("I am a car")


c1 = Car(250, 800000)
c1.show_car_details()
c1.show_vehicle_details()
