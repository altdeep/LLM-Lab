# Guidelines for LLM-Lab capstone project

The capstone project for this workshop focuses on building a large language model (LLM)-based application. Students will be tasked with interviewing potential users and prototyping an LLM-based app based on that feedback. Through this project, students will learn to apply design thinking, engineering, and project management skills to create a LLM-based application that meets the needs of its users. The project will challenge students to develop a deep understanding of their target audience and to propose an LLM-based product that would achieve product-market fit. By the end of the project, students will have gained valuable experience in designing and launching an LLM-based application.

## Weekly deliverables

Each week, you will need to submit project deliverables. These deliverables are submitted as a presentation deck and possibly adjacent files in Canvas. Your submissions are evaluated and counted as part of your participation grade.

## Final Deliverable
The ultimate deliverable for this project is a presentation summarizing your proposal and research, and a video recorded demo of a prototype.  Providing an actual working prototype is not required.

## Motivation for this research-based approach
In the capstone project, our goal is to build a tool that is anchored in the needs of some well-defined set of users.  In building any tool with an LLM, there is a risk that your tool will: 
1. Become commoditized as LLM models and APIs become cheaper, more open-sourced, and more ubiquitous.
2. Be displaced by a simple add-on that a private company like OpenAI or Microsoft adds to their existing products.
3. Become obsolete with the next generation of LLM.

Our approach takes the hypothesis that building tools specific to the needs of individual users is more defensible.  For example, if you spend a month developing a series of prompts that helps a specific set of people solve a specific problem, it is unlikely that your work will be able to take advantage of cheaper or better tech, rather than be devalued by it.  Further, as you learn more about a specific group of users and a domain, you become better positioned for building new tools for that user and that domain as the technology advances.

## A "lean" project focus
In this capstone project, you will rely on a validated-learning methodology to develop a prototype LLM-based product.
Essentially, this entails using interviews with potential users, iterative prototyping, and feedback to discover whether a proposed business model is viable.

### Why users can't do it for themselves
Some may point out that interfaces like ChatGPT make LLMs accessible to all, and that they can even generate code.  So why should any user need you to build a solution? Here are some obstacles for inhibiting a domain expert from building solutions with a LLMs on their own.

* An LLM-based solution will only part of the full end-to-end solution.
* Other technical components of that solution involve data management, ETL, authentication, etc.
* In many cases, one cannot use private data with public APIs. 
* Good prompts take time to design. Iterating on prompts is like iterating on code, and just as hard to manage.
* Best practices for prompt engineering are changing all the time. The average user cannot be expected to keep up.
* Prompt engineering is increasingly relying on sophisticated code libraries (e.g., Semantic Kernel, langchain, guidance, etc.).
* Sometimes, you need a sequence of prompts to solve a problem, like in a chat conversation.   Often these sequences need different branches managed by control flow.  This adds to complexity.
* People who are unfamiliar with LLMs are unfamiliar with their limitations. The therefore have trouble understanding failure modes (e.g., "hallucination"), when failures occur, and how do debug them when they do occur.
* Interfaces like ChatGPT are too open-ended. Good application design guides users to accomplishing their intended tasks as easily and directly as possible.

## Selecting a project focus

You want to work with your group to select a well-defined group of users. These could be based on professions like "doctor" and "attorney" or users within an industry or *industry vertical* --  a group of companies that focus on a shared niche or specialized market that spans multiple industries, e.g., fintech uses technology to provide financial services.

It goes without saying that you should pick an industry where you suspect LLMs could improve existing workflows as well as enable the existence of new workflows. Part of your job in this project will be to falsify or validate this hypothesis.

It is 100% okay to switch your target user group in the middle of the workshop. As you learn more, it is **expected** that your target users, hypotheses, and prototypes will change.

As you progress, try to narrow in on a group of user. The more specific you can be, the better. For example, you might start by interviewing on "lawyers and paralegals", and by the end you might focus in on "patent attorneys who handle litigation for tech companies" or "maritime lawyers who have to reconcile many different types of documents for compliance processes involving many different stakeholders from different jurisdictions."  

## Interview methods and finding pain points

Use live voice interviews (videoconferencing, phone calls, in-person).  Part of the reason for voice calls is that it is important to understand the "pain points" in a person's workflow, and that is much easier to do in a live conversation where you can hear tones and observe body language.  Potential painkillers are always better than potential vitamins (solutions that may do something useful but don't remove something the user dislikes).

Long email conversations are a last resort.  Do not use surveys or other digital data-capturing mechanisms.

## How many people should we interview?

As a general guideline, it is recommended that a group conducts no fewer than 50 collective interviews. However, this number may vary based on your domain and group size, with larger groups expected to conduct more interviews. Additionally, the accessibility of your target users will be taken into consideration. For instance, if you are targeting students or professors, we anticipate more than 50 interviews since you are part of a university community. It's worth noting that your users may differ in their professions and roles. If your focus is on medicine, you can interview doctors, nurses, administrators, patients, and so on.

The more people you interview, the better. Conducting more interviews allows you to identify and concentrate on segments where you can add value. Therefore, in the first four or five weeks, you should aim to conduct as many interviews as possible. After this time, you will be creating prompts and prototypes, and then seeking feedback from those you interviewed.

