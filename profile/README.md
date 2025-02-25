# Welcome to Vietway
Vietway - A graduation project developed by a group of 4 students for promoting and booking tours within Vietnam.

Vietway is a travel website where customers can effortlessly access detailed travel information, explore attractions, book tours, and make online payments. Additionally, the platform enhances tourism promotion through social media while offering robust management functions for administrators, managers, and staff. These include managing customer accounts, tour operations, attraction approvals, bookings, refunds, and content moderation, ensuring a seamless and efficient experience for both travelers and service providers.

## About Vietway
#### 1. Introduction
- Vietway is a web application project developed by a team of four individuals. The objective of the project is to create an online tour booking system that facilitates both the promotion and booking of tours within Vietnam. Additionally, Vietway allows users to leave reviews, manage their bookings, and engage with travel content through social media, enhancing both their travel experience and the visibility of Vietnam’s tourism.
- Vietway enables customers to effortlessly discover travel destinations, access detailed information about attractions, book tours, and make secure online payments.
- Vietway also provides efficient management capabilities:
	+ The Admin has the highest authority, managing manager and staff accounts, overseeing platform statistics, and ensuring smooth operations across bookings, customer engagement, and financial performance.

	+ The Manager supervises daily operations, reviews and approves attractions, tours, and posts, and manages customer accounts. They handle customer feedback, bookings, cancellations, refunds, and have access to platform analytics.

	+ The Staff supports content management and customer service, handling pending or rejected tours, attractions, and posts. They assist with bookings, refunds, and tour modifications, ensuring content meets quality guidelines before manager approval.

#### 2. Technology
- Front-end:
	+ React: 18.3.1
	+ React-DOM: 18.3.1
	+ Material-UI 
	+ Axios: 1.7.7
	+ React Router DOM: 6.26.2
	+ React-Slick: 0.30.2
	+ Slick-Carousel: 1.8.1
	+ Day.js: 1.11.13
	+ Firebase: 11.0.2
	+ React Helmet: 6.1.0
	+ React Google Maps API: 2.20.3

- Back-end:
	+ ASP.NET Core Web API with .NET 8.0
	+ AutoMapper: 13.0.1
	+ Hangfire: Hangfire.AspNetCore - 1.8.14, Hangfire.SqlServer - 1.8.14, Hangfire.Core - 1.8.14
	+ Microsoft.AspNetCore.Authentication.JwtBearer: 8.0.8
	+ Microsoft.EntityFrameworkCore: Microsoft.EntityFrameworkCore.Design - 8.0.8, Microsoft.EntityFrameworkCore.SqlServer - 8.0.8, Microsoft.EntityFrameworkCore.Tools - 8.0.8
	+ StackExchange.Redis: 2.8.16
	+ Swashbuckle.AspNetCore: 6.4.0
	+ Microsoft.AspNetCore.Http.Features: 2.2.0
	+ Microsoft.AspNetCore.Http.Abstractions: 2.2.0
	+ Microsoft.Extensions.Logging.Abstractions: 8.0.0
	+ Microsoft.Extensions.Configuration.Json: 8.0.0
	+ CloudinaryDotNet: 1.26.2
	+ FirebaseAdmin: 3.1.0
	+ MailKit: 4.8.0
	+ Microsoft.Extensions.Http: 8.0.1
	+ TweetinviAPI: 5.0.4
	+ BCrypt.Net-Next: 4.0.3
	+ IdGen: 3.0.7
	+ Microsoft.IdentityModel.JsonWebTokens: 8.1.0

#### 3. Views and functions of Vietway
- Home page
![Home page](/Images/Home_page.png "home page")


- Tour booking process
	+ Browse tours
![Browse available tours](/Images/Browse_tours.png "browse tours")


	+ Select a tour to view its details and choose a departure date from the available options for booking.
![Select tour to book](/Images/Select_tours.png "select tour")

	+ Booking (fill in contact information, add passenger details, choose payment method, make payment)
![Fill booking detail](/Images/Book_tours.png "fill booking detail")
![Payment](/Images/Make_payment.png "payment")

	+ Complete booking
![Complete booking](/Images/Complete_booking.png "complete booking")
![System send confirm email](/Images/Confirm_email.png "confirm email")


- Create tour (staff)
	+ Create tour template
![Staff manage tour template](/Images/Staff_template.png "Staff manage template")
![Create tour template](/Images/Create_template.png "Create tour template")

	+ After template is approved by manager, create tour using that template
![Staff manage tour](/Images/Staff_tour.png "Staff manage tour")
![Select template](/Images/Staff_approved_template.png "Staff manage tour")
![Create tour tour](/Images/Create_tour.png "Create tour")

- Create post (staff)
![Create post](/Images/Create_post.png "create post")


- Confirm post and upload approved post to social media
![Upload_post](/Images/Upload_post.png "upload_post")

	***** Full details about Vietway at [FinalProjectReport](https://github.com/Hieu-03/CapstoneProject_Vietway/blob/main/Documents/FinalProjectReport.pdf) *****
