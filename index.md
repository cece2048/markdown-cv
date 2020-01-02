---
layout: cv
title: Cecelia Chou's CV
---
# Cecelia Chou    
<br/>
- Software engineer with 3 years experience <br/>
- Financial related experiences
<br/>(financial transaction message exchange, stock trade system domain knowledge)<br/>
- Likes to follow the technology trend by blog and podcast in my free time<br/>
<div id="webaddress">
<a href="https://github.com/reiley2048">Github page</a> <br/>
	| <a href="https://stackoverflow.com/users/7041254/cece2048">StackOverflow page</a>
</div>

## Key Skills
_HUMAN LANGUAGE_
- Native Mandarin speaker.
- Fluent in English.

_JAVA_
- Three-year experience in Java. Familiar with the OO concept. <br/>
Spring framework, Spring boot, Mybatis, Redis.

_KOTLIN_

_LINUX_
- Experience in writing Shell scripts, mostly script to help deploy the product in the Linux server.

_JENKINS_
- Setup and maintaining the CI/CD system with Jenkins, create Jenkins custom plugin to customize the deployment process and write pipeline building script.

_SQL_
- Experience in working with Mysql, PostgreSQL, SQLserver. Also in memory DB: Redis 

## Professional Experience
`2019/03 - present`

_XTEAM Studio LLC, Software Engineer_

- Participate in developing and maintaining  the backend of our website with Spring framework 
- Build some slack bots to help maintainer interact with our system, which would send notifications to slack when something going wrong and provide options to them depending on the type of issue. I love doing this project, it's fun to build something that interacts with peoples.

`2018 - 2019/03`

_Boya Inc, Software Engineer_

I'm in charge of developing and maintaining the website crawling system, the goal here is to crawling for specific information in a variety URL, then actively send those information to registered consumers in minimum time.<br>
The difficulty of the crawling website is that these days most of them are generated dynamically, sometimes they also denied the request from the non-browser client to prevent DDOS attacks and crawlers. In that case, we need to come up with some workaround like mock a regular HTTP request with selenium or headless-chrome.

<br/>

`2016 - 2018`

_The Syscom group, Software Engineer_

- Set up CI/CD workflow with Gitlab, Jenkins, and Docker. <br/>
Integrating modules in various languages into one building workflow, which also deploy end product into different server including Linux and Windows.
- Involving in develope large-scale stock trading software systems, with average a million requests daily. The most crucial aspect of the stock the trading system is time efficiency, we have to deliver the request to trading center faster than other competitors, so our entire design is mostly focused on reducing the processing time. 
	Since we are a small team, so I have been involving in a lot of the lifecycle phases:
	1. Systems design: brainstorming and survey the strategies to minimize processing time
	2. Development
	3. Integration and testing: make tools to help integration test (setup IT environments)
	4. Deployment: deploy the final product to clients, and help train them with the system knowledge, make training documents.
	5. Maintenance: cooperate with the clients, help them solve the obstacles.
<br/>In all of those phases, I think the most difficult part for me is to cooperate with the clients, I have to be able to communicate the people in different domain (sometimes have no technology background), also I have to be careful about not promising for the services outside of our contract, that's some advanced human interaction techniques to me, but I learn how to do that by mimicking my co-works, they show me how to nicely initiate efficient communications.

## Education

`2012 - 2016`

_Bachelor of Information Management, National Dong Hwa University_

## Projects

_R6DBWebservice_

A middle layer web service to help APP frontend communicate with Cobol backend. Sending encrypted, signed Https requests to bank server. I learned how to customized block padding for encryption, secure Keys by storing them in the HSM server, initiate secure money transfer Https request to the bank, and the message transfer workflow in bank.

_ISO8583 Parser_

ISO8583 is a standard digital format using in the financial transaction, this parser constructs a message that's in ISO8583 format from other format and vice versa. I learned how financial transactions got initiated, processed, eventually realized in this project.

_Slack bots_

A slack bot that sends notifications to slack users, showing system data diagram and interact with the system.


<!-- ### Footer

Last updated: May 2013 -->