It is important to keep in mind that your group will be compared to other groups. If another group interviews 100 lawyers while your group interviews only 20, it will be evident that you put in less effort. Unlike other Khoury courses, this course does not require you to spend a significant amount of time coding up a project. There are no time-intensive homework assignments, only quizzes on written lectures. As a result, we expect you to utilize this time to conduct interviews.

### Advice on getting interviews

* Reach out to family and friends
* Reach out to NEU alumni and alumni from your other schools on LinkedIn
* Reach out to places where you've interned or where you've done a coop
* Reach out to other members of your associations and clubs
* Ask professors you have a good relationship with
* Ask for recommendations from people you interview

## Responsible research, privacy and security

Users may provide artifacts, such as data and documentation. Beware of privacy considerations in accepting and handling this information. Follow these guidelines:

* Do follow NEU's [Policy on Responsible Conduct of Research](https://policies.northeastern.edu/policy500/#:~:text=All%20Northeastern%20University%20undergraduate%20students%2C%20graduate%20students%20and,for%20Instruction%20in%20the%20Responsible%20Conduct%20of%20Research.)
* Do accept information in the public domain (e.g., job postings).
* When someone gives you something in confidence, do respect their confidence and de-identify information.  It is OK to submit de-identified information as part of your project milestones.
* Do not make project files publicly accessible.  Restrict access to members of your team and the instructors.
* Do use encrypted email if sensitive information is being transferred.
* Do use code names when appropriate.
* Do use good judgment in accepting information.
* Don't accept personally identifiable information of third parties (e.g., lists of customers)
* Don't accept health or medical data.

### For politically-themed projects 
There are federal regulations on conducting political research or political activity within a university setting. If your project focus is political in nature, you need to first talk to the [Office of General Counsel](https://generalcounsel.northeastern.edu/about/contact-us/).

### Do not compromise your personal safety
Avoid putting yourself in unsafe situations.  Favor videoconferencing over face-to-face meetings.  If doing a face-to-face meeting, bring a friend.

## Team formation
Teams should be finalized by the first week.  Changes will be allowed during the second week.  The typical team has five people.  More is possible.  Teams should have no less than three people.  Larger teams are fine.  Smaller teams are not -- they create more work for the TAs and do not lead to better results.  If you have a strong desire to work on your own, find teammates who will allow you to work on things you want to work on and will work on things you don't want to work on.

## Prompts, code, and rapid prototyping

Some of your project milestones will involve provide prompts and Jupyter notebooks that run the prompts through an API.  When we evaluate your prompts, we will ask the following questions:
* Are these prompts or set of prompts specific to the results of their research?
* Do the prompts incorporate specific information from this domain, such as context provided by a user?  Is it clear how the output of the prompts would fit into some downstream components of an overall 
workflow?

### Code for prompting
There are some Python libraries that help interface with public LLM APIs and do general prompt engineering tasks, such as langchain, Semantic Kernel, and Guidance.  Use these if the features of these libraries help you with your rapid prototyping.  You will not be evaluated for how well you use these tools.

### Rapid prototyping
Some milestones will include prototypes that you can go back and share with users to get feedback.  These prototypes should be **quick and dirty**.  The goal should be to get your idea to a place where you can get external validation.  Ways of doing this could include:

* A low fidelity wireframe built with a wireframing tool.  You can use tools like Figma if you already know how, but note that even presentations tools like Keynote or Powerpoint can be used for wireframing
* A Jupyter or Google Colab notebook
* A video of a workflow

On the more complicated side, you could spin up a quick app in a no-code or low-code app building tool like bubble.io or lightning.ai.

But **prototypes should be rough**.  Rough prototypes ensure your feedback focuses on what matters.  If you have a more polished prototype, people will be less likely to give you feedback that would take you in a different direct because they think you've already invested too much effort.

## Assessment Criteria and Grading Rubric
Each week you will submit a predefined set of project milestones.  The TAs will check your work and use it as part of their calculation of your participation grade. 

### Weekly grades and late submissions

The *rough* rubric is as follows:
* A if the TA judges that your team is putting forth a good faith effort.  * B if your team is putting forth a good faith effort but is missing some elements.
* C if the you are not putting forth a good faith effort
* I (incomplete) if your work is not complete.

In Canvas, you will be able to submit work late.  However, the TA has **full discretion** in how they handle late submissions.

TAs have a heavy load in managing and monitoring this class, and are taking other classes and have other responsibilities outside of their TA work.  So they are not required to chase down and evaluate late work.  You may email late work to your TA, but you will have to convince them TA to grade it, and they are not obligated to update an incomplete grade. 

Submit your work on time.  But submit late work if it unavoidable.  All of your work will be considered in your final grade, whether it is late or not. 

At the end of the semester, you will create a final presentation deck and video demo of your prototype.  You will present these items in a final presentation and then submit them for grading.

### Code is not evaluated in your final grade

Your final demo video should show demonstrate how your proposed solution would work. Ideally, it should show the following
* The problem it is solving for the user
* A depiction of the user journey -- when, why, and how the user would interact with the tool, the types of inputs that would go in, the types of outputs they would get from it, and what they would do with those outputs.
* Anything that shows how impactful this tool would be if deploy (e.g., total addressable market) 

**Your will not be evaluated on code.  You will not be evaluated on whether you have a polished app.** You are not required to submit code.  Your instructor might ask to see your code and prompts, but it will not be used to assign you a grade.


