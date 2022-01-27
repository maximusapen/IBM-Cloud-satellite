#!/usr/bin/python
# -*- platform_engineering: utf-8 -*-


class SoftwareEngineer:

    def __init__(self):
        self.name = "Maximus Apen"
        self.role = "Software Engineer"
        self.language_spoken = ["en_US"]

    def say_hi(self):
        print("Thanks for dropping you can find me on Twitter @maximus_apen")


me = SoftwareEngineer()
me.say_hi()
