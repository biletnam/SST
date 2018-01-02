# Story Seats Theater

## Description

I'm starting a community memory collection/fundraising project for the non profit historic theatre I work at called "Story Seats." Essentially, locals can purchase a personalized seat plate expressing a narrative memory they've had in the theatre i.e., "Ralph and Barb were the only ones here on Nov. 21, 1955 but they played the movie anyway", "Susie poured tomato soup off the balcony during a screening of Psycho." You get the gist.  
My vision is to also build a corresponding website that includes an interactive seat map where people can click through and listen to full interviews of these memories. I have the story collection under control, but my tech skills are horrendous (my iPhone 4 is doing great, thanks for asking). I'm looking for existing user-friendly platforms that I could use to build this, someone who would be interested in the project (it would pay), or at the very least, a ballpark quote for what it would cost to hire someone to make this so I can include it in some grant budgets.   

## Use Cases: User
![Users](https://i.imgur.com/0M2ccAk.png)

### 1.Security

**a.Login:** An account is needed to access SST, but guest access is also available  

**b.Create Profile:** Users can register into the application  

**c.User Profile:** Registered users would be able to add their address and payment details. Only registered user will be able to save and place orders of their personalized stories plates  

### 2.Story Seats

**a.Rooms:** User can see the available rooms of the theater with their own information. User can click the “Enter” option to see a detailed map of each of the available  

**b.Seats:** Once in a Room, user can select a seat that will take them to a more detailed view of that seat and the public stories  

**c.Stories:** In the Story Seats view, the user can see a visual representation of the posted stories that have been made public. User can hover the mouse on the story to see a written version of the interview and can click on top of it to listen to the interview  

**d.My Stories:** Once user clicks on the “Add” option of the previous screen, they can create and upload their own story, which will be stored under the “My Stories” tab. If desired, user can start the process of ordering a “Personalized Story Plate”   

### 3.Orders

**a.Plate Style Selection:** If the user clicks the “Purchase” option in one of their stories, then the application will show them a preview of all the available plates styles, so they can select the one they would like to order  

**b.Review My Order:** Once the user selects the style of the plate they would like to order, they will be redirected to the “Review Order” screen. Where they can fill the missing information (if needed) and finally submit their order  

**c.My Orders:** After placing the order, the user will be redirected to “My Orders” screen. Where they can track and manage their order  

## Use Cases: Administrator

![Administrator](https://i.imgur.com/fpjel24.png)

### 1.Security

**a.Roles:** Admin can activate and manage permissions given to a Role  
**b.Profile:** Admin can manage all the registered user profiles, changing their information and activating or deactivating accounts  

### 2.Story Seats

**a.Rooms:** Admin can add and edit available rooms of the theater (Required data for room needs to be specified)  
**b.Seats:** Admin can add seats and arrange them in the desired order in a default canvas  
**c.Stories:** Admin can manage all the available stories placed in one seat. Adding a title, style, description and audio file for each of them. Admin can also mark one story as public, so everyone should be able to see it on the “Stories” screen. Admin can also manage all the stories posted by the users  

### 3.Inventory

**a.Inventory:** Admin can manage the required “Materials” to produce a plate. I.e. the plates used to print the stories for then ship them to the users. This will help the system preventing fulfilling orders that cannot be fulfilled  
**b.Plates:** Admin can manage the available styles and prices of plates the user can select from when placing an order  
**c.Manage Orders:** Admin can mark an order as approve, fulfilled, shipped and delivered when needed. This could be linked to the shipping provider API if needed to keep status updated. This screen will be the final step before and order is processed  


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
