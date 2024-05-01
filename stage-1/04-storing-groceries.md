# 3.5 Storing Groceries

The robot stores groceries into a cabinet with shelves. Objects are sorted on the shelves based
on similarity, for instance an apple is stored next to other fruits.

**Main goal**: Move five objects from a table to the cabinet, grouping them by category or simi-
larity.

Optional goals:

1. Opening the cabinet door
2. Moving a tiny object
3. Moving a heavy object

## Focus

Object detection and recognition,object feature recognition,object manipulation.

## Setup

- Locations:
  - Start location: Before the test, the robot waits outside theArenaand navigates to the testing area when the door is open.
  - Test location:The testing area has a cabinet and a table nearby.
- People:
  - No people are involved in the test, unless the robot requires human assistance.
- Furniture:
  - Table:The table has 5–10 objects placed on it and the robot can choose which ones to grasp and in what order. On small tables, objects will be added as the robot frees up space.
  - Cabinet: The cabinet contains objects arranged in groups — either by category or likeliness — on different shelves.
  - Cabinet door:The cabinet door is open by default, but the team leader can request the door to be closed and score additional points for opening it. If the robot fails to open the door, it must clearly state this and request the referee to open it.
- Objects:
  - Table objects: The object on the table are arranged arbitrarily.
  - Cabinet objects: Some of the objects are placed behind the cabinet door and cannot be accessed unless the door is open.

## Procedure

1. Table location: At least two hours before the test, the referees announce the table and cabinet that will be used in the test, as well as a rough location of the table.
2. Cabinet door; heavy and/or tiny object: Half an hour before the test, the team informs the referees:
   - whether the cabinet door should be closed
   - whether a heavy and/or a tiny object should be used in the test
3. Test start:The robot moves to the testing area when the arena door is open.
4. Storing groceries:After identifying the table (and optionally opening the cabinet door), the robot moves the objects from the table to the cabinet.

## Additional rules and remarks

1. Table: The table’s rough location will be announced beforehand, having its position to the left, right, or behind the robot.
2. Incorrect categorization:The score is reduced if an object is stored on the cabinet, but not on a shelf with similar objects; this reduction is applied per incorrectly stored object.
3. New category: Objects that do not semantically belong to any of the categories represented on the shelves should be grouped together on a new shelf.
4. Deus Ex Machina:The scores are reduced if human assistance is received, in particular for:
   - telling or pointing out to the robot where to place an object
   - moving an object instead of the robot

## OC Instructions

At least two hours before the test:

- Announce which table and cabinet will be used in the test.
- Announce a rough location for the table.

## Referee Instructions

The referee needs to:

- Place 5–10 objects on the table.
- Place objects in the cabinet, grouping them by category or likeliness.
- Open the door of the cabinet (unless the team wants it closed).

## Score sheet

The maximum time for this test is 5 minutes.

| Action                                                                                                                 | Score  |
| ---------------------------------------------------------------------------------------------------------------------- | ------ |
| **Main Goal**                                                                                                          |
| Navigating to the table                                                                                                | 15     |
| Perceiving object and categorizing it correctly (visualize or say)                                                     | 5 × 15 |
| Picking up an object for transportation to the cabinet                                                                 | 5 × 50 |
| Perceiving objects in shelf and saying on which layer the currently handled object should be placed (visualize or say) | 5 × 15 |
| Placing an object in the cabinet                                                                                       | 5 × 15 |
| Placing an object next to similar objects on the cabinet                                                               | 5 × 50 |
| **Bonus Rewards**                                                                                                      |
| Opening the cabinet door without human help                                                                            | 200    |
| Picking and placing a tiny object                                                                                      | 100    |
| Picking and placing a heavy object                                                                                     | 100    |
| **Penalties**                                                                                                          |
| Storing an object without categorizing it correctly                                                                    | 5 ×–60 |
| **Deus Ex Machina Penalties**                                                                                          |
| A human handing an object over to the robot (the object is clearly indicated by the robot)                             | 5 ×–15 |
| A human handing an object over to the robot                                                                            | 5 ×–30 |
| A human placing an object in the cabinet at a location clearly indicated by the robot                                  | 5 ×–45 |
| A human placing an object in the cabinet                                                                               | 5 ×–90 |
| A human placing an object in the cabinet at a location clearly indicated by the robot                                  | 5 ×–30 |
| A human pointing at a target location                                                                                  | 5 ×–45 |
| **Special Penalties & Bonuses**                                                                                        |
| Not attending                                                                                                          | -500   |
