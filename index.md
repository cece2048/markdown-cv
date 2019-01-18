---
layout: cv
title: Riley Chou's CV
---
# Riley Chou    
<br/>
- Software engineer with 2 years experience
- Experienced in implementing multi-threaded, large-scale, responsive microservices.
- Financial related experiences
<br/>(financial transaction message exchange, stock trade system domain knowledge)
- I enjoy turning abstract concept into concrete, elegent, readable architecture.<br/>
  Likes to follow the technology trend by blog and podcast in my free time, <br/>
  occasionally reading some books about software design, reverse engineer and neural network.
<div id="webaddress">
<a href="https://github.com/reiley2048"> https://github.com/reiley2048</a> 
	| <a href="https://stackoverflow.com/users/7041254/riley2048">https://stackoverflow.com/users/7041254/riley2048</a>
</div>

## Professional Experience

`2018 - Present`

_Boya Inc, Software Engineer_

I'm incharge of developing and maintaining the website crawling system, 
the goal here is to crawling for a specific information in variety URL, 
then actively send those information to registed consumers in minimum time.<br>
The diffucalty of the crawling website is that these days most of the them are 
generated dynamicly, sometimes they also denided request from non-browser client 
to prevent DDOS attack and crawlers.
In that case we need to come up with some workaround like mock a regular 
http request with selenium or headless-chrome.

<br/>

`2016 - 2018`

_The Syscom group, Software Engineer_

- Setup CI/CD workflow with Gitlab, Jenkins and Docker. <br/>
Integrating modules in variety languages into one building workflow, <br/>
which also deploy end product into different server including linux and windows.
- Involving in develope large-scale stock trading software system, with average a million request daily. <br/>
The most crucial aspect of the stock trading system is time efficiency, we have to deliver <br/>
the request to trading center faster than other competitor, so our entire design is mostly focused on reducing the processing time. 
	Since we are a small team, so I have been involving in a lot of the lifecycle phases:
	1. Systems design: brainstorming and survey the strategies to minimize processing time
	2. Development: implementing function without big framework like Spring <br/>
	(annotation monitoring cost time)
	3. Integration and testing: makes tools to help integration test (setup IT enviroments)
	4. Deployment: deploy final product to clients, and help tranning them with the system 
		knowledge, make trainning documents.
	5. Maintenance: cooperate the clients, help them solving the obstacles.
<br/>In all of those phases, I think the most difficult part for me is to cooperate with the clients, I have to be able to communicate the people in different domain (sometimes have no technology background), also I have to be careful about not promising for the services outside of our contract, that's some advanced human interaction techniques to me, but I learn how to do that by mimicking my co-works, they show me how to nicely initiate efficient communications.

## Education

`2012 - 2016`

_Bachelor of Imformation Management, National Dong Hwa University_

## Projects

_R6DBWebservice_

A middle layer webservice to help APP frontend communicate with Cobol backend.
<br/>Sending encrypted, signed Https requests to bank server. 
<br/>I learned how to cusomized block padding for encrytion, secure Keys by storing them in HSM server, 
<br/>initiate secure money transfer Https request to bank, and the message transfer workflow in bank.

_ISO8583 Parser_

ISO8583 is a standard digital format using in financial transaction, this parser construct message that's in ISO8583 format from other format and vice versa.
<br/>I learned how financial transaction got initiated, processed, eventually realized in this project.

_UI For Trading System_

UI written in JavaFX, front-end for placing orders to backend stock trading system.

## Key Skills
_JAVA_
- Two year experience in Java. Familiar with the OO concept. <br/>
Spring framework, servlet, building reactive microservices RxJava.

_LINUX_
- Experience in writing Shell scripts, mostly script to help deploy product in Linux server.

_JENKINS_
- Setup and maintaining CI/CD system with Jenkins, create Jenkins custom plugin to <br/>
customize deployment process and write pipeline building script.

_SQL_
- Experience in working with Mysql, PostgreSQL, SQLserver. 
- Redis 

_OpenCV_
- Experience in using OpenCV as a tool to track human's pupils movement via webcam and <br/>
after we got pupils location data, then calculate their relative vector to decide if the   
person's gaze is fixated at a point in the screen or not. This is truly a difficult challenge   
for me at the time, because back then I have zero knowledge about Computer vision and   
video/audio processing, but through a lot of researching and paper reading, we still   
managed to delivery the prototype on time.

<!-- ### Footer

Last updated: May 2013 -->


