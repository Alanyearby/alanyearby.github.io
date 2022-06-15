## Welcome to my eportfolio that showcases the knowledge and skills developed during the computer science program at Southern New Hampshire University.

I am Alan Yearby, and I am currently pursuing my bachelor’s degree in Computer Science from Southern New Hampshire University (SNHU). While attending classes for my degree, I am serving in the United States Army as an instructor of Infantry leaders. I’ve been in the Computer Science program for three years. Any allocatable time not spent in the field training, or away from home was spent to classwork assignments. While in the program, I learned the importance of time management, how broad the Computer Science field is, and the importance of Computer Science in daily life. 
In my future career, computer science provides the benefit of providing more beneficial job opportunities while in the Army. I plan to use my Computer Science degree to pursue a career as a tech Warrant Officer. My future career will be specializing in the implementation of software and hardware as a leader, trainer and advisor. 
As I started my program of Computer Science, my goals have shifted considerably. In the past, I aspired of getting out the Army to go into programming as my new career. This goal has shifted due to the additional knowledge on the field of Computer Science as a whole. I realized that the scope of Computer Science is broad and covers an abundance of career opportunities where I would be able to use my knowledge accordingly. With this added perspective, I realized that I didn’t need due end my service to be in the Computer Science field. My career goals now orient towards staying in the Army as Warrant officer Developer Technician. While in the Army I will be able to develop and implement software and hardware capabilities and is a leader, trainer, and advisor to commanders at all levels (U.S. ARMY RECRUITING COMMAND, 2022).


# Code review 
As a starting point, I went about a code review over my enhancement plans amd what I though was lacking. Three past assignments in three categories were to be enhanced, those categories being: Software engineering and design, Algorithms and data structure, and Databases.

https://user-images.githubusercontent.com/76213355/173702147-061a9093-486a-4224-8405-9ffb38c4d632.mp4

# Software engineering and design 
The artifact is a project designed to create a 3d scene with texture mapping in OpenGl. The artifact was created in May of 2021 and titled ‘Texturing objects in a 3D scene’.
The selection of this artifact derived from the complexity of the code and the relation to the course outcome that were to be selected. I believe that implementing contextual, in-code comments that facilitate the readability of an OpenGl project to be the best bet in meeting the course outcome detailed in [CS-499-01].
There is a lot going on in the scene making for OpenGl to include texture components, with the inclusion of detailed comments in-code this will showcase my ability to understand code in software development. Ultimately, this artifact was improved through the addition of beneficial in-code comments designed to improve the readability of the code. 
Overall, I believe I have met the course objectives that were planned during the enhancement in Module One. As of now, I have no updates to my outcome coverage plan. 
In reflection, I learned as I went commenting the code, that a lot can be confusion throughout everything going on in a multipage OpenGl project. With the addition of detailed in-code comments, reviewers, such as myself are benefitted with useful in-code comments and won’t have to guess towards the meaning of the code.

<img width="1512" alt="Screen Shot 2022-06-14 at 7 34 27 PM" src="https://user-images.githubusercontent.com/76213355/173706537-406a5856-7c38-4602-9e19-8ad1a9e6c312.png">

Zip file including the enhancement:

