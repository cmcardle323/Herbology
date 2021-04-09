4/9/2021:

Herbology is a plant information reference chart which will allow you to maintain a running database of both all encountered plants as well as active (alive) plants. 

User Stories
As a User I can;
	create and login into a persistent account,
	view my saved and my actively tracked plants,
	view quick details about active plants,
	view plant specifics in a detailed view,
	view images of plants,

Difficulties
	Formatting: jumping from regular java DAO to Spring MVC required completely re-writing all previous work.
		I began by trying to salvage the hours of work already completed on my HTML and CSS as well as the basic database connection scripts. 
		Most of my methods could be adapted for Spring and were Frankensteined into a rough webpage I could get to run on Tomcat but was not communicating with my database.
		I struggled with trying to implement database persistence with my monster project, but was not able to get it to work. 
		I started a new test Spring project to work alongside parallel to my monster project. 
		Finally got my test Spring project to display data from my database, but improper file structure was interfering with my Spring Boot Configuration.
		I attempted to change the file structure manually but ended up breaking my code, trash and start anew, take 2. 
	Structure: Bad file structure caused me to create a new project 4/8.
		The @SpringBootApplication annotation was in a package that caused it to not scan subpackages. I re-created a new project with proper file structure and copy/pasted most of my code back over. 
		With proper file structure, coding the rest of the project was a breeze and worked as expected with my database. 
	TIME: Adequate time was not provided post Spring MVC lectures, which were the most crucial and important lectures.
		I spent many nights working on the project preemptively in an attempt to stay ahead of the crunch. 
		In the end, all the work I did do was a detriment as it was just code that I fiddled with for hours before finally discarding. 
		Once we learned about Spring MVC, we had two more weeks to complete the project, yet we still had Spring lectures in that time. 
		I again spent many more nights working to complete the project, often into the early morning of the next day which just made lectures harder to concentrate on. 
		Had I known the project was a Spring MVC project from the start, I could have saved myself a lot of time, stress, and effort.


