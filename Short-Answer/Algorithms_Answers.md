Add your answers to the Algorithms exercises here.

Exercise Ia. O(n^3)

Ib. O(n^4)

Ic. O(n^2)

Exercise II


assuming __n__-story building is a list of every floor in integers...

while len(__n__-story building) >= 2:
    if egg_drop(__n__-story building[range(__n__-story building)//2]) == broken:
        __n__-story building = __n__-story building[:__n__-story building // 2]
    elif:
        __n__-story building = __n__-story building[__n__-story building // 2:]

# Person goes up to __n__-story / 2 then drops an egg. If it breaks then go down and go to the middle point of the bottom half of the __n__ story and repeat. Else go up to the middle point of the top half and drop an egg and repeat.

# Continue loop until left with list of two integer floors and select the floor that == broken upon calling egg_drop() function

# Run time complexity would be O(n)

