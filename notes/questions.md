**1. Career Pathways and Industry Insights**
- Could each of you briefly describe your role and what a typical day looks like in your job?
	- as a senior data scientist my role is to design intelligent features and generate new knowledge to guide decision making in the organisation. i act as a bridge between the engineering and the business functions. on a typical day i meet with stakeholders to concretize their requirements, translating a pain point of theirs into a question that can be answered by (available) data. i then code in sql/python/bash to access, wrangle, model, analyse that data towards a solution that yields an answer. 
- How did you first get into data science or analytics, and what skills helped you most early on?
	- myself, i came from physics. i did numerical astrophysics and cosmology at uni. i bridged between observational and theoretical physics. 
- How do the roles of data analyst, data scientist, and data engineer differ in your organizations?
	- as a general rule, the terms vary so much between organisations that it is really hard to say. in some smaller companies, i would use the term 'data professional' because you will find yourself doing a little bit of everything. having said that, here is a brief summary:
	- data engineer: a builder. builds pipelines between data systems and models data in databases. 
	- data analyst: a business liaison. delivers analytical reports (in a business intelligence suite, or reporting engine) that inform and assist decision making for business stakeholders. (by *analytics* i mean a combination of filter/group by/aggregate operations).
	- data scientist: a business liaison. trains statistical models and methods of scientific computing to design intelligent features and answer research questions.
	- machine learning engineer: a builder. 
	- "full stack data scientist": a mythical combination of all of the above. including building/maintaining/delivering data governance, data strategy, 
- What are some common misconceptions that students or graduates have about working in data?
	- *the sexiest job title of the 21st century*. it was fun while it lasted, but that time is over.
	- that you will be working on local copies of the data. that's rare in an organisation, for many good reasons.
	- that brilliance and skill will get you promoted. only strategic impact. that may or may not require brilliance and skill.
- Looking ahead, how do you see the data field evolving over the next few years, particularly with AI and automation?
	- over time, ai will make product managers of all of us. instead of working at the fine grain detail of our chosen fields, we will be overseeing ai models doing that. instead of figuring out how to solve each problem, we will be evaluating ai-generated solutions for their correctness and fitness for purpose. instead of obsession over detail, and mathematical skill, it will  large picture systemic understanding and empathy for the models that will determine your success. 
- Are there particular industries (such as healthcare, finance, or sustainability) where you see the most growth in data-related roles?
	- i see it everywhere. any field that doesn't have growth in terms of data related roles is a field that is saturated with data related roles and natural employee churn will make plenty of roles available there as well. my recommendation to you is to take whatever it is you already know and love (healthcare, finance, sustainability, retail,) and look into how data can improve operations in that field, then show you understand how how data helps, and that's how you will find a job, or the job will find you.

**2. Skills and Tools**

- What technical skills are most in demand for graduates entering the data job market today?
	- number 1: sql and python. 
	- secondary: software development best practices (version control, devops, automated testing, autmated documentation. 
	- specialty system skills: R, sparks, business intelligence suite, 
	- design thinking (as a product person)
- How important are communication and storytelling skills compared to purely technical abilities?
	- medium important for your project works (have something to say before you say it), and very important for your career. communication skills will affect your career progression a lot more than mathematical/programming skill.
- For students without industry experience, what’s the best way to gain practical, real-world exposure to data projects?
	- outside of actually getting hired, i don't really know. but here are some thinking out loud ideas:
	- find someone who will take you: use your contacts, see if anybody has an analytical challenge on their hands to help. you are unlikely to get their data, but you can show that you know how to handle data like theirs to solve a problem like theirs. solve it, using synthetic data if you must. put it on github. write a blog. 
	- go at it alone: take a skill you are already good at (e.g. time series analysis) and apply it to a problem in a space you are already knowledgeable about (football? f1 racing? astronomy?)  tackle it. put it on github. write a blog.
- Are online certifications valuable for employability?
	- a) not for you, as you will already have a degree from an accredited institute and that trumps any online certificate (unless the latter is on precisely the topic the role is about). the problem is knowing what an online certificate actually tells a potential employer. it will have to be a certificate from someplace that the hiring managed knows of. i have had candidates put certificates on their cvs, and i have no idea what they are. they might demonstrate very impressive rigorous coursework, or they might be completely fraudulent. i am not investing my time researching online courses. 
	- b) yes. sometimes. especially in older, established and more conservative organisations: banks, govern ment. younger startups are more likely to look at your github repos and blog posts. 
