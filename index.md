# the Drone Companion Application project

##### _A partnership between Transport Canada and the Code for Canada_ 


### The Code for Canada Fellowship program

The Code for Canada fellowship program embeds digital professionals in government for a 10-month residency. The goal is to show what’s possible when we apply the latest methods in user-centered design, product management and software development. 

### Who made up the Digital Drone Collective? 

The "core team":
* Jeannie Stewart-Smith, Senior Policy Analyst, _RPAS Task Force_
* Olivier Bellehumeur-Genier, Safety Inspector, _RPAS Task Force_
* Weiguang Xiao, Developer, _TC Solution Centre_
* Jennifer Payne, Product Manager, _Code for Canada Fellow_
* Andee Pittman, Designer, _Code for Canada Fellow_
* Fatima Khalid, Developer, _Code for Canada Fellow_

The "extended collective":
The core team was supported by a project panel made up of Transport Canada employees from a variety of disciplines and levels. They supported by providing feedback and navigating internal policies. 

* Felix Meunier, Director, _RPAS Task Force_
* Ryan Coates, Manager, Policy, Regulations & Stakeholder Engagement, _RPAS Task Force_
* Nic Horne, Executive Director, _TC Solutions Centre_
* Danielle Holden, Director, _Solutions Centre_
* Kofi Arthiabah, Director, _Cloud Infrastructure Operations_ 
* Carine Lavoir, Manager, _Internal Communications_
* Stephanie Bell Senior Communications Advisor, _Internal and Corporate Communications_
* Graham MacVannel, Lawyer, _Legal Counsel_
* Natasha Pecarski, Aviation Team Lead, _Web Services_
* Ron St Louis, Communications Advisor, _Web Services_
* Graham Rivers, Director _Digital Enablement_

### The Challenge

The challenge for our team was outlined in our project charter: 

> “Drone operators—especially those recreational operators who are new to aviation—experience confusion and frustration when planning flights, conducting and recording site surveys, analyzing risk, and reporting incidents. As a result many operators are not flying safely and in a manner that is consistent with regulations. By prioritizing features based on research into the needs of recreational drone operators, fellows will build a product that makes it easier for them to fly more safely and in accordance with regulations.”

Our target users are new recreational drone pilots. From our research, we learned these individuals often use their drones for photography or for the fun of flying. Many of these individuals have limited knowledge of aviation and drone regulations.

### What did the research tell us?
For primary research, we conducted several rounds of interviews, a diary study, and an immersion study. 

**The biggest challenge found in the research was a lack of practical education for recreational drone pilots** on how to follow the regulations. We found the gap for this group existed despite several efforts in the policy, service delivery and roll-out. 

**1.Recreational drone pilot exam and certification service**

The policy included two levels of certification: the basic pilot license and the advanced pilot license. The basic pilot license only requires an online exam. The advanced contains an in-person demonstration of skills. Despite this, we found that the knowledge requirements for the basic drone pilot exam were extensive, and would likely still be a barrier. 

The study guide provided by Transport Canada indicated exam takers would have to learn over 250 aviation topics in subjects such as flight theory, meteorology and radiotelephony. 

Sample of a knowledge requirement in flight theory: 

> The small RPAS pilot operating within visual line of sight must be able to:
Explain the function of the vertical fin.
Identify basic components including lifting and stabilizing components.

To learn these, prospective drone pilots would have to sift through standard aviation textbooks written for professional pilots.  

For the two (out of four) participants that discovered the certification requirement, only one was able to pass on the first attempt. This participant used the internet to search for answers to the questions. Technically, "open-book" is allowed by the regulations. The rationale for this was to balance the difficulty of the exam. However, we found research that suggested that retention from open book exams is lower over time[1]. We identified that this approach may not fulfill the policy objective. 

[1]https://www.researchgate.net/publication/51717450_Expectancy_of_an_open-book_test_decreases_performance_on_a_delayed_closed-book_test

Further, the exam neglected to support practical knowledge of how to conduct the requirements of the regulations. For the recreational drone pilot, it's likely more effective to have them understand "how" to be safe, than understand "what" and "why" alone.  

**Private sector training**

From our organizational research we found that the RPAS Task Force believed the private sector would provide training for both the Basic and Advanced exams. We spoke to the Ottawa Flight School during one of their events where Transport Canada spoke about the new regulations. They explained to our team that they would not be creating a course for the Basic certificate because it wasn't financially viable. 

