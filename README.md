# Building-AI
TEST 1

import random

def main():
    probs = [0.8, 0.9, 1.0]
    animals = ["dogs", "cats", "bats"]
    prob = random.random()
    favorite = ""
    if prob < probs[0]:
        favorite = animals[0]
    elif prob >= probs[0] and prob < probs[1]:
        favorite = animals[1]
    elif prob >= probs[1] and prob < probs[2]:
        favorite = animals[2]
    else:
        favorite = "coding errors"
    print("I love " + favorite) 

main()

"## Summary"
I love dogs
