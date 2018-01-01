# Story Seats Theater

## Description

I'm starting a community memory collection/fundraising project for the non profit historic theatre I work at called "Story Seats." Essentially, locals can purchase a personalized seat plate expressing a narrative memory they've had in the theatre i.e., "Ralph and Barb were the only ones here on Nov. 21, 1955 but they played the movie anyway", "Susie poured tomato soup off the balcony during a screening of Psycho." You get the gist.  
My vision is to also build a corresponding website that includes an interactive seat map where people can click through and listen to full interviews of these memories. I have the story collection under control, but my tech skills are horrendous (my iPhone 4 is doing great, thanks for asking). I'm looking for existing user-friendly platforms that I could use to build this, someone who would be interested in the project (it would pay), or at the very least, a ballpark quote for what it would cost to hire someone to make this so I can include it in some grant budgets.   

## Use Cases: Administrator

![Administrator](https://i.imgur.com/fpjel24.png)

### 1. Security
#### 1.1 Roles
The application needs to have at least two initial roles created, User and Administrator.
##### 1.1.1 Create Role
##### 1.1.2 Read Role
##### 1.1.3 Update Role
##### 1.1.4 Delete Role
#### 1.2 Profile
Module needed to manage all the users accounts.
##### 1.2.1 Create Profile
###### 1.2.1.1 User Details
###### 1.2.1.2 Personal Details
###### 1.2.1.3 Address Details
###### 1.2.1.4 Payment Details
##### 1.2.2 Read Profile
##### 1.2.3 Update Profile
##### 1.2.4 Delete Profile

### 2. Story Seats
Module needed to create the virtual rooms with all the properties it involves.
#### 2.1 Rooms
![Rooms](https://i.imgur.com/wzGpI1O.png)  
Module that will allow the administrator to create the needed rooms.
##### 2.1.1 Create Room
##### 2.1.2 Read Room
##### 2.1.3 Update Room
##### 2.1.4 Delete Room
#### 2.2 Seats
![Seats](https://i.imgur.com/0DZozsb.png)  
Module that will allow the administrator to create and drag the seats in a default canvas of a room.
##### 2.2.1 Create Seat
###### 2.2.1.1 Place position of seat on Map
##### 2.2.2 Read Seat
##### 2.2.3 Update Seat
##### 2.2.4 Delete Seat
#### 2.3 Stories
![Stories](https://i.imgur.com/Lh0RnkI.png)  
Module that will allow the administrator to review and edit the different stories in each of the seats.
#### 2.3.1 Create Story
##### 2.3.1.1 Write 100 character summary
##### 2.3.1.2 Write extended interview
##### 2.3.1.3 Upload audio
#### 2.3.2 Approve Story
#### 2.3.3 Read Story
#### 2.3.4 Update Story
#### 2.3.5 Delete Story

### 3. Plates Module
Module needed to upload the different plate styles from where the user could select to place his order.   
#### 3.1 Plates Design
##### 3.1.1 Create Design
##### 3.1.2 Read Design
##### 3.1.3 Update Design
##### 3.1.4 Delete Design
#### 3.2 Reviews
Module needed to verify and edit the posted reviews in case needed
##### 3.2.1 Read Review
##### 3.2.2 Approve Review
#### 3.3 Plates Order
#### 3.3.1 Validate Payment
#### 3.3.2 Authorize Order
#### 3.3.3 Fulfill Order
#### 3.3.4 Ship Order

### 4. Inventory
Module needed to limit the raw materials nneded to produce and ship the plates.
##### 4.1 Create Asset
##### 4.2 Read Asset
##### 4.3 Update Asset
##### 4.4 Delete Asset

## Use Cases: User

![Users](https://i.imgur.com/0M2ccAk.png)

### 1. Security
![Login](https://i.imgur.com/Bj2AAfF.png)
#### 1.1 Profile
![Imgur](https://i.imgur.com/wofEKE4.png)
##### 1.1.1 Create Profile
![Create](https://i.imgur.com/IBrnnJC.png)
##### 1.1.2 Update Profile
##### 1.1.3 Close Profile

### 2. Story Seats
#### 2.1 Navigate Rooms
![Imgur](https://i.imgur.com/3UsUlzv.png)
#### 2.2 Navigate Seats
![Imgur](https://i.imgur.com/ZxB4V0k.png)
#### 2.3 Stories
![Imgur](https://i.imgur.com/FvAQfx3.png)
#### 2.3.1 Create Story
##### 2.3.1.1 Write 100 character summary
##### 2.3.1.2 Write extended interview
##### 2.3.1.3 Upload audio
#### 2.3.2 Navigate Stories
![Imgur](https://i.imgur.com/7Vu9EEB.png)
#### 2.3.3 Update Story
#### 2.3.4 Delete Story

### 3. Plates Module
#### 3.1 Order Plate
![Imgur](https://i.imgur.com/7Vu9EEB.png)
![Imgur](https://i.imgur.com/OTjeX0t.png)
![Imgur](https://i.imgur.com/Ixl0q74.png)
#### 3.2 Track Plate
#### 3.3 Return Plate
#### 3.4 Write Review

## Non-Functional Requirements

### -Responsive
Mobile Friendly Version and Possible Mobile APP

### -Secure Payment
PayPal, Credit Card, Visa Checkout and MasterPass

### -Architecture
RESTfull oriented project hosted on AWS, to allow cross platform future clients development

### -Security
SSL certificate implemented in the Tomcat Server

### -Technologies
Java Spring-Boot project running on an embedded Tomcat server, with a MySQL Database Server

## Balsamiq Mockups
https://balsamiq.com/  
**-User:** Mapirisoft  
**-Key:** eJzzzU/OLi0odstPdypNr6rxTSzILMoszk8rqTEyMrA0MDYyMDCocTYEkgBUQA4f  

## ArgoUML
http://argouml.tigris.org/

## Class Diagram

## Entity Relationship Diagram
