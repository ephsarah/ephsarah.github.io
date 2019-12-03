---
layout: post
title: Project Report
subtitle: December 2, 2019
comments: true
---

# Assignment: Project Report

**1. Project title, description, motivation**

## Sarah's Singing LED Christmas Tree.
    
    *Amidst the stress of papers and final exams, it's often hard for me to get in the Christmas spirit!*
    *I designed this singing, light-up Christmas tree to remind myself that the most wonderful time of the year is indeed right around the corner...no matter the academic challenges that lie ahead.*
    *It's the perfect size to hang up on your dorm wall - and small enough to bring home to show off to parents! I know mine are anxious to see the new skills I've picked up in CS103.*
    * When light sensor senses it's dark, LEDs flash in pattern that looks like snow falling (highest position LED to lowest -- white, green, red -- twinkling similar to ghost firefly).
    * When light sensor senses it's dark AND yellow star is snapped onto top of tree, buzzer plays "Jingle Bells" and LEDs flash according to the music.

**2. Comprehensive materials list**
    * LilyPad board
    * 6 LilyPad LEDs
    * 1 light sensor
    * 1 buzzer
    * conductive thread
    * 12" strip of conductive fabric
    * scissors, needle
    * 1 snap (1 female and 1 male side)
    * green felt (20" x 20")
    * 1 square brown felt
    * 1 square yellow felt
    * red, green shiny embroidery floss
    * yellow, green embroidery floss
    
**3. Screenshot of your revised paper prototype of your project**

![Paper Prototype](https://ephsarah.github.io/img/treeproto.jpg)

**4. 1 Photo of your alligator prototype working**

![Tree Alligator Prototype](https://ephsarah.github.io/img/aligatortree.JPG)
Here is a photo when I alligator clipped the star snap feature. This photo was taken before I broke apart my board. This stage was important to make sure my code worked and that the light sensor and snap/button behaved appropriately.

*I alligator prototyped the whole project in class on the Monday before Thanksgiving break (with all pieces separated, and lots of clips!) but can't find the photo I took!!

**5. Photo of at least 3 stages of your working project (or video)**

![Working Code](https://ephsarah.github.io/img/workingcode.JPG)
A picture of my working code on an unsnapped board.

![One stage](https://ephsarah.github.io/img/1stage.JPG)
The under layer of the tree where you can see the circuit paths. I used conductive thread and made a bus with conductive fabric to bring the negative traces from the LEDs and star snap back to ground. I prevented my traces from crossing by placing a scrap piece of felt in between as insulation.

![Fabric Tube](https://ephsarah.github.io/img/fabrictube.JPG)
An up-close view of my fabric tube that encases the star's positive trace. This ensures that it doesn't get tangled with anything else. After I sewed the tube, I turned it inside out to have a cleaner edge.

![2 Sides](https://ephsarah.github.io/img/2sidestree.JPG)
Before I sewed the two faces togegther.

![Final Tree](https://ephsarah.github.io/img/finaltree.JPG)
The tree, all trimmed and ready to sing and dance!

**6. 3 tips to your past self**
    
    1. Digital vs. Analog Reads! I've made this mix-up a couple times now...In this case, I was accidentally analogReading the snap!
    2. Be brave and test, test, test! There were several moments when I felt wary of moving forward with the project because I was worried it wouldn't work and then I'd have to start over. I realized that sometimes you have to just go for it -- test when you can, but sometimes you just have to hope for the best and see if it works!
    3. Overestimate time it takes to sew decorations! This is not something that can be rushed...Rushing == painful needle pokes!
    4. Position LEDs closer to board to minimize voltage drop. I noticed the white LEDs (farthest away) tended to get dim. Sometimes I could fix this by wiggling the wiring/board around a little bit. They were a bit temperamental.


**7. Citations of any resources used**
    
    Music code taken from http://repairmypc.net/2017/08/jingle-bells-arduino-sketch/
    posted August 25, 2017 by Emmanuel
    
    Chris, Nathan, and Iris -- thank you!