We also found that the list of locations offering in-person flight exams for the Advanced certificate was limited. There were only 64 locations across the country upon the initial release of the regulations. This led us to think that the private sector appetite for drone education might only exist within major city centres. 

Without being able to guarantee a company would provide this service, we believed this educational gap could remain. This was central to our justification for Transport Canada to invest in filling this gap.   

**Content provided in the Aeronautical Information Manual** 

The Aeronautical Information Manual (AIM) is the standard aviation book that Transport Canada produces to describe aviation regulations. By reviewing the current editions of the textbook, we could hypothesize that they would not enable users to complete a site survey successfully. We were only able to see the first draft of the information provided on the Site Survey after we finished our discovery period. We decided to include the AIM and the other legal aviation documents required by Transport Canada in our first prototype test. We found that in all usability sessions, the participants were interested in learning about how to complete the regulations, but found the materials insufficient because they lacked basic information and context. The internet also lacked credible information and lead participants further astray. 

**Safety campaigns on social media and in-person events**

A commendable effort was made to bring awareness to the regulations. However that awareness didn't include educational support for the site survey. The basic rules were the focus, and didn't connect users to alternative educational resources.   

The RPAS team also completed two cross-country information tours. The first occured between the Canadian Gazette publishings to seek feedback on the first draft. Then again they went on tour after the publishing of the regulations. The team describes little participation from the recreational drone community. Even if they had, in-person events are not accessible to the full target audience. Without consideration to serving remote communities, this was not a viable option for education.  

#### Opportunity Statement
> Recreational drone operators in Canada need to understand and be able to enact all the steps required between acquiring and safely operating a drone, and to understand the risks of drone flight because users want to feel competent, safe and legal when they are flying a drone. Users want to keep their drone safe and avoid fines. They want an efficient, free, understandable, comprehensive, trusted source of information.

> The Digital Drone Collective will need to start small to learn about how we might tackle regulation guidance with a digital tool in order to bring it to scale. To do this, we are going to investigate how we can best facilitate the learning of the most challenging part of the regulations, the site survey. Through this, we can learn how we might apply this approach to other aspects of the regulation. We will investigate how we guide users through the process, have them understand why, and when they’ve achieved success. Through this, we can grow motivation, help people understand the information, and give guidance on how to comply with regulations. 

We thought the site survey, although a complex process, would be the most impactful to prototype with. It would ensure that we could test the central question: can we teach people the required aviation practices with a digital tool? To reduce the risk and take a lean approach, we needed to test with the hardest skill. Fortunately, the site survey is also the aviation practice with the greatest impact on safety. This made it an easier sell to the broader collective. 

**Problem statement:**

How might we enable recreational drone pilots to confidently conduct their first site survey?

**Product goals:**

* Instruction, guide users through the process of conducting a site survey
* Include the what, why, and how in the context of applying the skill 
* Include success metrics, give users criteria for success. How will they know when they’ve done it sufficiently and would pass inspection? 
* Be a trusted source, including liability information and awareness, have Transport Canada branding 
* Provide access offline to serve the remote nature of drone flying
* Ease, make the process of site survey manageable and easy for users

**Desired product outcomes:**

* Motivation to follow regulations through an understanding of why these aspects are important to safety and avoiding fines
* Success with following regulations from understanding instructions and receiving guidance.

**Design constraints:**

* Must be a digital tool
* Must be scalable to accommodate other “doing” pieces of the regulations
* Must allow users to conduct activities properly under the regulations, ie. no simplifying processes to meet user needs.

### What we designed
To see the first concept explorations, check out our first concept gallery page.

To see the first prototype, check out our first prototype gallery page.

To see the second prototype, check out our second prototype gallery page. 

To see the final design, check out our final design gallery page. 

### What we built

We built a progressive web application to guide users through conducting a site survey. Our long-term vision is a tool that guides users through all the steps necessary to comply with drone regulations (Canadian Aviation Regulations Part IX), including those not part of the site survey.

The app was built with the following: 
* React.js - frontend
* .NET core - backend
* PostgreSQL - database
* WET 4, Aurora Design System - Theme layer base
* Azure - Cloud
* Docker - Containerization
* Paypal AATT - accessibility testing
* MobX - state management
* Jest, Enzyme - automated testing
* Travis CL - continuous integration and deployment

To see the repository, visit our [Drone Companion App Repository](https://github.com/sugaroverflow/drone-companion-app)
