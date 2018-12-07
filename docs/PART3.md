# Send SDK commands to the drone

Now that Node-RED is setup and configured we will start to send commands to the drone.  The SDK documentation, available from [the Ryze downloads page](https://www.ryzerobotics.com/tello-edu/downloads) details all the available commands.

The video below shows how commands are sent using the UDP node and also shows how the starter flow was created.

<- Add video here ->

## Task

You should take the [part3 starter flow](/flows/starter/part3_starter.json) and add an inject and change nodes to enable the following commands:

- emergency
- up 50cm
- down 50cm
- right 50cm
- left 50cm
- forward 50cm
- back 50cm
- rotate clockwise 90º
- rotate counter-clockwise 90º
- rotate clockwise 360º
- flip forward

When you need to pass a parameter for a command, ensure you use the property **payload.tellovalue** so the **format output message** node will generate the correct command to send to the drone.

There is a [solution flow](/flows/solutions/part3_solution.json) available if you need help or want to check your solution.

---

[Home](/README.md) | [Node-RED](/docs/PART1.md) | [Setup](/docs/PART2.md) | **Commands** | [Dashboard](/docs/PART4.md) | [Telemetry](/docs/PART5.md) | [Mission](/docs/PART6.md) | [Pictures](/docs/PART7.md) | [Visual Recognition](/docs/PART8.md)

---