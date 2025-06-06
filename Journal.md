## Day 1 (5/24) - 2-3 hours

- Began researching bionic hand design and the biomechanical structure of an actual hand.
- I want my design to be able to independently curl the fingers (over the IP joints) and rotate them (over the MCP joints), which in real hands basically requires two independent systems, flexors and extensors, to coordinate precisely. This would require 2 servos per finger which is unfeasible. Other robotic hands only allow fingers to curl, but I think that removes a lot of functionality. I think I can get away with implementing some sort of differential control. I will have to see how to do this once I prototype a finger and physically test the motion using strings. 

## Update 2 (5/26 - 6/4) - 10 hours

This update cycle I did a lot more (scattered) research into how I can design the hand and get maximum functionality out of it. First of all, I think it is important to set clear design criteria since there seem to be many levels of complexity that can be added.

### Design Criteria
- Should cost less than $350 (to fit within Hack Club's allowed budget)
- All fingers must be able to flex (over IP joints), rotate (over MCP joint), and abduct
- The wrist should be able to rotate
- The dimensions of the hand and forehand should approximate actual human dimensions
- It should try to mimic the feel of a real hand as much as possible (admittedly won't be the best)
- Complexity and number of motors needed should be minimized

One thing especially different about this is the degree of motion I want to add for each finger - many designs online only allow the finger to flex, essentially only allowing a fist formation. I want to allow the finger to rotate down independently as well. This will require at least 2 motors per finger. Abduction is also important, so I want to use 1 motor to abduct all 4 fingers and one to abduct the thumb (possibly), along with 1 motor to rotate the wrist. This will require about 12-13 motors in all. 
