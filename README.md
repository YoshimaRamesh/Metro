![image](https://img.shields.io/badge/Contributors-15-red?style=for-the-badge&logo=github)
![image](https://img.shields.io/badge/Branches-30-yellow?style=for-the-badge)
![image](https://img.shields.io/badge/Spring%20Boot-v2.5.6-success?style=for-the-badge&logo=spring)
![image](https://img.shields.io/badge/Angular-v8.3.8-red?style=for-the-badge&logo=angular)
![image](https://img.shields.io/badge/Maven-v3.8.1-informational?style=for-the-badge)



<h1> Chennai Metro Travel Planner and Ticket Booking </h1>
Chennai Metro Travel Planner and Ticket Booking(CMTPTB) is a website that helps metro users to view travel plan, book tickets and buy travel-card. Admin: Admin is a person who has control over lines and stations,ticket policy. Customer: Customer is person who can create account  by signing up and login to account to view source and destination stations and plan their travel,they can book tickets online by using wallet and travel-card.

<h2>Getting Started</h2>
<ul>
<li> Start with this Github Repository</li>
<li>Git clone to directory of your choice $ git clone https://github.com/sainikhilll/cps.git</li>
<li> Open CMTPTB-frontend folder in VS Code</li>
<li>Run npm install in terminal.</li>
<li>Run ng serve to launch frontend.</li>
<li>Open SQL Script which is present in Database folder in MySQL workbench and run the script to create all the required tables</li>
<li>Import the CMTPTB-rest in STS and Change Database configurations in application.properties</li>
<li>Start the Application from CMTPTBRestApplication.java file.</li>
<li>Access the application from Browser</li>
</ul>

<h2>Technologies Used</h2>
<h3>Frontend</h3>
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>Angular</li>
  <li>Bootstrap</li>
</ul>

<h3>Backend</h3>
<ul>
<li>Java</li>
<li>Rest</li>
<li>Spring Framework</li>
<li>Spring Boot</li>
<li>Spring Data JPA</li>
<li>Maven</li>
<li>Hibernate</li>  
</ul>

<h3>Database</h3>
<ul>
<li>MySQL</li>
</ul>

<h3>DevOps</h3>
<ul>
  <li>AWS</li>
  <li>Git</li>
</ul>

<h3>Testing</h3>
<ul>
  <li>Postman</li>
</ul>

<h3>IDE</h3>
<ul>
<li>Spring Tool Suite IDE</li>
<li>Visual Studio Code</li>
</ul>

<h2>Features</h2>

<h3>Admin</h3>
<ul>
<li>As an admin, I can access the application using a default admin account name and password, so that I can manage the metro station details and ticket details.</li>
<li>As an admin, I can view the list of lines with start station, end station, number of stations and total travel time, so that I can know the list of lines available.</li>
<li>As an admin, I can add a new line by providing the line name, so that I can create a new line.</li>
<li>As an admin, I can modify the new line name, so that I can manage when line name is changed or when there is a correction required in the line name.</li>
<li>As an admin, I can view the list of all metro stations, so that I can have a view of the stations available</li>
<li>As an admin, I can add a new station with station name, so that I can add when a new station is introduced.</li>
<li>As an admin, I can update a station name, so that I can manage when station name is changed or when there is a correction required in the station name.</li>
<li>As an admin, I can include a station to a line in a specific position with distance from the previous station, so that I can include a station in between existing station.</li>
<li>As an admin, I can remove a station from a line, so that I can rearrange the station in the way it is required to be.</li>
<li>As an admin, I can view the distance ranges and its ticket price, so that I can view the current ticket pricing policy.</li>
<li>As an admin, I can add a distance range with prices, so that I can modify the current ticket pricing 
policy.</li>
<li>As an admin, I can remove a distance range, so that I can modify the current ticket pricing policy.</li>
<li> As an admin, I want to logout after login, so that I can avoid unauthorized access.</li>

</ul>    
<h3>Customer</h3>
<ul>
<li>As a customer, I want to sign up using name, email, password and confirm password, so that I can start using the application with my personalization.</li>
<li>As a customer, I want to login using email and password, so that I can login.</li>
<li>As a customer, I want to view the current balance in my wallet, so that I can know the money available in my wallet.</li>
<li>As a customer, I want to transfer money from my bank account to my wallet, so that I can purchase a ticket or travel card.</li>
<li>As a customer, I want to view the travel plan with all instructions having start station, intermediate stations, all connect stations and end station so that I can have clear instructions for my metro journey.</li>
<li>As a customer, based on the travel plan I can view the ticket price, so that I can know the cost of my travel.</li>
<li>As a customer, based on the travel plan I can book multiple tickets, so that I can have my metro journey.</li>
<li>As a customer, I want to view the travel plan searches made before and apply them, so that I can quickly apply the search I want.</li>
<li>As a customer, I want to view the current ticket that I have purchased, so that I can refer it whenever I want to.</li>
<li>As a customer, I want to view all the tickets that I have purchased so far, so that I can refer it in the future.</li>
<li>As a customer, I want to buy a travel card, so that I can make frequent travels without having the need to buy ticket each time.</li>
<li>As a customer, I want to add money into the travel card, so that I have sufficient balance during my journey.</li>
<li>As a customer, I want to view the balance amount in travel card, so that I know if I have sufficientfunds available in my travel card.</li>
<li> As a customer, I want to view all the transactions made on a travel card, so that I can refer it in the future.</li>
<li>As a customer, I want to transfer the money in my travel card to wallet, so that I can utilize and manage my funds wherever required.</li>
<li>As a customer, I want to change my password, so that I can secure my account from unwarranted access.</li>
<li>As a customer, I want to modify my profile details like name and email, so that I can manage my account.</li>
<li>As a customer, I want to transfer money from my wallet to bank account, so that I can manage my funds effectively.</li>
<li>As a customer, I want to logout after login, so that I can avoid unauthorized access.</li>
</ul>
