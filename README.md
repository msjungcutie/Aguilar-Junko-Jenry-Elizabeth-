class Car:
  """Represents a car with brand, model, and year."""

  def __init__(self, brand, model, year):
    """Initializes a new Car object."""
    self.brand = brand
    self.model = model
    self.year = year

  def display_info(self):
    """Prints the car's details."""
    print(f"Brand: {self.brand}")
    print(f"Model: {self.model}")
    print(f"Year: {self.year}")

# Create two car objects
car1 = Car("Honda", "Ford", 2021)
car2 = Car("Mercedes", "Hyundai", 2023)

# Display their details
print("Car 1:")
car1.display_info()

print("\nCar 2:")
car2.display_info()
