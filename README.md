Cloned From https://github.com/SpaceCowboyLive/joyviz
# joyviz
Joystick Visualizer is an offline version based on the code of Anton Natarov (https://linkedin.com/in/antonnatarov/en)

Original application can be found here (https://tealyatinasite.appspot.com/joystick/)

Original documentation can be found here (https://web.archive.org/web/20220818185347/http://www.teall.info/2019/03/joystick-visualizer.html)

 changes made with QWEN 3.8 27B in LMStudio with VS Code, Prompt:
 hi analyse the respository , it is a javascript code for browser based device axis and button overlay. 
 I can be integrated into obs for example to show how the conbtroler oder joystick is used in real time. Please do the following changes:
- update the code to beable to handle more than 4 deivces when not using a chrome based browser
- keep the numbering of the devices but the overlay is bound to the hardware ID of the selected device. 
When regeneration the overlay the number should be define from the hardware ID so that the overlay is kept konstant even if the order of the devices changes"
To be Able to use more than 4 devices use a non chromium browser such as firefox.
To Use this with obs you have to add firefox as a programm source and add a chromakey filter

