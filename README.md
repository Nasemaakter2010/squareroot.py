# squareroot.py
def sqroot_newtonmethode(number, number_iters = 1000):
    a = float(number) # number to get square root of
    for i in range(number_iters): # iteration number
        number = 0.5 * (number + a / number) # update
	  # x_(n+1) = 0.5 * (x_n +a / x_n)
    return number
number = float (input ("please enter a positive number:"))

print("the square root of the number is approximately:",sqroot_newtonmethode(number))
