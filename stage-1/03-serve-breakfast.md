# Serve Breakfast

## Description

The robot has to set a table for breakfast for one person and prepare cereal for them.
**Main goal**: Place breakfast items on a table (bowl, spoon, cereal box, and milk carton) and prepare cereal.

**Optional goals**:

1. Pour milk into the bowl
2. Place the spoon next to the bowl

## Focus

Object perception,manipulation, andtask planning.

## Setup

- Locations:
  - Start location: Before the test, the robot waits outside theArenaand navigates to the kitchen when the door is open.
  - Test location:The test itself takes place in the kitchen.
- People:
  - No people are involved in the test unless the robot requires human assistance.
- Furniture:
  - Table:The robot serves breakfast on the table which is announced beforehand.
  - Chairs:Chairs may be placed around the table and won’t be removed.
  - Doors:The robot does not need to open any doors to find the breakfast items.
- Objects:
  - All objects used in the test are in their predefined locations when the test starts.

## Procedure

1. Table selection: At least two hours before the test, the referees announce the surface that will be used as a table.
2. Test start:The robot moves to the kitchen when the arena door is open.
3. Serving breakfast:To serve breakfast, the robot has to place breakfast items on a table (bowl, spoon, cereal box, and milk carton).
4. Pouring cereal: After placing the breakfast items on the table, the robot should pour cereal into the bowl.
5. Optional goals:
   - Pouring milk:After pouring cereal, the robot pours milk into the bowl in order to fully prepare the breakfast.
   - Placing the spoon next to the bowl: In principle, the spoon can be placed anywhere on the table, but placing it next to the bowl is desired so that it is easily reachable by a person.

## Additional Rules and Remarks

1. Safe placing: Objects must be placed with care, namely the robot should place rather than throw or drop objects.
2. Deus ex Machina:The scores are reduced if human assistance is received, in particular for:
   - pointing to an object or telling the robot where an object is or where to place it
   - handing an object over to the robot
   - having a human place objects on the table
   - having a human pour cereal into the bowl

## Referee Instructions

The referee needs to:

- Remove all objects from the table.
- Place all objects in their default locations.

## OC Instructions

During the Setup Days:

- Provide official cutlery and tableware for training.

At least two hours before the test:

- Announce the table that will be used.
- Announce a rough location of the table.

## Score sheet

The maximum time for this test is 5 minutes.

| Action                                                             | Score  |
| ------------------------------------------------------------------ | ------ |
| **Main Goal**                                                      |
| Initial navigation to pick up area                                 | 15     |
| Perceiving object and categorizing it correctly (visualize or say) | 4 × 15 |
| Picking up breakfast items for transportation to the table         | 4 × 50 |
| Placing breakfast items on the table                               | 4 × 50 |
| Pouring cereal into the bowl                                       | 300    |
| **Bonus Rewards**                                                  |
| Pouring milk into the bowl                                         | 300    |
| Placing a spoon next to the bowl                                   | 100    |
| **Penalties**                                                      |
| Throwing or dropping an object on the table                        | 4 ×–30 |
| Spilling cereal while pouring                                      | –100   |
| Spilling milk while pouring                                        | –100   |
| **Deus Ex Machina Penalties**                                      |
| Pointing at an object                                              | 4 ×–5  |
| Handing an object over to the robot                                | 4 ×–20 |
| A human placing an object on the table                             | 4 ×–60 |
| A human pouring cereal in the bowl                                 | –100   |
| **Special Penalties & Bonuses**                                    |
| Not attending                                                      | -500   |
