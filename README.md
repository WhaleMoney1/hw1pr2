# hw1pr2
homework 1 part 2

# CSCI1010: Lab 1, Problem 1
# Filename: hw1pr2.py
# Name: 
# Problem description: Solving the quadratic equation!

from math import *

a = input("supply a value for a: ")
b = input("supply a value for b: ")
c = input("supply a value for c: ")

a = float(a)
b = float(b)
c = float(c)

x = (-(b)-(sqrt((b**2)-(4*a*c))))/(2*a)
y = (-(b)+(sqrt((b**2)-(4*a*c))))/(2*a)

print("the solutions are", x,"and",y)
