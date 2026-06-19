# Gizmo 2.0
## Description
Gizmo 2.0 is generally a small desk robot that acts as an AI companion whose only mission is to interact with you, dance with you, and even brainstorm with you. Gizmo 2.0 can help you organize your thoughts, and he gives incredible answers for any questions you ask him. Also, he is provided with a mic for voice and music recognition. So, you can have a little party with him, and it has 2 servo motors that act as joints for his arms, which are mainly used for dancing and interaction with his owner.

Gizmo was made after a lot of research and thinking i had like a really long time seeing totorial and example on the internet to see how to make a moving AI companian and which MCU to get and what could be its abailities so i used ESP32-S3 as the main MCU, inmp441 as a microphone, a speaker, 2 servo motors and a customed PCB to hold every thing together.

## Why it was biult
I had a really good time designing Gizmo as I made a unique 3D design with inspiration from EVE in the Wall-E robot film. As a kid I loved this character so much, and since it was really quiet and charming, it was like a new technology on earth to clean the planet, but I made it a little different. I made it to be like a moving thing on my desk to dance with me and interact with me when having long programming or designing sessions. Gizmo will be there for you. I wanted to make it with a moving wheels but i couldn't get a good design as well as that my desk is not that big for a moving robot So i ended up by making a static one with moving arms and a big processer which is the ESP32-S3.

There is another good reaseon for building Gizmo which is the amount of memories and thoughsts i gave into biulding it. Since this is my last project before attendign fallout which is a hackathon organized by Hack Club in shenzhen and i can't wait to go.

## How to use it / Build it
The first step of constructing Gizmo 2.0 is fabricating the PCB since it will be one of the main parts of the prototype. Also, you need it since the prototype doesn't have any additional space to maintain the electronics without the PCB. So, after fabricating the PCB, you should buy the components as well as jumpers and long wires for the LCD, speaker, and servo motors. After that you should 3D print the parts I provided in the repo, and for each part there is a compatible part in the main body, which will hold everything from servo motors to the connector and the head, which is part 5 or head connector; this connects to the neck of the head part.

Now we start the assembly. First of all, get your LCD and glue it to the front head part, then glue the speaker to the back head part, and assemble the 2 parts using the neck I provided, which has a place to hold all these parts together. After this, get the base and add the PCB after assembling everything and uploading the firmware. and close the base with the top part of the base and then assemble the main body and the servo motor holder and glue the servo motors to the part, then glue the arm to the servo motor after it to the main body after assembling the arms to the body. Now you have a full working prototype.

