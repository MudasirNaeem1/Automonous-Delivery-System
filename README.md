# -Automonous-Delivery-Robot
The Autonomous Delivery Robot project in Python allows users to select a start location and multiple delivery locations on a grid. For instance, the start location turning green, while delivery locations turn red.

🔍 Project & Output Highlights:
(User can select start location and delivery locations by yourself)
let's suppose ❗
1. Start Location: (0, 0) - Turned green.
2. Delivery Locations:
   - (4, 8) - First delivery, turned red.
   - (10, 11) - Second delivery, turned red.
   - (3, 8) - Third delivery, turned red.
   - (7, 13) - Fourth delivery, turned red.
   - (12, 5) - Fifth delivery, turned red.

🎮 Simulation Steps:
- The robot starts at (0, 0) and moves to each delivery location, turning path cells blue.
- The sequence follows from the start to the first delivery (4, 8), then to the second (10, 11), and so on.

🔄 Resetting and Clearing:
- Reset Grid: 
Clears all set locations and paths, returning the grid to its initial state.
- Clear Paths:
Removes only the blue path cells, leaving the start and delivery locations intact.
