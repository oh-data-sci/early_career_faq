questions
===

# How does your organization ensure data is used responsibly and ethically, particularly around bias, privacy, and transparency?
## A1. oskar holm, senior data scientist
- this is an enormous issue. if the company has individual consumers as their customers (b2c), these issues are particularly acute and complex. if the company's customers are themselves businesses (b2b, which i have more experience with) it is less worrying.
- gdpr, the european privacy legislation/regulation is the first concern for both categories. every recording of personally identifiable information must have a legitimate purpose that is disclosed to the subject. data collected for a purpose, can not be used for a later downstream purpose unless the subject explicitly consents to that, too. companies must also be ready to pull out all information on a data subject, correct it if wrong, or purge it if not needed for legitimate reasons.
- for data science models on pii data, there are special considerations. by definition, statistical models pick up patterns in historical transaction records. the difference between biased prejudice and assuming historical patterns apply to future observations can be a narrow path through a minefield. if you are building a statistical model for evaluating someone's credit worthiness, or their insurance claims or something like that, then **best intentions are not enough**. you need your assumptions and outputs vigorously challenged and tested. and good luck, that stuff is hard. 

# What are some challenges you face when handling sensitive or large-scale datasets?
## A1. oskar holm, senior data scientist
- first of, *sensitive* is much more work to deal with than *large scale*. 
- sensitive requires an effective system of data governance. that means policies, persons of responsibilities, and technology sensitive requires encryption, proof of right-to-access, access logging,  audit records, and more. this is involves a number of systems, processes and protocols. 
- large-scale is not really a problem any more. it was 15-20 years ago, in an era we called the big data era. now, you have modern data systems with built-in parallel processing that abstract all that away, unless you are a systems engineer or a software developer at the bare metal level. a lot bigger problem now is recency of data and concurrency of operations on it. streaming data systems are not as mature yet, but getting there i suppose. big data is dead. long live hot data.

# How is the rise of AI tools changing the role of human data scientists and analysts, should students be more concerned or more excited?
## A1. oskar holm, senior data scientist
- shorter version: more excited. the field will become better to work in. but also aware that:
  > over time, ai-agents will make product managers of all of us. instead of working at the fine grain detail of our chosen fields, we will be overseeing ai models doing that.
- longer version: go back to the time when cars first arrived on the scene. most people still rode horses. anyone who drove a car had to be its mechanic to keep it running. the earliest motorists knew a lot more than modern drivers about repairing their cars. but they knew a lot less about driving a car (fewer rules, no seatbelts, reflective vests and warning triangles, and fewer conditions met with). many (or most?) modern motorists can't repair a car beyond filling the tank and changing a tire. likewise, with ai, data scientists will know less and less about building the models and the engines that drives the training process. but they will know more and more about testing the outputs and ensuring they solve problems, are safe to deploy, are robust to unknown input. 
- the productivity benefits are real. machine learning modelling on a data

# As automation becomes more common, what soft skills or mindsets will keep data professionals relevant?
## A1. oskar holm, senior data scientist
