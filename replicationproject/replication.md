# Assessment 1: Replication project

## FSR Ukulele ##

## Related projects ##
*Find about 6 related projects to the project you choose. A project might be related through  function, technology, materials, fabrication, concept, or code. Don't forget to place an image of the related project in the* `replicationproject` *folder and insert the filename in the appropriate places below. Copy the markdown block of code below for each project you are showing, updating the number* `1` *in the subtitle for each.*

### Related project 1 ###

Project: Micro:bit guitar

https://makecode.microbit.org/courses/csintro/arrays/project

![Image](https://pxt.azureedge.net/blob/a9d374a286c0f544dee4d366cbb31409806fdd1f/static/courses/csintro/arrays/microbit-guitar.png)

This project is related to mine as it is also an example of a project that uses the micro:bit to play different tones when the guitar is held differently and tilted while playing. Although I would be using a different form of input the concept is similar wherein the the pitch and tone of the sounds are modulated based on the input from the user. The array of notes can be played when an input occurs, such as one of the buttons being pressed, or if one or more of the pins is activated.

### Related project 2 ###

Project: Micro:bit paper piano

https://drive.google.com/file/d/1dgUUIEMWrP4NXYAxSSu5Rrd2ygb8OVcj/view

![Image](https://i.pinimg.com/originals/3e/18/49/3e1849fee14e298666b287468ab5feb1.jpg)

This project is also related to mine as it is also type of musical instrument whereas in this project the keys are covered by tin foil. All the keys are connected to 3.3 Volt that is supplied by the 3V pin of the microbit. There are 3 strips of tin foil laying under the keys perpendicularly. Each strip is connected to a digital input pin on the microbit. When a key is pressed it connects 3V to the digital input through the tin foils. The way microbit can recognize the different keys is that every key can
contact to different combination of strips as we cover some of the strips with paper

### Related project 3 ###

Project: Micro:bit tilt thermin

http://www.suppertime.co.uk/blogmywiki/2019/02/microbit-music-experiments/

![Image](https://i.ytimg.com/vi/oFTcXJISoH4/maxresdefault.jpg)

This project is also related to myine as it is also type of musical instrument, controlling the pitch of the tone being played by changing the physical pitch (tilt) of the micro:bit.

### Related project 4 ###

Project: Micro:bit light thermin

https://www.element14.com/community/community/stem-academy/microbit/blog/2018/12/21/project-bbc-microbit-light-theremin-by-cabe

![Image](rp01.jpg)

![Image](rp02.png)

This project is also related to myine as it is also type of musical instrument, controlling the pitch of the tone being played by changing the physical pitch (tilt) of the micro:bit.

## Reading reflections ##

### Reading: Don Norman, The Design of Everyday Things, Chapter 1 (The Psychopathology of Everyday Things) ###

*What I thought before: Never really understood the importance of feedback before but while working on this project where it was very helpfull in troubleshooting while prototyping. It actually lets you know how the user is interacting with the guitar.*

*What I learned: I learned that prequisite knowledge shapes the affordance of a technology, whereas in my projects's case the user usually already has an idea about how to play the guitar along the frett even though the technology behind the guitar works very differently.*

*What I would like to know more about: I would like to learn more about how a designer could make intuitive signifiers and find ways of mapping controls without misdirecting the user.*

*How this relates to the project I am working on: Like I mentioned previously affordances govern how we interact with any object or technology and in the casee of my guitar project I did not have the need to design and set-up a signifier to instruct the user on how the guitar worked. The inate idea of a guitar paved the path towards the user atomatically understanding how the technology worked.*

### Reading: Chapter 1 of Dan Saffer, Microinteractions: Designing with Details, Chapter 1 ###

*What I thought before: I've always looked to go big and tried playing with out of ordinary designs but through reading Dan Saffer's writing in this chapter, I understand that experimental designs are not always the best idea for the best end-user experience.*

*What I learned: I learnt that no matter how small or big a microinteraction model is, attension to detail is crucial as it is within these minor details that lies the secret to well-designed interaction models.*

*What I would like to know more about: Dan Saffer mentions that often times the attention of clients and stakeholders is focused on the big features instead of the small details that would enhance those features or improve the overall experience. I'd like know more on how a designer could tackle these situations while working professionaly*

*How this relates to the project I am working on: Multiple micro-interactions make up my project as a whole, I had to first figure out code to just sensing touch from the resistor and then add the detail of modulating the pitch based on pressure. Simple touch and pressure interaction triggers all of the events from my project*

### Reading: Scott Sullivan, Prototyping Interactive Objects ###

*What I thought before: I've always had notion that high-level programming skills are need to actually design physical interactive systems, my view on this has significantly changed. With creative coding becoming much more accessible along with a vast array of open-source libaries, it has become much easier for people to program dynamics interactive systems.*

*What I learned: I learnt that perseverance is a necessity when you're working on a design project. Scott mentions multiple situations where it seeemed linke the end of the road, but he had to keep trying to eventually breakthrough.*

*What I would like to know more about: I am curious about what Scott is up to after working on CAPYBARA.*

*How this relates to the project I am working on: Prototyping and beta testing was a crucial process I had to follow just like the author mentions about his project. Beta testing allowed me figure out errors in code that probably would'nt have noticed before demo without the test.


## Interaction flowchart ##

![Image](Chart.png)

## Process documentation


![Image](001.jpg)
*First analog signal read test from the force sensitive resistor.*

![Image](003.jpg)
*Testing note trigger with the speaker using the FSR.*

![Image](007.png)
*Code used in the testing metioned above.*

![Image](002.jpg)
*Velostat sheet resistance test.*

![Image](004.jpg)
*FSR taped on to the guitar frett and testing connection with the speaker.*

![Image](008.png)
*Code used for the test above.*

![Image](005.jpg)
*Close-up on how the FSRs were taped onto the frett board together along with the velostat sheet.*

![Image](006.jpg)
*Half way through to finishing the frett board using double-sided tape, electrical tape, aluminum foil and velostat sheets.*

![Image](009.png)
*Final code used to play different notes triggered by the different resistors on the frett.*


## Project outcome ##


### FSR Ukulele ###

### Project description ###

*This is a project replicating the idea of a guitar like musical instrument built with the microbit and a speaker. Notes are played according to the physical touch and pressure of the touch from the user on the instrument. The main purpose or use for this project would be educate children and beginners about the musical notes and pitch modulation in instruments.*

### Showcase image ###

![Image](Main2.jpg)

### Additional view ###

![Image](main3.jpg)

### Reflection ###

*The best part about the project that surprised me was how responsive the FSRs were, even after tapng them shut on top of the frett board. The part I'd like to improve upon is the cable management, it was pretty difficult to keep the wires hidden and also keep away from getting shorted*


*The original guitar project showed me how I could code all the different tones I needed to be triggered from reading an analog pin's value. Another tutorial gve me a great tip on using aluminum foil along with my velostat sheet to get a perfect pressure sensor.*


*TeachwithICT.com gave me good examples and information on how to program the microbit to play notes responsively(https://www.teachwithict.com/microbit-music.html)

The official BBC Microbiit Guide was also really helpful when I got stuck on how 3v power pins worked and if they could be shared. (https://books.google.com.au/books?id=fZ84DwAAQBAJ&lpg=PP1&ots=hdXuFWZPIh&dq=microbit%20and%20music%20&lr&pg=PP1#v=onepage&q=microbit%20and%20music&f=false)*


*I could definitely add more notes to the guitar but to really improve on the project, maybe I could've used other ways to modulate the pitch, for example by using the accelerometer on the board or maybe even an ultrasonic distanc sensor instead.

I could've also used conductive ink or copper tape instead of fighting with wires to channel all the signals from the sensors to the microbit.*
