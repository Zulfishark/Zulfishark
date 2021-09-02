class SoftwareEngineer:

    def __init__(self):
        self.name = "Zulfiqar Sarkar"
        self.role = "CS Student"
        self.tools = ["C"]
        self.learning = ["Python"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find"
                    "some of my work interesting.")

me = SoftwareEngineer()
me.say_hi()
