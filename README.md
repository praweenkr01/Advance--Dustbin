<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="dustbin">
        <h1>Advance Dustbin</h1>
    </div>
    <div><h2>Introduction</h2>
        <p>In this project, I have designed a simple system called Advance Dustbin using Arduino,
            Ultrasonic Sensor, and Servo Motor, where the lid of the dustbin will automatically open
            itself upon waste coming ear to it. The Advance dustbin is a carefully designed solution
            that solves the social issue of people avoid touching bin to put waste in it.
            Throwing Garbage in the bins/dustbins is a good practice and we do not require to
            convince people to put their waste product in it.but During this pandemic (Covid -19)
            ,keeping safe distance from every contaminated things or person is necessary.
            Therefore, the aim of our project was to make a dustbin where we don’t need to even put
            our feet on paddle of bin to open.</p>
        </div>
        <h2>Preview</h2>
         <div id="vidio">
             <iframe src="https://www.youtube.com/embed/CQkZaaJPbcw"  width="560" height="315" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
         </div>
        <div>
            <h2>Problem Considered</h2>
            <p>
                As the world is Advancing, there is one stinking problem we have to deal
                with. Garbage! In our daily life, we see the picture of garbage bins being overfull and all
                the garbage spills out. This leads to the number of insects and mosquitoes breed on it. A
                big challenge in the urban cities is solid waste management and lake of people’s interest
                to pull the cover of bin to throw their waste, not only in India but for most of the
                countries in the world. Hence, such a system has to be build which can eradicate this
                problem or at least reduce it to the minimum level. This project gives us one of the most
                efficient ways to keep our environment clean and green. By using this advance dustbin
                we can give a pollution free environment and a disease free surroundings.
            </p>

        </div>
        <div>
            <h2>Objective</h2>
            <p>
                The main objective of this project is to open lid of bin when senses something has came
                near to be put in the bin. Nowadays people are using more products including food items,
                industrial products, medicines and, plastic materials. After expiry of these items they are
                put it into a dustbin for disposal. Without proper maintenance of dustbins, these expiry
                items can create epidemic diseases among people and pollution to the ambience. And
                other person who will come to put something in it will avoid opening the bin So the
                dustbins sholud be such which open itself after detection to ensure cleanliness. This paper
                presents an Arduino based adv dustbin . The Arduino Uno controller is used to read the
                dustbin levels with the help of Ultrasonic sensor. After 100% filling of dust and waste
                items, red LED glow so to collect the garbage deposited. Arduino Uno contains
                Atmega328p-pu IC. . Embedded C is used to program the controller and html is employed
                for creating the web page.
            </p>

        </div>
        <h2>Working</h2>
        <div>
            <p>
                The fullness status of the bin is determined by calculating the distance between the lid of
                the bin and the trash by using an ultrasonic sensor. A distance threshold will be set
                according to the bin dimensions. When the ultrasonic sensor indicates that the bin is full,
                then a microcontroller board will control a bins lid. The location of the bin is predefined
                by the sanitary worker who will identify the filled bin by Red LED light glow. The
                system return to default operation when the bin is emptied by the users.
            </p>
        </div>
        <h2>Components</h2>
        <div>
        <ul id="component">
            <li>Arduino board</li>
            <li>Ultrasonic Sensor</li>
            <li>Servo Motor</li> 
            <li>Red LED</li>
            <li>Green LED</li>
        </ul>
      </div>
      <h2>Results</h2>
      <div>
         <p>When the waste object is brought near to the lid, due to Ultrasonic Sensor the object is
            detected and the lid opens for a certain time and then the lid automatically will be closed.
            Thus the lid can open automatically without manual operation. Hence manual work is
            reduced and automatically is carried out. Hence it is very useful in our day to day life.
            green LED will be signify that dustbin is not fulll and if RED led is glowing the bin will
            not allow anyone to put anything inside it.</p>
      </div>
      <h2>Constraints</h2>
        <ul>
            <li>Continuously power supply/using battery.</li>
            <li>Malfunctioning in bad weather and can even be damaged.</li>
            <li>Currently no AI,for proper detection hand coming for throwing waste in
                dustbin.</li>
        </ul>
        <h2>Future Work</h2>
        <div>
            <p>
                The AIoT fusion to enable devices to learn, reason, and process information like humans
                so that open covers only when pattern of motion to of throwing things is detected.
                Add more function to provide variety of features like sending signal to phone when bin is
                full.
            </p>
        </div>
</body>
</html>
