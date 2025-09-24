# Ex04 Places Around Me
# Date:24.09.25
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html

<html>
    <head>
        <title>
            MY CITY
        </title>
    </head>
    <body>
      <h1 align="center">
        <font color="red"><b>KAVANGARAI,PUZHAL</b></font>
      </h1>
      <h3 align="center"  >
        <font color="blue"><b>ISHWARYA M (25011836)</b></font>
      </h3>
      <center>
       <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="HOME" title="HOME" href="home.html" coords="1176,368,1230,399" shape="rect">
    <area target="" alt="JJ PALACE" title="JJ PALACE" href="palace.html" coords="1017,315,70" shape="circle">
    <area target="" alt="KVT. LITTLE MASTER CRICKET GROUND" title="KVT. LITTLE MASTER CRICKET GROUND" href="ground.html" coords="835,491,900,561" shape="rect">
    <area target="" alt="JMHI FISH MARKET WEST KAVANGARAI" title="JMHI FISH MARKET WEST KAVANGARAI" href="market.html" coords="1273,792,53" shape="circle">
    <area target="" alt="SRI NALLAGHU NADAR POLYTECHNIC COLLEGE" title="SRI NALLAGHU NADAR POLYTECHNIC COLLEGE" href="college.html" coords="995,90,1086,129" shape="rect">
</map>
      </center>
    </body>
</html>




home.html

<!DOCTYPE html>
<html lang="en">
<head>
  
 
  <title>MY HOME TOWN</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #004080;
      color: white;
      padding: 7px;
      text-align: center;
    }

    main {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #004080;
    }

    

    
  </style>
</head>
<body>

  <header>
    <h1>Home</h1>
  </header>

  <main>

    
      <h2>About my home</h2>
      <p>My home is a special place where I live with my parents and my little brother.
         It is a cozy house with a living room, a kitchen, two bedrooms, and a bathroom.
          The walls of my room are painted blue, my favorite color. 
          My favorite corner is near the window, where I sit and read books.</p>

<p>In front of my house, there is a small garden with colorful flowers and a swing. 
  
We also have a big mango tree that gives us shade. My home is filled with love and laughter. 
My mom and dad always make it feel warm and welcoming.I like spending time with my family at home.
 We play games, watch TV, and eat together. I also have a study table in my room where I do my homework.
  My home is my safe and happy place, and I love it very much.</p>
    
       
    
  </main>
</body>
</html>



college.html

<!DOCTYPE html>
<html lang="en">
<head>
  
 
  <title>Sri Nallalaghu Nadar Polytechnic College</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #005c80;
      color: white;
      padding: 7px;
      text-align: center;
    }

    main {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #005c80;
    }

    

    
  </style>
</head>
<body>

  <header>
    <h1>Sri Nallalaghu Nadar Polytechnic College</h1>
    </header>

  <main>
    <h2>About the College </h2>
    <p>Sri Nallalaghu Nadar Polytechnic College is located in Chennai Tamil Nadu country of India. Established in 1983, SNNPC is a Private college. The university is permitted through AICTE. Sri Nallalaghu Nadar Polytechnic College gives five guides throughout 1 stream specifically Engineering..Popular levels presented at Sri Nallalaghu Nadar Polytechnic College encompass Diplomas. Besides a sturdy coaching pedagogy, Sri Nallalaghu Nadar Polytechnic College is likewise a pacesetter in studies and innovation. Focus is given to sports past lecturers at Sri Nallalaghu Nadar Polytechnic College, Which is clear from its infrastructure, extracurricular sports, and national & global collaborations.

Philanthropic-minded Nadars of Chennai, with the primary goal to set up an instructional institute, fashioned the CHENNAI VAZHNADARGAL SANGAM in the year 1966 with the liberal contribution of the members, a vast area of forty-one acres of land changed into received withinside the Chennai, Nellore Trunk Road, simply 16km from Chennai.


Sri Nallalaghu Nadar and his brothers Sri. A.N. Ramasamy Nadar and Sri. A.N. Govindasamy Nadar contributed a sizeable amount to start the first educational institute of the Sangam, in memory of their beloved father Sri. TVA Nallalaghu Nadar.

Accreditation and Ranking at Sri Nallalaghu Nadar Polytechnic College
Sri Nallalaghu Nadar Polytechnic College was approved by the All India Council for Technical Education (AICTE).

Courses Offered at Sri Nallalaghu Nadar Polytechnic College
Sri Nallalaghu Nadar Polytechnic College courses are offered at various levels like Diploma Degrees i.e Diploma in Electronics and Communication Engineering, Diploma in Electrical & Electronics Engineering, Diploma in Computer Science Engineering (Lateral Entry), Diploma in Electrical and Communication Engineering (Lateral Entry), Diploma in Mechanical Engineering (Lateral Entry), etc. You can also find a brief overview of the different courses offered by the university across various disciplines with their specializations on the Course page.</p>

