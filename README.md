# my-work
import math

def calculate_surface_area(radius):
    # Calculate the surface area using the formula 4 * pi * r^2
    surface_area = 4 * math.pi * radius ** 2
    return surface_area

# Example usage
radius_of_planet = 6371  # Example radius in kilometers (approximate radius of Earth)
surface_area_of_planet = calculate_surface_area(radius_of_planet)

print(f"The surface area of the planet is {surface_area_of_planet} square kilometers.")
