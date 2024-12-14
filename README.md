# LA-14

class Spiderman:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def describeSpiderman(self):
        print(f"{self.name} is {self.age} old.")


class Tobey(Spiderman):
    def __init__(self, name, age, movieTitle):
        super().__init__(name, age)
        self.movieTitle = movieTitle


class Andrew(Spiderman):
    def __init__(self, name, age, movieTitle):
        super().__init__(name, age)
        self.movieTitle = movieTitle


class Tom(Spiderman):
    def __init__(self, name, age, movieTitle):
        super().__init__(name, age)
        self.movieTitle = movieTitle


tobey = Tobey("Tobey", 49, "Spider-Man 3")
andrew = Andrew("Andrew", 41, "The Amazing Spider-Man")
tom = Tom("Tom", 29, "Spider-Man: Homecoming")

print(f"{tobey.name.upper()} {tobey.movieTitle}")
print(f"{andrew.name.upper()} {andrew.movieTitle}")
print(f"{tom.name.upper()} {tom.movieTitle}")
