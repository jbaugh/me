# Jarrett Baugh
I love to solve problems and learn new things. I enjoy learning new programming languages and challenging myself. I'm especially interested in fault tolerance and high scalability architecture.

### Technical Skills
**Languages:** Ruby, Go, Elixir, Javascript, Lua, Erlang, Python

**Web:** Rails, HTML/CSS/Sass, Rack, Sinatra, Node.js, React, Angular

**Testing:** RSpec, Capybara, Cucumber, EUnit

**Servers:** Apache, nginx

**Datastores:** MySQL, PostgreSQL, Redis, memcached, ETS

**Operating Systems:** Linux, OS X, Windows

**Misc.:** Security, performance


### Professional Experience
#### Leaseful, Lead Software Developer
###### April 2016 - Present
- Python (Django) application converted to Ruby on Rails
- Test Driven with emphasis on maintainability
- Reduced page load time from ~3 seconds to ~200ms
- Integrated with Braintree (merchant accounts)

#### BiggerPockets, Software Developer
###### October 2013 - Present
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

### Personal Projects
#### Game Client/Server
###### Client
- Written in C++, uses Lua for scripting/configuration
- Winsock for networking
- DirectX for graphics
- Boost for threads
- irrKlang for audio
- Full featured (sprite paperdolling, animations, control handling, shaders, world generation, GUI, networking)

###### Server (C++)
- Written in C++ and uses MySQL
- Winsock for networking
- Developed a task scheduler to efficiently prioritize important tasks (network input)
- Utilizes smart world management (only 'things' near a player should be processed)
- Full featured (request handling, account creation/authentication, database integration, NPC spawning an AI, player abilities, combat, quests, crafting)

###### Server (Erlang)
- Written in Erlang and uses MySQL
- Uses OTP and an extremely fault tolerant design
- Contains a feature subset of the C++ Server

#### Application Updater
- Written C++ and uses Boost
- Cross platform
- Dynamically determines which files are out of date and only downloads the missing or out of date files
- Works against a web server

#### OctopusCI
- Written in Ruby
- Attempted to solve continuous integration for multi-branch workflows (using smart queueing, distributed testing servers and Github integration)
- At the time, it worked well, but there are far better solutions now

### Education
###### University of California, Irvine
###### BSc in Computer Science
