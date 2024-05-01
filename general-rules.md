# RoboCup Competition

The competition consists of two Stages and a Final. Each stage consists of a series of Tests that are being held in a daily life environment. The best teams from Stage I advance to Stage II, which consists of more difficult tests. The competition ends with the Final, where only the two highest-ranked teams of each league compete to select the winner.

## General Rules and Regulations 

These are the general rules and regulations for the competition in the RoboCup@Home league. Every rule in this section can be considered to implicitly include the term “unless stated otherwise”. This means that additional or contrary rules, in particular with respect to the specification of tests, have a higher priority than those mentioned in the general rules and regulations.

### Scenario 
Most competition tests take place in the RoboCup@HomeArena, but some tests may take place outside, in a previously unknown public place. In this section, the Arena and its contents are described, in particular the furnishing and other information that is common between tests and leagues.

### Changes to the Arena 

Since robots should be able to function in the real world, the Arena is not fixed and might change without further notice. 

1. Major changes: Any furniture (at a Predefined Location or not) that cannot be expected to be fully static in an everyday environment might be moved slightly between tests. In particular, furniture will not change rooms or move drastically inside a room, but a couch or table may be slightly rotated or moved; fixed locations for such furniture items should not be assumed. Walls will stay in place and rooms will not change function. Passages might be blocked. 
2. Minor Changes: Slightly moved chairs, slightly closed doors, or anything similar cannot be avoided and might happen at any time, even during a test.

### Objects 

Some tests in the RoboCup@Home league involve recognizing and manipulating objects Most objects are likely to be lightweight and easy to grasp with one hand. Every Object Category has an assigned Predefined Location, where objects of that category can usually be found during tests (for example, an Fruits can be found on the Kitchen Table); assignments are announced during the Setup Days. Objects are provided at the competition for training. 

Two types of objects are used in the tasks: 

1. Known Objects: Objects previously known to the robot, divided into: 
    1. Consistent Objects: Objects whose image appears in the list of objects. 
    2. Similar Objects: Objects whose image is not present in the list of objects, but look similar enough to one of them that a person would consider them the same kind of object. For example, an apple whose color is different from the apple in the list of objects, or a piece of cloth with a different pattern. 1
    3. Standard Objects: Objects chosen from the YCB Dataset.
2. Unknown Objects: Any other object that is not in the object list but can be grasped or handled (e.g., Arena decorations).

### Predefined Rooms and Locations 
Some tests in the RoboCup@Home league involve a Predefined Location where people or objects can be found. Room names, predefined locations, and location classes are announced during the Setup Days

### Predefined Person Names 
Some tests in the RoboCup@Home league involve memorizing a person’s name. All people in the Arena have an assigned Predefined Name chosen by the TC.

### Bypassing Features With Human Help Because the Show Must Go On 
Robots can’t score unless they accomplish the main goal of a task. However, in many real-life situations, a minor malfunction may prevent the robot from accomplishing a task. To prevent this situation, while fostering awareness and human-robot interaction, robots are allowed to request human assistance during a test.

#### Procedure The procedure to request human assistance while solving a task is as follows: 
1. Request help: The robot must indicate loud and clear that it requires human assistance. It must be clearly stated: 
    * The nature of the assistance
    * The particular goal or desired result
    * How the action must be carried out (when necessary)
    * Details about how to interact with the robot (when necessary)
    * Detailed information to identify objects for picking and placing (e.g. object name, color or location). The provided information needs to show that objects were perceived by the robot. 
2. Supervise: The robot must be aware of the human’s actions, being able to tell when the requested action has been completed, as well as guiding the human assistant (if necessary) during the process. 
3. Acknowledge: The robot must politely thank the human for the assistance provided.

### Scoring 
There is no limit in the amount of times a robot can request human assistance, but score reduction applies every time it is requested. 

1. Partial execution: A reduction of 10% of the maximum attainable score is applied when the robot request a partial solution (e.g. pointing to the person the robot is looking for or placing an object within grasping distance). The referee decides whether the requested action is simple enough to corresponds to a partial execution or not.
2. Full awareness: A reduction of 20% of the maximum attainable score is applied when the robot is able to track and supervise activity, detecting possible, and when the requested action has been completed. 
3. No awareness: A reduction of 30% of the maximum attainable score is applied when the robot has to be told when the requested action has been completed. 
4. Bonuses: No bonus points can be scored when the robot requests help to solve part of a task that normally would grant a bonus. 
5. Score reduction overlap: The score reduction for multiple requests of the same kind do not stack, but overlap. The total reduction applied correspond to the worse execution (higher reduction of all akin help requests). This means, a robot won’t be reduced again for requesting help to transport a second object, but a second reduction will apply when the robot asks for a door to be opened. 
6. Allowed types of assistance: Thetypes of assistance allowed in a given task are specified in the respective task description. It should be noted that only the assistance types explicitly mentioned in a task description are actually allowed in a task; other types of assistance are not allowed and will nullify the obtained points for the part of the task in which they are applied. For instance, if a task focused on manipulation does not explicitly mention a Deus Ex Machina penalty for instructing a person to perform a manipulation activity, it should not be assumed that this is a loophole that can be exploited.

