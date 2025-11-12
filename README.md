# LudiComputer
<b>An easy way to build own personal computers, 
in an 80 pin, 2mm pitch, in a proposed S80 based bus</b>

<b>It is an electronic unit built by the player himself</b>

It is not just about playing, but also, above all, about building systemic computing machines embedded within minimum agreements.

In practice and as objectives, LudiComputers are: 
fantastic calculators, 
fun computers, 
chaotic computers, 
relaxed workstations, 
robotics that make humans work 
and in general systems where the important thing is to have been the designer and/or builder of the game machine itself.

<img src="image/ludicoputer03.jpg" alt="LudiComputer" width="800">

<b>LudiComputer S80 is designed for Hackathons</b>

The LudiComputers with S80 base connector are units that communicate with each other through one or more central bases, called nexus.
The nexus are electrically neutral, without power and havent only an LED that indicates the presence of energy on the bus supplied by one of the participants in the game. 
This topology modifies the classic connection form of the nexus, which instead of being on a battery, can form a flat extended structure on the game board, like domino tiles.

<img src="https://www.microelectronicjb.com/wp-content/uploads/2021/11/ResetLC01L.jpg"
     alt="Logic can work despite having neither energy nor intelligence"
     width="800">

The pin connector, as seen in the previous photo, corresponds to what gamer devices should have, they are cheaper and easier to obtain. (Diotronic sells it, Barcelona - Spain) The links incorporate sockets where each link connects three sockets and a quarter of male pins for interconnection with the following links.

<b>Reversible connector</b>

The ground terminals, negative pins, or common to all internal circuits are the four central pins (39, 40, 41, 42) and the central quarters (19, 20, 61, 62).

In the case of accidentally turning the connector, the power supplies are in the same place.

It follows that the four positives of 3V3 are central and central quarters (17, 18, 37, 38, 43, 44, 63, 64) as shown in the figure. However, it must be taken into account that there are only 16 GPIO pins forward or backward.

<img src="https://www.microelectronicjb.com/wp-content/uploads/2025/07/pinoutS80.png"
     alt="S80 forms four groups of 20 pins in symmetrical arrangement"
     width="800">

<b>Divisibility of the S80 Bus</b>

This bus is formed by four equal groups with symmetrical connection.

The protocol should be able to allow partial compositions of the connector, so that only those pins that are of interest to communicate can be soldered to the board to form groups of 8, 16, 32 or 64 bits as appropriate. The shape of the box must be designed to avoid misunderstandings due to displacement in the correlation of pins.

With all that has been said so far, it is very easy to imagine a system with fewer pins and smaller dimensions. However, for now, this format has been chosen to be able to make the four resolutions compatible in a single system (8 bits, 16 bits, 32 bits, 64 bits)

<img src="https://www.microelectronicjb.com/wp-content/uploads/2021/11/S80LC01L-1.jpg"
     alt="S80 connector, 80 pins in 2 millimeter pitch and double row."
     width="800">


<b>3D Scalability</b>

The designer must pay close attention to the location of pin 1, believe me, it is not trivial. In addition, two types of nexus plates have been provided, the passing and the rotating ones. There are also level-changing plates to form stacks or so-called Stacks. All this is mentioned in the rules of the game.

<b>Division by systemic game categories</b>

A LudiComputer S80 game base can be part of a communication protocol game depending on what the rules of the proposed game impose. In other words, depending on the game needs, the base will need to be of a more or less advanced category.

Six categories are defined:
LC-0 Communications, radio links
LC-1 Logical or abstract games
LC-2 Role and simulated characters
LC-3 Stage box or diorama
LC-4 Video games in local mode
LC-5 Video games in remote mode

<b>PCB dimensions for all LC-X S80</b>

<img src="https://www.microelectronicjb.com/wp-content/uploads/2025/07/base_peanya.png"
     alt="3D simulation of the base of the pedestals, minimum version to be able to connect on a table"
     width="800">

The printed circuit board is 100 x 100 millimeters with chamfers of 3 x 3 millimeters on each side. Through holes of 3.2 millimeters in diameter are provided for mounting with metric 3 through screws. The centered location of the through holes is 90 x 90, that is, the four square centimeters of the four ends have the through holes centered.

<b>The PCB</b>

The thickness of the printed circuit board must be the standard 1.66 millimeters since it is the size that remains between both rows of terminals in a 2 millimeter pitch pin strip. The connectors enter with a slight force that leaves them immobilized, but which facilitates subsequent soldering. You have to be careful when centering the connector, but it is very easy compared to how difficult it is to center the processors.

<img src="https://www.microelectronicjb.com/wp-content/uploads/2025/07/footprintS80.png"
     alt="3D simulation of the base of the pedestals minimum version to be able to connect on a table"
     width="800">

<b>The energy game</b>

The energy game consists of knowing how to defend the energy of our power supply from 3.3V. We may be powering all the other players if the voltage delivered is higher than the agreed point. However, in some games it may mean that we deliver energy to the objective to put it into operation, it will depend on each case.

High drop regulators tend to be very precise, on the other hand low drop regulators can produce significant differences depending on the loads. It is each player's problem whether to put their own power supply at the mercy of the bus or not, which is why two power supply circuits can be differentiated to avoid interference.

<img src="https://www.microelectronicjb.com/wp-content/uploads/2021/11/S803D.jpg"
     alt="Different 3D evolutions of the coupling between boards of the LudiComputer S80"
     width="800">

<b>Extension</b>

Systemic games have no player limit, so that the bus may require several physical level repeater bases, 3V3 CMOS signals.

<img src="https://www.microelectronicjb.com/wp-content/uploads/2022/04/IMG_20220404_162818_550-scaled.jpg"
     alt="3D simulation of the base of the pedestals minimum version to be able to connect on a table"
     width="800">

<b>Hello world!</b>

This LudiComputer concept expressed in this article is mentioned without the intention of invading what other projects have been able to express in a similar way. This work has been done freely and anonymously since 2021 and should not go against what third parties have done without the knowledge of my work. In this sense, shared use is allowed without its development going against mine or beyond the correct non-commercial use, without the intention of economic benefit, neither mine nor that of third parties.

<b>Open to the LudiComputer experience!</b>

<img src="https://www.microelectronicjb.com/wp-content/uploads/2021/11/LC-2.jpg"
     alt="Hello world!"
     width="800">

<b>© Jordi Breu, 2021. This article is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License.</b>

