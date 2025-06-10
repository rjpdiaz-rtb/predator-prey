# predator-prey
Async Learning Task: Prey-Predator Ecosystems

# Ecosystem
The predator-prey ecosystem I chose was the bear-fish ecosystem

# Agents
The agents in this model include bears, fish, and krill.

# Predator Behavior
Every timestep, bears can move, eat fish on the same tile, have a chance to reproduce, have an energy penalty for moving and reproducing, and die. Bears gain energy by eating fish and die when their energy <= 0.

# Prey Behavior
Every timestep, fish can move, eat krill on the same tile, have a chance to reproduce, have an energy penalty for moving and reproducing21, and die. Fish gain energy by eating krill and die when their energy <= 0.

# Krill Behavior
On setup, krill spawn on every patch and move around. When the patch doesn’t have krill on it, it will add 1 tick to its timer. Once the timer hits the threshold, it will spawn another krill.
