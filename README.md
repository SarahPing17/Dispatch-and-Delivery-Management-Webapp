# Dispatch-and-Delivery-Management-Webapp
Dispatch &amp; Delivery Management Webapp from team 3

# Product Requirements Document
## Overview
### Objective
- Service: We are a company that provides parcel delivery service by drones and robots. 
- Project goal: We want to design a web application for users to choose the delivery options, place an order, and track the delivery.
### Assumptions
- We consider the senders and recipients in San Francisco only.
- Most users will access this service via web application.
- We assume we have unlimited number of drones and delivery robots
- We assume this delivery procedure for simplicity: Both of the drones and robots will go to the client’s site to pick up packages once a client places an order, then go back to our warehouse (station) for security check/recharge/refuel, then deliver the package.

## Success criteria
Once this project is completed, users in San Francisco will be able to send packages using our drones and delivery robots within the same city. Using our website, they can choose delivery options that best fit their needs, place orders, and track the packages. 

## Scope
### User stories and requirements
Requirements      | Priority(P1>P2>P3)     | Notes to Front/back end tech lead:     |
---------- | :-----------:  | :-----------: |
As a user, I can register a new account.<br>- Registration info:<br>-- First name<br>-- Last name<br>-- Username<br>-- Password| P1     | Please check the registration info     |
As a user, I can log in to the website.     | P1     |     |
As a user, I can enter shipping information. <br>- Info includes: <br>-- Package weight<br>-- Number of packages<br>-- Sender’s name and address<br>-- Recipient’s name and address| P1    | Please check this info     |
As a user, I can choose from multiple delivery service options provided by the website. <br>- Basic options:<br>-- Option 1: express delivery - drone (less than 1 hour)<br>-- Option 2: economy delivery - robot (cheaper than the current delivery companies in the market)| P1    | Please check these options. The idea of the basic options we provide is that users can only pick between fast (drone) and cheap (robot) delivery.     |
As a user, I can choose from multiple delivery service options provided by the website.<br>- Advanced options:<br>-- Option 3: economy robot second-day delivery<br> --Option 4: economy robot 3-day delivery|P2|We can talk about these advanced options later. The idea is that we can provide even cheaper options than option 2. This can be done by collecting a bunch of packages in the warehouse and using one robot to send them all at once later.|
1s a user, I can enter my credit card info and place an order.| P1| |
As a user, after placing the order, I can get a tracking number.| P1| |
As a user, without logging in, I can track my order by putting in my tracking number. I can see tracking info:<br>- Basic tracking info:<br>-- Tracking log|P1|Please check the basic tracking info|
As a user, without logging in, I can track my order by putting in my tracking number. I can see tracking info:- Advanced tracking info:<br> --a map to show the real time location of my package on the tracking page.|P3|We can discuss later|
As a user, I can see my profile after login. In my profile:<br>- Basic user profile:<br>-- Username<br>-- Order history<br>--- ender’s info, recipient’s info, tracking number, status, package into, order price |P1|Please check the basic user profile|
As a user, I can see my profile after login. In my profile:<br>- Advanced user profile:<br>-- In my order history, I can click the tracking number to go to the tracking page.|P2|We can discuss later|
 As a user, I can log out.|P1| |

     
### Future enhancements
- In reality, the company has a limited number of drones and robots. Some delivery options may not be available when we’re out of drones or robots. 
- When the volume of drones and robots are low in some warehouse stations, our backend service will alert our operations team to move devices to those stations and best balance the volume between different stations.
- We have a certain number of drop off stations in the city. Customers will be provided with a lower cost option to ship the package when they choose to drop off their packages.
- Create a mobile application that users can use.
### Out of scope
- We do not consider senders and recipients outside of San Francisco.
- We do not consider currencies other than US dollars.
- ...
