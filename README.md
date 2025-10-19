# task-8.2-Produce-a-default-sequence-of-numbers-starting-from-0-ending-at-10-and-with-a-step-of-1-
define the function my_generator(n) that takes a parameter n
def my_generator(n):
    # initialize counter
    value = 0
    # loop until counter is less than n
    while value < n:
        # produce the current value of the counter
        yield value
        # increment the counter
        value += 1
# iterate over the generator object produced by my_generator
for value in my_generator(3):
    # print each value produced by generator
    print(value)
