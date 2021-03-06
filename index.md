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

![The DDC Core Team](ddc-team-ideation-1/ddc-core-team.png)

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

Our target users are new recreational drone pilots. From our research, we learned these individuals often use their drones for photography or for fun. Many of these individuals have limited knowledge of aviation and drone regulations.

### What did the research tell us?
For primary research we conducted:
- several rounds of interviews 
- a diary study
- an immersion study 
- usability studies throughout prototyping

The biggest challenge found in the research was a lack of practical education for recreational drone pilots.  We found the gap for this group existed despite efforts in the policy, service delivery and marketing communications. 

**Recreational drone pilot exam and certification service**

The policy included two levels of certification: the basic pilot license and the advanced pilot license. The basic pilot license only requires an online exam. The advanced contains an in-person demonstration of skills. Despite this, we found that the [knowledge requirements](https://www.tc.gc.ca/en/services/aviation/publications/tp-15263.html) for the basic drone pilot exam were extensive, and would likely still be a barrier. 

[The study guide](https://www.tc.gc.ca/en/services/aviation/publications/tp-15263.html) provided by Transport Canada indicated exam takers would have to learn over 250 aviation topics in subjects such as flight theory, meteorology and radiotelephony. 

Sample of a knowledge requirement in flight theory: 

> The small RPAS pilot operating within visual line of sight must be able to:
Explain the function of the vertical fin.
Identify basic components including lifting and stabilizing components.

To learn these, prospective drone pilots would have to sift through standard aviation textbooks written for professional pilots.  

Only two out of four participants discovered the certification requirement in their immersion. Of those two, only one was able to pass on the first attempt. This participant used the internet to search for answers to the questions during the test. 

"Open-book" is allowed by the regulations. The rationale provided for this was to balance the difficulty of the exam. We investigated the effects on open-book tests and found conflicting research. We concluded that in a regular course, open-book exams seemed to make little to no difference in learning outcomes. However, retention from open book exams has found to be lower over time. Considering there is no coursework provided to support this exam, there's no guarantee that learning will happen. This seemed to be the factor that enabled open-book tests to be preferable to closed-book. Therefore we suggested that without educational material, this approach may not fulfill the policy objective. 

**Relying on the private sector for training**

We found that the RPAS Task Force believed the private sector would provide training for both the Basic and Advanced exams. We decided to investigate this to see if we could confirm this approach. We spoke to the Ottawa Flight School during one of their events where Transport Canada presented. They explained to our team that they would not be creating a course for the Basic certificate because it wasn't financially viable. 

We also found that the list of locations offering in-person flight exams for the Advanced certificate was limited. There were only 64 locations across the country upon the initial release of the regulations. This led us to think that the private sector appetite for drone education might only exist within major city centres. While there was no data on where drone pilots lived yet, we found evidence that suggested that drone communities flourished in more rural areas due to the perceived level of safety.  

We concluded that Transport Canada could not guarantee that the private sector would provide the needed education for the Basic Pilot Certificate. We believed it was likely that an educational gap could remain for recreational pilots.   

**Content provided in the Aeronautical Information Manual** 

The Aeronautical Information Manual (AIM) is the standard aviation book that Transport Canada produces to describe aviation regulations. We reviewed the current edition of the textbook to gauge its usability for a recreational drone pilot. It is text-heavy, with little use of imagery, and the content was directed at readers who already had an education in aeronautics. Therefore, we believed that users would find this resource difficult to use for their self-directed learning. 

We were only able to see the first draft of the information provided on the site survey after we finished our discovery period. We decided to include the AIM and the other legal aviation documents required by Transport Canada in our first prototype test. We found that in all usability sessions, the participants were interested in learning about how to follow the regulations. However, they found the materials insufficient because they lacked basic information and context related to drone flight. The internet also lacked credible information for Canada, and lead participants further astray. This confirmed our hypothesis, and lead us to conclude that the basic material provided by Transport Canada would be insufficient for the needs of this audience. 

**Safety campaigns on social media and in-person events**

A commendable effort was made to bring awareness to the regulations. However that awareness didn't include educational support for the site survey. The focus for the campaigns was on registering, certifying, and parameters for flight.   

The RPAS team also completed two cross-country information tours. The first occurred between the Canadian Gazette publishings to seek feedback on the first draft. Then again they went on tour following the publishing of the regulations. The team described little participation from the recreational drone community. Even if they had, in-person events are not accessible to the full target audience. Without consideration of serving remote communities, this was not a viable option for the kind of education needed for this group.  

#### Opportunity Statement
> Recreational drone operators in Canada need to understand and be able to enact all the steps required between acquiring and safely operating a drone, and to understand the risks of drone flight because users want to feel competent, safe and legal when they are flying a drone. Users want to keep their drone safe and avoid fines. They want an efficient, free, understandable, comprehensive, trusted source of information.

> The Digital Drone Collective will need to start small to learn about how we might tackle regulation guidance with a digital tool in order to bring it to scale. To do this, we are going to investigate how we can best facilitate the learning of the most challenging part of the regulations, the site survey. Through this, we can learn how we might apply this approach to other aspects of the regulation. We will investigate how we guide users through the process, have them understand why, and when they’ve achieved success. Through this, we can grow motivation, help people understand the information, and give guidance on how to comply with regulations. 

To reduce the risk and take a lean approach, we needed to test with the hardest skill. We thought the site survey, although a complex process, would be the most impactful to prototype with. It would ensure that we could test the central question: can we teach people the required aviation practices with a digital tool?  Fortunately, the site survey is also the aviation practice with the greatest impact on safety. This made it an easier sell to the broader collective. 

> How might we enable recreational drone pilots to confidently conduct their first site survey?

**Product goals:**

* Instruction, guide users through the process of conducting a site survey
* Include the what, why, and how in the context of applying the skill 
* Include success metrics, give users criteria for success. How will they know when they’ve done it sufficiently and would pass inspection? 
* Be a trusted source, including liability information and awareness, have Transport Canada branding 
* Provide access offline to serve the remote nature of drone flying
* Ease, make the process of site survey manageable and easy for users

**Desired product outcomes:**

* Motivation to follow regulations by understanding why and how these practices are important to safety
* Success with following regulations from understanding instructions and receiving guidance.

**Design constraints:**

* Must be a digital tool (because we're a Code for Canada Fellowship  team on a 9 month residency)
* Must be scalable to accommodate other “doing” pieces of the regulations
* Must allow users to conduct activities properly under the regulations, ie. no simplifying processes to meet user needs.

### What we designed
To see the first concept explorations in our Alpha phase, [check out our first concept gallery page.](concept-gallery.md)

To see the first prototype in our Alpha phase, check out our first prototype gallery page.

To see the second prototype in our Beta phase, check out our second prototype gallery page. 

To see the final design, check out our final design gallery page. 

### What we built

We built a progressive web application to teach users how to conduct a site survey. We followed Canada.ca "look and feel" standards so that the application could be hosted on Transport Canada's website.  We built the tool with room to grow and expand through containerization and using other modern technologies. 

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
