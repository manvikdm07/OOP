# OOP
import cmath  # supports complex numbers

def quadratic_roots(a, b, c):
    # calculate discriminant
    d = (b**2) - (4*a*c)

    # find two roots
    root1 = (-b + cmath.sqrt(d)) / (2 * a)
    root2 = (-b - cmath.sqrt(d)) / (2 * a)

    return root1, root2

# Example usage
a = float(input("Enter coefficient a: "))
b = float(input("Enter coefficient b: "))
c = float(input("Enter coefficient c: "))

if a == 0:
    print("Not a quadratic equation (a cannot be 0).")
else:
    r1, r2 = quadratic_roots(a, b, c)
    print(f"The roots are: {r1} and {r2}")