[Milestone 2 enhancement.zip](https://github.com/Alanyearby/alanyearby.github.io/files/8904482/Milestone.2.enhancement.zip)

# Algorithms and data structure
The artifact I have selected for Algorithm and Data Structure category is an application designed to calculate a user’ grade point average (GPA) through the input of corresponding letter grades and give the user a relating honor qualification. The artifact is titled ‘GPA Honors Calculator’ and was created during the CS 312 course during my CS program. 
I selected this artifact for my ePortfolio due to the value the application can have to a user and connection the app has towards the course outcome of CS-499-04. Specifically, how the application is structured to allow input of letters and give a corresponding GPA along with a qualifying for honors, showcase my skills in algorithms and data structure through the complexity of the application that retrieves valuable information for the user. The artifact was improved by adding the ability to retrieve more letter grades for a more comprehensive GPA and a loop to mediate incorrect inputs. 
I believe I met the course objectives I detailed during the code review and enhancement plan. CS-499-04 details that demonstrate innovative techniques that deliver value, of which I assume I did. As of now, I have no updates to my outcome-coverage plans. As I went about creating the artifact, I realized that creating applications designed to bring value to the user can be very rewarding. I found that I had a substantial amount of fun through the enhancement of this artifact. I faced the challenge of what areas of the application needed the most improvement, I believe I made the correct choice. 

<img width="1512" alt="Screen Shot 2022-06-14 at 7 40 47 PM" src="https://user-images.githubusercontent.com/76213355/173707265-d840712a-7a0a-434f-96fa-0409b718fa95.png">

<img width="1512" alt="Screen Shot 2022-06-14 at 7 53 38 PM" src="https://user-images.githubusercontent.com/76213355/173708952-d9225414-f5a4-4c70-8db0-6a833d717389.png">

# Databases

This artifact is a depiction of practices and techniques of databases using ‘Mongodb’. It was first created during CS 340, since then I have learned additional practicality, relating to how databases are implemented in daily life from experience. 
Comparatively speaking, this artifact was chosen due to the area of improvement I could show. When I took the CS 340 over a year ago, I used a Windows operating system to go about the techniques showcased in the class. Now I am implementing the knowledge I learned, as well as additional practices on a Mac operating system. Firstly, to get ‘Mongodb’ on a Mac OS I had to go through a third-party application called ‘Homebrew’ and install ‘Mongodb’ through the terminal. This artifact was improved via additional databases of interest to me. I implemented practical querying techniques to retrieve useful information relating to movies. I secured the database by adding user roles with password protection.
I believe I met the course objectives through my implementation plan associated with the course outcome of [CS-499-05] that focused on security mindset with an additional focus on practicality. As of now, I have no updates on my outcome-coverage plan. The process of enhancing/modifying the artifact required me to think differently. Using a different OS required me to think differently. I learned a lot about using techniques for the same results but in different ways. I encountered a roadblock initially trying to get ‘Mongodb’ on my OS, this was fixed through persistence. 


<img width="1512" alt="image" src="https://user-images.githubusercontent.com/76213355/173709216-ff0127c2-824d-412e-8a92-196ad7094896.png">

Implementing ‘Mongodb’ on a Mac operating system, I went about retrieving an extensive .json detailing movies with the intention of providing detailed query’s and security protection for the database created for the collection. In the image above I went about essentially loading the .json file into my Mongodb client with the following ‘mongoimport’ commands:

```mongoimport –jsonArray –db movie –collection movielist –file /Users/alanyearby/Desktop/MongoPractice/Movies.json
```

<img width="1512" alt="image" src="https://user-images.githubusercontent.com/76213355/173709245-f1b465fa-4746-44d2-b55e-0ec97fd23ede.png">

Confirmation of the database and use of the database to include the subsequent collection took place with the following commands:
```show dbs
use movie
show collection
```

<img width="1512" alt="image" src="https://user-images.githubusercontent.com/76213355/173709272-c9135891-fb6a-46cc-9f3d-d9b8eb97fbf5.png">

The image above depicts the confirmation of the data in the collection ‘movielist’ through the following command:
```db.movielist.find().pretty()```


<img width="1512" alt="image" src="https://user-images.githubusercontent.com/76213355/173709293-a363e7b6-2104-41b1-a1cb-a656c36a26f5.png">

The above image shows the inclusion of an additional database with a more detailed information to query. 

<img width="1512" alt="image" src="https://user-images.githubusercontent.com/76213355/173709314-5726735e-24cb-4f7d-bcaa-f4abf58bc8f5.png">

The image above shows the detailed query command in ‘mongodb’ to find specific information using the following command:
```db.movieRating.find({“genres”: “Action”: “Keanu Reeves”}).pretty()```


<img width="1512" alt="image" src="https://user-images.githubusercontent.com/76213355/173709338-7bb307b9-859d-4dda-b8d4-ba06d0e76f38.png">

The image above depicts further useful querying for specific information, in this case movie ratings higher/greater than 8.0 through the following command:
```db.movieRating.find({“imdbRating”: {$gt: 8.0}}).pretty()```

<img width="1512" alt="image" src="https://user-images.githubusercontent.com/76213355/173709346-3b511164-591d-448e-9b80-aad497ab01f1.png">

Finally, the image above shows the inclusion of security measures to give a user authorization via the following command:
```db.createUser({user: “alanyearby”,pwd: passwordPrompt(),roles:[{role: “readWrite”, db: “movies”}]})```


## References 



Bradley, G. (2022, March 21). Top 6 Computer Science Trends in 2021. Code a New Career | ComputerScience.Org. https://www.computerscience.org/resources/computer-science-trends/


F. (2022). GitHub - FEND16/movie-json-data: Filmdata i JSON-format från IMDb. GitHub. https://github.com/FEND16/movie-json-data

Film.JSON. (2022). Gist. https://gist.github.com/saniyusuf/406b843afdfb9c6a86e25753fe2761f4

U.S. ARMY RECRUITING COMMAND. (2022). 170D - Cyberspace Capability Developer Technician. https://recruiting.army.mil/170d/
