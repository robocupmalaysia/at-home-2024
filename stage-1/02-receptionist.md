# Receptionist

## Description

The robot has to take two new guests to the living room to introduce them and offer a free place to sit.
**Main goal**: Introduce and usher two newcomers to a party and maintain appropriate gaze direction (at person, direction of navigation).
**Optional goals**:

1. Describe the first guest for the second guest.

## Focus

System Integration,Human-Robot Interaction,Person Detection,Person Recognition

## Setup

- Location:
  - The test takes place in the living room.
  - The robot starts inside theArenaat a predefined location near the entrance door.
  - Entrance: The entrance door is open by default.
- People:
  - Host: The host’s name and favorite drink will be announced before the test. The host is already sitting in the living room.
  - Guests:Both guests have a name and favorite drink. Guests have to be guided to the living room to be introduced. Each of the guest will arrive separately. The sound of the bell will be provided to teams during setup period before competition.

## Procedure

- Introductions: When introducing guests, the robot must clearly identify the person being introduced and state their name and favorite drink. Introducing two people means to introduce them to each other.
- Seating People: The robot must point at a place or location where the guest can sit.
- Switching Places: Guests may switch places after they were seated.
- Describing the First Guest: Naming at least 4 characteristics of the first guest, i.e., color of clothes, color of hair, gender, and age, earns bonus points.
- Looking at person/direction of navigation:During verbal interactions and descriptions of people, robot looks at the conversational partner. Robot can point at the person being introduce/described or alternate gaze between two people. During navigation robot looks in the direction where it is going. Persistently gazing towards unrelated person or incorrect direction while moving during the task deducts points.

## Additional rules and remarks

1. Misunderstanding: Not understanding the guests and asking them again is fine. Continuing with a wrong name or drink causes a score reduction of 50pts.
2. Partial Scoring:The main task allows partial (per guest) scoring.
3. Deus ex Machina:Score reduction applies per guest as follows:
   - Custom Operator: Since the main focus of the test is HRI, no custom operator can be chosen.
   - Alternative HRI:Using an alternative HRI to understand a guest causes a score reduction of 75pts.
   - Recognizing People: If the robot has to ask for help to identify people, score is reduced by 200pts.

## Referee Instructions

The referees need to:

- Assign name and drink to 3 volunteers.
- Arrange (and re-arrange) people in the living room.

## OC Instructions

During setup day:

- Provide the dorbell sound.

At least two hours before test:

- Announce starting position.
- Announce host’s name and favorite drink.
- Recruit volunteers as host and guests.

## Score sheet

The maximum time for this test is 5 minutes.

| Action                                                                    | Score   |
| ------------------------------------------------------------------------- | ------- |
| **Main Goal**                                                             |
| Navigate to the door, when the door bell rings                            | 2 × 15  |
| Guide the guest to the other guests (navigate to the guest group)         | 2 × 100 |
| Look in the direction of navigation or at the navigation goal             | 2 × 50  |
| Introduce a new guest to every other guest                                | 2 × 50  |
| Offer a free seat to the new guest                                        | 2 × 100 |
| Look at the person talking                                                | 2 × 25  |
| Look at the person the robot is introducing the guest to                  | 2 × 50  |
| Qualitative robot social performance                                      | 50      |
| **Bonus Rewards**                                                         |
| Describe the first guest to the second guest                              | 150     |
| **Penalties**                                                             |
| Wrong guest information was memorized (continue with wrong name or drink) | –50     |
| Persistent inappropriate gaze (away from conversational partner)          | –50     |
| Persistent gaze not in the direction of the navigation while moving.      | –10     |
| **Deus Ex Machina Penalties**                                             |
| Alternative HRI                                                           | 2 ×–75  |
| Not recognizing people 2                                                  | ×–200   |
| **Special Penalties & Bonuses**                                           |
| Not attending                                                             | -500    |