- From your experience, what are the most common skills gaps you see in new graduates entering data roles?
	- SQL
	- working processes (note taking, documenting, testing, thoroughness, agile (tickets, work organisation)


**3. Employability and Career Preparation**
- What makes a strong CV or LinkedIn profile for data-related positions?
	- length (lack of it) and focus
	- the link to your github repos, blog, your work examples
- What kinds of projects or portfolio work tend to impress recruiters most?
	- those that are technically closest to the role being hired for. (being close to the subject area can also help, but being technically close is better. )
		- e.g.: if the role is for time series analysis in the retail space and your project shows experience doing a time series analysis experience in healthcare, that's great. good but less great if you show clustering experience in retail. 
	- note that most *recruiters* have never worked in data and their image of the roles normally differ widely from the actual role. that's to be expected. i don't really know what working as a recruiter is really like. so the answer is different for recruiters than it is for *hiring managers*.
- What’s the best way for students to network and find opportunities in the data industry?
	- who planted this question?! the answer is obvious. go to the local meetup scene. i recommend the [brighton data forum ](https://www.meetup.com/brighton-data-forum)
- How do employers typically assess candidates in interviews for data roles, are there case studies, coding tasks, or presentation elements?
	- all of the above. although at the junior level the decision is generally made in fewer interviewing rounds, unless the company is that much smaller. first interview: people team screen candidates for cv keywords, work permit, salary expectations, etc. second interview: technical test of some kind (varies). third interview: culture fit (just means: how is it going to be to have to work with you? how will you react to being forced to work with us? if there is a fourth interview it will be with someone higher up who has veto power, usually goes well). 
- Do you think internships or placements are essential, or can independent or university projects demonstrate readiness effectively?
	- no, not essential. the technical aptitude and similarity between project work and the role description matters more.

**4. Ethics, Responsibility, and the Future of Data Work**
- How does your organization ensure data is used responsibly and ethically, particularly around bias, privacy, and transparency?
	- this is an enormous issue. if the company has individual consumers as their customers (b2c), these issues are particularly acute and complex. if the company's customers are themselves businesses (b2b, which i have more experience with) it is less worrying.
	- gdpr is the first concern for both categories. every recording of personally identifiable information must have a legitimate purpose that is disclosed to the subject. data collected for a purpose, can not be used for a later downstream purpose unless the subject explicitly consents to that, too. companies must also be ready to pull out all information on a data subject, correct it if wrong, or purge it if not needed for legitimate reasons.
	- for data science models on pii data, there are special considerations. by definition, statistical models pick up patterns in historical transaction records. the difference between biased prejudice and assuming historical patterns apply to future observations can be a narrow path through a minefield. if you are building a statistical model for evaluating someone's credit worthiness, or their insurance claims or something like that, then **best intentions are not enough**. you need your assumptions and outputs vigorously challenged and tested. and good luck, that stuff is hard. 
- What are some challenges you face when handling sensitive or large-scale datasets?
	- first of, *sensitive* is much more work than *large scale*. 
	- sensitive requires a system of governance. sensitive requires encryption,  proof of right-to-access, access logging,  audit records, and more. this is involves a number of systems, processes and protocols. 
	- large-scale is not really a problem any more. it was 15-20 years ago, in an era we called the big data era. now, you have modern data systems with built-in parallel processing that abstract all that away, unless you are a systems engineer or a software developer at the bare metal level. a lot bigger problem now is recency of data and concurrency of operations on it. streaming data systems are not as mature yet, but getting there i suppose. big data is dead. long live hot data. 
- How is the rise of AI tools changing the role of human data scientists and analysts, should students be more concerned or more excited?
	- in long: go back to the time when cars first arrived on the scene. most people still rode horses. anyone who drove a car had to be its mechanic to keep it running. the earliest motorists knew a lot more than modern drivers about repairing their cars. but they knew a lot less about driving a car (fewer rules, no seatbelts, reflective vests and warning triangles, and fewer conditions met with). many (or most?) modern motorists can't repair a car beyond filling the tank and changing a tire. likewise, with ai, data scientists will know less and less about building the models and the engines that drives the training process. but they will know more and more about testing the outputs and ensuring they solve problems, are safe to deploy, are robust to unknown input, 
	- 
	- in short: more excited, but also aware that "*over time*, ai will make product managers of all of us. instead of working at the fine grain detail of our chosen fields, we will be overseeing ai models doing that. instead of figuring out how to solve each problem, we will be evaluating ai-generated solutions for their correctness and fitness for purpose. instead of obsession over detail, and mathematical skill, it will  large picture systemic understanding and empathy for the models that will determine your success.*"
	- 
	- the productivity benefits are real. machine learning modelling on a data
- As automation becomes more common, what soft skills or mindsets will keep data professionals relevant?

**5. Advice for Students**
- What’s one thing you wish you’d known when starting your own career in data?
	- start networking early. it's like putting away savings. the benefits compound over time like compounding interests.
	- in an organisational hierarchy, upwards communication, downwards communication, and peer communication are separate skills. don't be fooled that being good at one of them means you are good the others.
	- skill and brilliance may get you hired, but don't reliably get you promoted. only strategic impact does. that may or may not require skill.
	- think hard about what aspects of the role you enjoy the most. be aware of it if/when that shifts.
- How can students make the most of their time at university to prepare for industry?
	- balance skill acquisition, networking, and strategic career planning. 
- What are the most common mistakes you see students or graduates make when applying for data roles?
	- most common: not prepping for follow up questions.
	- most serious: dishonesty. 
- For international students, what extra steps can help strengthen their chances in the UK job market?
	- as an immigrant here myself, i am not aware of anything i did differently from native applicants. however, i may not be the best placed person to answer that. i am aware that i enjoy many unearned privileges for looking pretty much like the natives.
	- you will need to network all the more hard though. you (probably) don't have a school mate from childhood, or an uncle or an acquaintance of your mother's in a bank in london looking to hire. but native brits do. to compete against that you will have to find and utilise whatever connections you make.
- For students who feel overwhelmed by how broad the data field is, what’s your advice for finding a focus or specialism?
	- start with the part you most enjoy currently the part you are most interested in. at the edges of that aspect you will find in order to know better your favourite aspect you need to better understand another aspect. the more you know about a new aspect. you can start enjoying data 

**Quick-Fire Round**
- Favorite data tool or library right now?
	- duckdb + motherduck: opensource analytical database and a corresponding cloud data warehouse with a generous free tier. 
- One underrated skill every data professional should have.
	- window functions in sql?
	- deeply understanding table joins?
	- building bespoke data visualisations for infographics 
- Best piece of career advice you’ve ever received?
	- communicate more upwards. data professionals need to be *data leaders*. 
- Most exciting project you’ve worked on recently.
	- clustering and classification combination for customer segmentation.