### Bypassing Automatic Speech Recognition 
Giving commands to the robot is essential in many tests. When the robot is not able to receive spoken commands, teams are allowed to provide means to bypass ASR via an Alternative method for HRI . Nonetheless, Automatic Speech Recognition is preferred.
1. ASRwith Default Operator: Noscore reduction. The command is given by the human operator who must speak (not shout) loud and clear. The default operator may repeat the command up to three times. 
2. ASR with Custom Operator: A reduction of 10% of the maximum attainable score is applied when a custom operator is requested. The Team Leader chooses a person who gives the command exactly as instructed by the referee. 
3. Gestures: A reduction of 20% of the maximum attainable score is applied when a gesture (or set of gestures) is used to instruct the robot. 
4. QR Codes: A reduction of 30% of the maximum attainable score is applied when a QR code is used to instruct the robot. 
5. Alternative Input Method: A reduction of up to 30% of the maximum attainable score is applied when a alternative HRI interface, is used to instruct the robot. Alternative HRI interfaces must be previously approved by the TC during the Robot Inspection.


## Procedure during Competition

### Safety First!

1. **Emergency Stop**: At any time when operating the robot inside and outside the scenario the owners have to stop the robot *immediately* if there is a possibility of dangerous behavior towards people and/or objects.

1. **Stopping on request**: If a member of the Technical or Organizational committee, an Executive or Trustee of the federation stops the robot (by pressing the emergency button) there will be no discussion.
Similarly if they tell the team to stop the robot, the robot must be stopped *immediately*.

1. **Penalties**: If the team does not comply, the team and its members will be excluded from the ongoing competition *immediately* by a decision of the *Technical Committee* (TC).
Furthermore, the team and its members may be banned from future competitions for a period not less than a year by a decision of the RoboCup JapanOpen Federation Trustee Board.

### Maximum number of team members

1. **Regular Tasks**: During a regular task, the maximum number of team members allowed inside the *Arena* is *one* (1).
Exceptions are tasks that explicitly require volunteer assistance.

1. **Setup**: During the setup of a task, the number of team members inside the *Arena* is not limited.

### Fair Play

*Fair Play* and cooperative behavior is expected from all teams during the entire competition, in particular:

- while evaluating other teams,
- while scoring, and
- when having to interact with other teams’ robots.

This also includes:

- not trying to cheat (e.g., pretending autonomous behavior where there is none),
- not trying to exploit the rules (e.g., not trying to solve the task but trying to score), and
- not trying to make other robots fail on purpose.

> [!WARNING]
> Disregard of this rule can lead to penalties in the form of negative scores, disqualification for a test, or even for the entire competition.

### Expected Robot’s Behavior

Unless stated otherwise, it is expected that the robot always behave and react in the same way a polite and friendly human being would do.

Please consider that average users will not know the specific procedure to operate a robot.
Hence, interaction should be as with any other human being.

### Robot Autonomy and Remote Control

1. **No touching**: During a test, the participants are not allowed to make contact with the robot(s), unless it is in a “natural” way and required by the task.

1. **Natural interaction**: The only allowed means to interact with the robot(s) are gestures and speech.

1. **Natural commands**: Anything that resembles direct control is forbidden.

1. **Remote Control**: Remotely controlling the robot(s) is strictly prohibited.
This also includes pressing buttons, or influencing sensors on purpose.

> [!WARNING]
> Disregard of this rule can lead to penalties in the form of negative scores, disqualification for a test, or even for the entire competition.

### Collisions

1. **Touching**: Gently *touching* objects is tolerated but unadvised.
However, robots are not allowed to crash with something.
The "[safety first!](#safety-first)" rule overrides any other rule.

1. **Major collisions**: If a robot crushes into something during a test, the robot is immediately stopped.
Additional penalties may apply.

1. **Functional touching**: Robots are allowed to apply pressure on objects, push away furniture and, in general, interact with the environment using structural parts other than their manipulators.
This is known as *functional touching*.
However, the robot must clearly announce the collision-like interaction and kindly request not being stopped.

> [!WARNING]
> TC can (and will) immediately stop a robot in case or suspicion of *dangerous* behavior.

### Removal of robots

Robots not obeying the rules are stopped and removed from the *Arena*.

1. It is the decision of the TC member monitoring the test if and when to remove a robot.

1. When told to do so by the TC member monitoring the test, the team must immediately stop the robot, and remove it from the *Arena* without disturbing the ongoing test.

1. More than 1 team member is allowed to enter the *Arena* after the robot has been stopped to quickly remove the robot from the *Arena*.

### Start signal

The default *start signal* (unless stated otherwise) is *door opening*.
The robot is waiting behind the door, outside the *Arena* and accompanied by a team member.
The test starts when a TC (not a team member) opens the door.

### Entering and leaving the *Arena*

1. **Start position**: Unless stated otherwise, the robot starts outside of the *Arena*.

1. **Entering**: The robot must autonomously enter the *Arena*.

### Referees and Scorer

All tests are monitored by a referee, who is a member of the *Technical Committee* (TC).
The TC may appoint an assistant scorer to aid in keeping time and filling in scoresheets.
The following rules apply:

1. **Referee Selection**: Referees are EC/OC/TC members.

1. **Referee instructions**: Right before each test, referee chooses one or more assistant to aid during the test.
The assistants will be instructed by the referee.

### Operators

Unless stated otherwise, robots are operated by a person selected by the competing team.
However, in some cases, *operators* other than the competing team may be selected by the TC.

### Time limits

1. **Regular Task**: The time limits set for each task are *strictly* followed.
Please, check each task time limit in the rules section.

1. **Setup time**: Unless stated otherwise, there is *5 minutes* for setup time.
Robots need to be ready right after the door has been closed to the former team.

1. **Time-up**: When the time is up, the team must immediately remove their robot(s) from the *Arena*.
No additional points will be scored.
