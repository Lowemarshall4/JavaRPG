# JavaRPG

A 2D RPG made in Java

Necro-Caster is a 2D Role Playing game that I created my sophomore spring semester of college.
Inspiration for the gameplay was drawn from Pokemon style games as you walk around on a 2D tiled map and enter turn based battles to progress your character.
In my iteration, you are a necromancer that utilizes his unique items and abilities to shift the battles to your favor.

Necro-Caster's UI was created using a mix of Java's AWT and Swing API's to render the graphics to the screen following a MVC approach to the design architecture.
The 2D tilemap's were created by utilizing a tile map engine I created that allowed me to render entire multi-layer maps simply by representing
each layer as a matrix of integer ID's. Each ID corresponds to a specific .png that is rendered in place of the ID. These .png's can be found in
the resources folder of the project.

NOTE: This is not guaranteed to work on your machine, I'm still doing testing to confirm that these steps will work on other Windows machines.
      I could eliminate the use of the database as it is not necessary, but was included as a requirement for the course.

REQUIREMENTS TO RUN ON YOUR MACHINE (STILL TESTING)
1. Java Developement Kit & Maven
2. VSCode w/ Extension Pack for Java & Maven for Java plugins
2. Access to your own MYSQL database

STEPS TO GET RUNNING ON YOUR MACHINE (STILL TESTING):

1. Clone repository to your machine & open it with VSCode
2. Set up a local/remote MYSQL database
3. Run the included SQL file to populate database w/ required data (file found in JAVARPG/Necro_Caster/src/java/Database)
4. Change database connection code to connect to your own database (code to change found in JAVARPG/Necro_Caster/src/java/GUI/Controller @ line 522)
5. Use Maven plugin to compile the project
6. Navigate to JAVARPG/Necro_Caster/src/java/GUI/GameMain.java file and press run above main method

