# Carry My Luggage

## Description

The robot helps the operator to carry some luggage to a car which is parked outside.
**Main Goal**: The robot helps the operator to carry a bag to a car parked outside.
**Optional goals**:

1. Re-entering the arena
2. Following the queue on the way back to the arena

## Focus

Person following, navigation in unmapped environments, social navigation.

## Setup

- Locations:
  - The test takes place both inside and outside the Arena.
  - The robot starts at a predefined location in the living room.
- People: The operator is standing in front of the robot and is pointing at the bag to be carried outside.
- Objects: At least two bags are placed near the operator (within a 2m distance and visible to the robot).

## Procedure

1. Picking up the bag: The robot picks up the bag pointed at by the operator.
2. Following the operator: The robot should inform the operator when it is ready to follow them. The operator walks naturally towards the car; after reaching the car, the operator takes the bag back and thanks the robot.
3. Obstacles: The robot will face 4 obstacles along its way (in arbitrary order):
   - a small object on the ground
   - a hard-to-see object
   - a crowd of people obstructing the path outside
   - a small area blocked using retractable barriers
4. Optional goals:
   - Re-entering the arena: The robot returns to the arena, going back in through the entrance.
   - Following the queue: After the robot has reached the car, a few of the people that formed the crowd obstructing the robot return to the arena in a queue. The robot can decide to join the queue on its way back to the arena, in a manner that appears natural to the people in the queue.

## Additional Rules and Remarks

1. Car location: There is no real car outside; instead, a fixed location outside the Arena is designated as a car location.
2. Reaching the car: The robot can reach the car location only by following the operator (the location is unknown before the test).
3. Deus ex Machina: Score reductions for human assistance are applied in case the robot loses the operator, and needs to find them again through:
   - Natural interaction (e.g., waving and calling)
   - Unnatural interaction (e.g., raising both hands and jumping)
   - Touching the robot (e.g., pulling the robot’s hand)

## Referee Instructions

The referees need to:

- Select one volunteer to act as the operator.
- Select three to four people to obstruct the robot’s path outside and form the queue on the way back to the arena.
- Choose positions for the bags and assign a bag to the operator.
- Choose the order of the obstacles that the robot will face outside while following the operator.
- Designate a location outside as a car location.
- Designate a location for the queue to form returning into the arena. The queue is composed of the same people that form the crowd.
- Mind the robot when it goes outside the Arena.

## OC Instructions

At least two hours before test:

- Select and announce the robot’s starting point.
- Select which bags will be used in the test.

## Score Sheet

The maximum time for this test is 5 minutes.

| Action                                                            | Score |
| ----------------------------------------------------------------- | ----- |
| **Main Goal**                                                     |
| Perceiving the correct beg (visualize on screen or say which one) | 15    |
| Picking up the correct bag                                        | 100   |
| Following the person to the car                                   | 300   |
| Avoiding the crowd of people obstructing the path                 | 50    |
| Avoiding the small object on the ground                           | 50    |
| Avoiding the hard-to-see object                                   | 50    |
| Avoiding the area blocked with retractable barriers               | 50    |
| **Bonus Rewards**                                                 |
| Re-entering the arena                                             | 100   |
| Joining and staying in the queue on the way to the arena          | 300   |
| **Penalties**                                                     |
| Dropping the bag                                                  | –50   |
| **Deus Ex Machina Penalties**                                     |
| Rediscovering the operator by natural interaction                 | –50   |
| Rediscovering the operator by unnatural interaction               | –100  |
| Rediscovering the operator by direct contact                      | –200  |
| **Special Penalties & Bonuses**                                   |
| Not attending                                                     | -500  |
