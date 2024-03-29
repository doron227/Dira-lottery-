## Description:

The aim of the four python scripts is to alert the user about the existence of potential lotteres in the city that are of interest and at an appropriate price for the  user. Apartment at a discount (price per tenant) or  "Discount Apartment" is the flagship program initiated by the State of Israel with the goal of making it easier and accessible for non-home-owner people to purchase their first apartment under preferential conditions. "Discount apartment" is a general term for the variety of housing programs within the Ministry of Construction & Housing and the Israel Lands Authority. It’s definition includes target price, reduced price, price for tenants and apartments for rent.

## The process includes several steps:

* Issuing a certificate of eligibility to participate in the program
*  Registration for lotteries
* The lottery
* Exceptions committee for winners (if necessary)
* Financing the apartment and getting a mortgage
* Choosing an apartment and signing a contract
* Waiting for the apartment to be occupied (the winners will be informed about the progress of the project)

## Why ?
The registration dates for the various projects are published in the press and on the Ministry of Construction & Housing’s website. After the publication of the dates, the lottery registration for said project opens for at least 8 days, and terms of the registry are published on the website. Participants holding a valid certificate of eligibility on the day of registration will be able to register for the project through the lottery registration website. The issue here is that the contestant has to enter the lottery either through the Ministry of Construction & Housing website or by staying up to date with the press for every lottery period. They would need to check which lotteries are held, in which cities and what the price per square meter in each lottery is. The contestant has to search  through a lot of information on the lotteries, most of which might not be relevant to his personal needs and can present two main problems: 
a) A huge time commitment and investment. 
b) The contestant may miss out on  relevant lottery opportunities. 


## requirements 

* pyton 3 

### Dira lottery relies on the following packages:
* os
* tkinter
* customtkinter
* tkinter
* json
* pandas
* re
* random
* smtplib
* sys
* pathlib
* Numpy
* matplotlib.pyplot
* Requests
* email.mime.text
* email.mime.multipart MIMEMultipart
* email.mime.application


## Usage:
The user needs to download the four Python files to the same directory and run the file gui_dira

**When the user runs the code, a window will appear. In this window the user will be asked to fill in several details.**
<p align="center">
<img src="https://github.com/doron227/Dira-lottery-/blob/main/images/number1.png" width="400" height="400" />
 

The user can enter up to 3 cities with lotteries where he wishes to be alerted about. Each of these choices include a city (blue rectangle) and a price per square meter that he is willing to pay for the specific city .
 
<p align="center">
<img src="https://github.com/doron227/Dira-lottery-/blob/main/images/number2.png" width="500" height="500" />
 

The user has to enter an email - to which he will receive the notifications and the frequency of receiving the emails.
Also, the user has to choose when to stop receiving the emails automatically.
  
<p align="center">
<img src="https://github.com/doron227/Dira-lottery-/blob/main/images/number%203.png" width="450" height="200" />
    
**In addition** to the email informing about upcoming lotteries in a given city at a given price chosen by the user, the user will receive an additional email with a weekly/bimonthly/monthly update (according to his choice). This email contains a pptx presentation which contains information about what is the national average price per square meter in lotteries (in all cities),  Maximum and minimum price per square meter. In addition to this information, there is data about the average prices in the cities the user has selected.
