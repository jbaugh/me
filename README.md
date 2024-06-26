# Jarrett Baugh
I love to solve problems and learn new things. I enjoy learning new programming languages and challenging myself. I'm especially interested in fault tolerance and high scalability architecture.

### Technical Skills
**Languages:** Ruby, Elixir, Go, Javascript/Typescript, Python

**Web:** Rails, Phoenix, Node.js

**Datastores:** PostgreSQL, MySQL, Dynamodb, Redis, ETS


### Professional Experience
#### ModeMobile, Staff Software Engineer
###### September 2019 - present
- Primarily Ruby on Rails with Node.js applications (mostly NestJS)
- Reduced costs by optimizing database queries, code and architecture
- Built robust, scalable systems using AWS (EC2, ECS(Fargate), Kinesis, Lambdas, SQS, Dynamodb)
- Increased API performance and reliability
- Led backend team to more efficient workflow, code quality improvements, better team cohesions
- **Project:** Ad mediation API
  - Scalable, simple and fast NestJS application deployed on EC2 with autoscaling
  - Served ads based on user data (demographics, ad limits, placement)
- **Project:** Charge screen
  - Allowed users to earn points while charging their phone
  - Built a solution that scales with our user growth
  - Built security into the solution to prevent fraud
  - Uses redis heavily to keep it fast and efficient
- **Project:** Influencer experience improvement
  - Architected a solution to improve system performance while also improving the experience for power users
  - Worked without issue since implementation
- **Project:** Performance improvements
  - Re-architected code so that we could remove unnecessary database locks
  - Improved third party integrations to eliminate unnecessary database updates (autovacuums became a problem)
  - Improved transaction code so that user updates were quicker
  - Added caching using redis
  - Improved database queries (examples: adding indexes, reworking queries based on performance tests, changing database schema to better fit our use case)
- **Project:** Revenue reporting tool
  - Integrated with advertising partners to collect revenue data in one place
  - Built a fault-tolerant application to better handle third party API failures
  - Worked with product team to integrate into AWS QuickSight for better data exploration

#### Caremessage, Software Engineer
###### March 2017 - September 2019
- Wrote scalale code
  - Processed and worked with millions of records
  - Use background processing to interact with 3rd party APIs and process data
  - Flexible API could join several tables, and response must be kept low
- Secure code
  - HIPAA compliance to protect privacy of patients
  - Use of brakeman and other audits to maintain security
- Reliable code
  - Medical offices depend on this application so reliability was a priority
- Worked on upgrading Rails 4 to Rails 5
- Maintained different public API versions
- Worked with Twilio to send text/voice messages, process responses
- **Project:** Appointments
  - Worked with existing feature foundation to extend and improve usability
  - Improved performance by reworking queries, caching appropriately
  - Balanced product requirements with engineering requirements
  - Delivered features on time while slowly reducing technical debt
- **Project:** File center
  - Improved usability by reducing some possibility of user errors by properly handling
duplicate data, invalid data, etc.
  - Improved performance by using business rules to catch validation issues before heavy processing

#### Leaseful, Lead Software Developer
###### April 2016 - December 2018
- Python (Django) application converted to Ruby on Rails
- Test Driven with emphasis on maintainability
- Reduced page load time from ~3 seconds to ~200ms
- Integrated with Braintree (merchant accounts)

#### BiggerPockets, Software Developer
###### October 2013 - March 2017
- Rails 3 converted to Rails 4 
- Wrote scalable, secure and reliable code to handle the rapid traffic growth
- Worked closely with billing system using Stripe
- 'Owned' many large projects which were core features of the site
- **Project:** Calculators
  - Created calculator tool to help customers make investment decisions
  - Used TDD to ensure accuracy and reduce unnecessary complexity
- **Project:** Hard Money Lender System
  - Built a self-serve subscription system for customers
  - Reduced overhead and increased revenue
- **Project:** Book Order System
  - Built a system for managing book orders throughout the order's life cycle: purchasing, fulfillment and shipping
  - Improved productivity of team while reducing human errors

#### Sleepy Giant, Software Developer
###### January 2012 - October 2013
- Rails 3 and Rails 4
- Worked closely with clients (game development studios) to build web sites, billing integrations, game authentication servers and more
- Integrated with many billing and game APIs to handle the international market
- Architected several new projects with consideration of expected traffic, reliability needs, client goals and development time
- **Project:** Animal Jam
  - Maintained and extended existing site
  - Developed and executed the localization process
  - Integrated with several payment processors to allow customers many ways to pay
  - Provided a robust, reliable and performant API for game servers to interact with
- **Project:** ESO
  - Wrote a fast game authentication server to handle consistent and burst traffic
  - Oversaw routine security and performance audits
  - Architected the application into scalable services with fault tolerance in mind
  
#### RealPractice, Software Developer
###### July 2010 - January 2012
- Helped build new platform in Ruby on Rails
- Built automated testing framework using Java and Selenium
- Maintained existing PHP applications (CakePHP / SilverStripe)
- **Project:** Client Workflow System
  - Scheduling system for managing recurring or one time events
  - Email parsing using (basic) natural language processing
  - Integrated with their phones and could connect calls from leads to clients
  - Fault tolerant design
- **Project:** Website Builder
  - Drag and drop design (using some jQuery UI but also custom plugins)
  - Site was made up of components which allowed very rich designs
  - Satisfied ease of use requirements while allowing custom building by internal admins

#### Side Projects
##### Fundraising Site
- Written in Elixir with Phoenix
- Supports local schools with fundraising challenges
- Team, member and event management including donation goals and rewards
- Inspired by a family member's struggle to find good, affordable software to meet their needs

##### Online Game Server
- Written in Go
- Networked server (using sockerts) supporting clients playing an online game
- Uses channels for event based architecture
- Fully featured game including combat, leveling, spells, items and more.

### Education
###### University of California, Irvine
###### BSc in Computer Science
