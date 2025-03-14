
# 🙋‍♂️   Meet Josh Hayles  |  Solutions Engineer II @ Datadog | #kubernetes #AWS #technicalWriting #WebDevelopment
> **My greatest ability is the desire to learn.**

## Links

🔗 [AWS Cloud Practitioner Certification](https://www.credly.com/badges/64aa49f6-67db-403d-967f-c34014a286c8/public_url)

🔗 [Tax Corrector (Product)](https://www.taxcorrector.com)

🔗 [MyTechnicalWriting](https://staycurious.io/lists)

🔗 [LinkedIn](https://www.linkedin.com/in/joshhayles/)


## A little about me

After 15 years of experience building and running my own Real Estate business, I have significant skills regarding customer service, the user experience (both, online via product use, as well as in-person communication with people), and I love building systems and processes that create efficiency. 

Combining my business and customer skillset with my "stay curious" approach to technology is what allowed me to build my passion project called Tax Corrector, which is a website that helps homeowners reduce their property taxes (more info below).

As a Solutions Engineer II at Datadog, I specialize in Containers and Cloud. I help customers integrate the Datadog Agent into their container environments (Kubernetes, EC2, Fargate, AWS, VMs, etc) to collect their Logs, Metrics, Traces, custom metrics, and more. I'm always challenging myself to deepen my knowledge and expertise in these areas, strengthening my skills in the Datadog product, and diving deep into complex issues.

## My Background
15 years of experience in Real Estate, where I created a six-figure business that I ran by myself.
  
  - I learned Entrepreneurship skills that taught me all aspects of business:
       - Customer Service
       - Customer-Centric Approach
       - Community Involvement (Home ownership affordability, helping homeowners lower property taxes)
       - Customer Interaction with hands-on communication methods, and automating systems for efficiency and accuracy 
       - Developing Business Plans Customized to my Client’s needs
       - Strong Written and Verbal Communication Skills (Real estate newsletters, Blogs, Neighborhood Analysis, etc)
       - Product and Technology Research that benefited my clients and business needs
       - Teamwork collaboration with a variety of parties involved in each transaction that required custom communication methods
       - Educating clients and the public about the market, technology, and trends
       - Creating memorable and pleasant experiences for my clients in a variety of ways

## [Tax Corrector](https://www.taxcorrector.com)
Tax Corrector is a website I built that helps homeowners reduce their property taxes. I currently have hundreds of paying customers using this service each year. 

- Engineered and deployed (AWS Fargate) a scalable web application using Django, JavaScript, HTML, and CSS that processes hundreds of annual property tax protest reports, featuring automated evaluation forms and secure payment processing (Stripe)
- Implemented data-driven algorithms (taken from my experience in Real Estate) along with a responsive UI/UX design, high quality PDF reports that result in an average of a 12% - 20% reduction for customers, and a 90% success rate
- Backend Tech: Django, postgres, celery, Mailchimp API, AWS SQS, S3, ECS Fargate and Docker for deployment
- Backend Flow: Stripe checkout → EventBridge → AWS SQS queue (also has a dead-letter-queue for failures) → Lambda → Mailchimp API + Django database updated

This architecture separates the concerns of event ingestion (EventBridge), buffering queue (SQS), processing (Lambda), and failure handling (Dead Letter Queue). This separation makes the system more resilient because a problem in one component doesn't immediately break the entire flow.
The SQS queue serves as a buffer that decouples the event source (Stripe/EventBridge) from my processing logic (Lambda). 

## My Software Engineer Background with Flatiron
At Flatiron, I learned a variety of technology and put in 50 to 60 hours of work per week into their program for roughly 4 months

The overall technology was focused on full stack development. I learned Javascript (in its raw form first), then React for the framework. For the backend we learned Ruby / Rails.

Since then, I have focused on improving my Web Development skills using: JavaScript (Pure / Vanilla), advanced JavaScript, CSS / Styling and Prototyping, Svelte/Sveltekit, Node.js, and solving DSAs (Data Structures and Algorithms).

## Why I love Technology (and writing about it!)
- I’m a tech-enthusiast, especially when it comes to Real Estate technology

    - I thrive on an environment that allows me to learn new things
    
    - I love creativity and having the ability to constantly make improvements
    
    - I love to combine my business skills with technology to solve problems for homeowners
    
    
## What I Bring to the Table
- Team Player  👊 
    - I love working with people who are eager to learn, creative, and love to talk about technology
    
    - Whatever needs to be done to help the team, I’m all-in.

    - Innovative ideas for improving / creating products and services to benefit the team’s goals.

    - Collaborating with the team and communicating effectively is important to me.


- Passionately Curious (with a never-ending appetite for learning and improvement)  ⛑️ 
    - Working hard is something that came natural to me in Real Estate because I loved everything about it. That same passion is applied to tech and entrepreneurial services that improve the user’s experience 
    
    - I’m currently studying Cloud Technologies, Containers (Kubernetes, Docker), and advanced troubleshooting on a daily basis at Datadog
    
    - I’m not only capable of learning any technology that’s needed for the job, I’m excited to do so!


- Understanding Product Features | User Benefits | User Experience (really well)  🤗 
    - I’m great at researching a product, getting feedback from customers, documenting that feedback, putting together a report to analyze that information, and making suggestions on what’s best for the product and customer’s experience
    
    - I’m also great at coming up with creative and innovative ideas for new products / services (especially Real Estate, Investing, Homeownership, and Finance)
    
        - Example: I created a publication called “Inside the Mind of the Buyer” that taught Homeowners how to think like a buyer before they put their home on the market. When you list your home and you’re asking someone to pay a price for it you’re now in the presentation game. Your home is open to public opinion, and you have to care about every detail because that’s what the buyer is thinking as they walk through your home:
        
            - I had to understand everything about my client’s goals and create a custom plan that fit their needs, desires, timelines, communication preferences, their expectations, etc.
            
            - I anticipated areas of concern, objections they would likely have and I created custom plans to make sure there weren’t any holes that needed to be plugged in my process:
            
                - Example: I created an estimated proceeds sheet called provides a breakdown of all the costs associated to the seller when they sell their home, and an estimated “walk away” amount to give them an idea of how much money they’ll get at the closing table. I was within $500.00 accuracy with this approach (it was reliable and predictable)
                
                - I presented this at our initial meeting because I knew it would help them make an informed decision about selling.