</main>
</body>
</html>



ground.html

<!DOCTYPE html>
<html lang="en">
<head>
  
 
  <title>K.V.T LITTLE MASTER CRICKET GROUND</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #803300;
      color: white;
      padding: 7px;
      text-align: center;
    }

    main {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color:  #803300;
    }

    

    
  </style>
</head>
<body>

  <header>
    <h1>K.V.T LITTLE MASTER CRICKET GROUND</h1></header>
    <main>
        <h2>Play Ground</h2>
    <p>Playgrounds are more than just a place for children to play and have fun. They are essential for the physical, social, and emotional development of children. In this essay, we will explore the importance of playgrounds in promoting physical activity, fostering social interactions, and enhancing cognitive skills. We will also discuss the benefits of outdoor play in improving mental health and overall well-being. Join us as we delve into the world of playgrounds and their impact on children’s lives.

</p>
<P>One of the main benefits of playgrounds is that they encourage physical activity. In today’s society, where children are spending more and more time indoors in front of screens, playgrounds provide a much-needed opportunity for kids to get outside and move their bodies. Climbing, swinging, sliding, and running around on the playground equipment helps children develop their gross motor skills and stay active and healthy.

In addition to physical benefits, playgrounds also offer important social benefits. When children play on a playground, they have the opportunity to interact with their peers, make new friends, and learn important social skills such as sharing, taking turns, and resolving conflicts. Playgrounds are a great place for children to practice these skills in a safe and supervised environment.</P>
</main>
</body>
</html>


market.html

<!DOCTYPE html>
<html lang="en">
<head>
  
 
  <title>JMHI FISH MARKET WEST KAVANGARAI</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #008029;
      color: white;
      padding: 7px;
      text-align: center;
    }

    main {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color:  #008029;
    }

    

    
  </style>
</head>
<body>

    <header>
    <h1>JMHI FISH MARKET WEST KAVANGARAI</h1></header>
    <main>
        <h2>Fish Market</h2>
        <p>A fish market is a place where sellers and buyers come together and sell or purchase fishes. There can be also whole sale trading and sometimes individual consumers can also buy.</p>
        <p>In country like India most of the fisherman live in village and sell their fishes at markets located in villages, district headquarters or at a crossroads are considered primary markets. They are usually selling their fish near to areas where fish are caught. Fishermen bring a variety of fishes (dominated by small fish from both open-water capture and from ponds) to the primary markets. Available sellers in the market also told us that in the early morning the prices of the fishes, availability of the fishes, types of the fishes are more than at the other time of the day.



        </p>
        </main>
</body>
</html>




palace.html

<!DOCTYPE html>
<html lang="en">
<head>
  
 
  <title>JJ PALACE</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #800066;
      color: white;
      padding: 7px;
      text-align: center;
    }

    main {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #800066;
    }

    

    
  </style>
</head>
<body>

  <header>
    <h1>JJ Palace</h1>
  </header>

  <main>
    <h2>Marriage hall</h2>
    <p>Jj Palace Marriage & Party Hall has been serving the community for many years as a leading Event Venues in Puzhal, Chennail Conveniently located near Kannappasamy Nagar, Kannada Palalyam this banquet hall blends sophistication and comfort, making it an ideal choice for special events. Established in 08-2022, rated 43 stars based on 465 reviews, Jj Palace Marriage & Party Hall has eamed a reputation for making every occasion memorable.

Services Offered

Jj Palace Marriage & Party Hall specializes in hosting a variety of events, offering ample space for large gatherings as well as intimate celebrations. Some of the services they provide include

Amenities: in addition to occasion services, Jj Palace Marriage & Party Hall provides a range of amenities to make your event unforgettable, such as Wheel Choir Accessible in Car Parking Common Bathroom, Wheel Chair Accessible Entrance And Exit
</p>
</main>
</body>
</html>
```
# OUTPUT

<img width="1920" height="893" alt="map" src="https://github.com/user-attachments/assets/d993933b-eb31-457c-94a0-7533c61c7e6f" />
<img width="1920" height="1080" alt="home" src="https://github.com/user-attachments/assets/108b45c7-1fbe-410e-8b85-08d0c810f16f" />
<img width="1920" height="1080" alt="college" src="https://github.com/user-attachments/assets/1ec54dd5-4258-42cf-8b77-2d078e0a9185" />
<img width="1920" height="1080" alt="ground" src="https://github.com/user-attachments/assets/dafabd3b-b7fb-456a-bdea-0b3c48210ee4" />
<img width="1920" height="1080" alt="market" src="https://github.com/user-attachments/assets/b4e4818f-eba2-4761-9de1-8c0b6d7dd2de" />
<img width="1920" height="1080" alt="palace" src="https://github.com/user-attachments/assets/fc199356-c189-491a-af2d-8f1aa9df9945" />







# RESULT
The program for implementing image maps using HTML is executed successfully.
