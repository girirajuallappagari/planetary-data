# planetary-data
class Planet :     def __init__(self,name, surface_gasses, number_of_moons,planet_has_rings):          self.name = name         self.surface_gasses = surface_gasses         self.number_of_moons = number_of_moons          self.planet_has_rings = planet_has_rings              def count_moons(self):         print(self.number_of_moons)     def gasses_of_planets(self):         print(self.surface_gasses) mercury= Planet("Mercury","",0,"No") venus= Planet("Venus",("Carbon Dioxide","Nitrogen"),0,"No") earth= Planet("Earth", ("Nitrogen", "Oxygen" ),1, "No") jupitor= Planet("Jupitor", ("Hydrogen", "Helium"), 79,"Yes") saturn= Planet("Saturn",("Hydrogen", "Helium"), 83, "Yes") uranus= Planet("Uranus", ("Hydrogen", "Helium", "Methane"), 27, "Yes") Planet.count_moons(saturn) Planet.gasses_of_planets(jupitor)
