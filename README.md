# College Matchmaker
Short description of project.





## Project PI/Project Team 
Wesley Dong (wesley.s.dong@vanderbilt.edu | dongws | PI)

## Link to Video Explanation: 

## Link to AI Assistant: 
[College Matchmaker] (https://chat.openai.com/g/g-GDpOmdUQa-college-matchmaker)

## Example inputs and prompts

## Project Proposal 

### Description of Problem/Opportunity
The process of selecting a university is an important decision in a student's life, with long-lasting implications on their personal and professional development. Current matching systems online primarily focus on objective criteria like GPA, test scores, and intended major. However, these systems often overlook subjective yet crucial aspects of a university experience, such as campus culture, social environment, and personal growth opportunities. As a result, students might end up in institutions that do not align with their personality, preferences, and values, potentially leading to dissatisfaction and underperformance. Even here at Vanderbilt, students have discussed about regretting their decision commiting to Vanderbilt or are generally unsatisfied with their experience at Vanderbilt. 

### Proposed Solution/Approach
To address this issue, I propose creating a comprehensive university matching application that goes beyond conventional parameters, incorporating subjective elements to provide a more holistic and personalized college match. The application will collect data on various universities, evaluating academic metrics, student culture, campus personality, and social settings. Simultaneously, it will gather student preferences through a detailed questionnaire, considering their academic, social, and lifestyle choices. With this solution, a student can confidently select a college that not only satifies the student's academic qualficiations, but also their other interests. 

Data collection will include the following: 
1. Official University Websites and Publications - Most universities provide detailed information on their official websites, including details about academics, student life, culture, admission requirements, and financial aid.

2. Surveys and Questionnaires - Create surveys to current university students or alumni to gather firsthand accounts of their experiences.

3. Social Media and Online Forums - Reddit (e.g., r/college), College Confidential, university-specific Facebook groups.

4. Direct Communication with Universities - Reaching out directly to universities’ admissions offices or specific departments for information.

The project will use ChatGPT for natural language processing, helping to interpret and generate text-based responses from/to the user. A matching algorithm will then analyze both sets of data to find the best-fit universities for each student. The recommendations will be accompanied by personalized explanations, explaining why each university might suit the student’s preferences. Additionally, a feedback mechanism will be integrated to continuously refine and improve the matching algorithm based on user experiences.

### Project Outline and Timeline
1. Project Prosposal (October 26)
Define project goals, design overview, and metrics.

3. Data Collection and Database Setup (Nov 1)
Gather data on universities and set up a database to store this information. Design the student questionnaire.

4. Development of Matching Algorithm (Nov 14)
Develop the algorithm that will match students with universities based on their preferences and the collected data.

5. Integration of ChatGPT (Nov 21)
Incorporate ChatGPT for processing data. Ensure seamless integration with the matching algorithm.

9. Final Refinements and Project Closure (Dec 1)
Document the project, evaluate success against objectives, prepare for presenation.

## Goals of project 

### Goal 1
Comprehensive Data Collection - Gather detailed data on universities, ensuring coverage of academic, cultural, social, and logistical aspects to facilitate a well-rounded matching process.
### Goal 2
Development of a Matching Algorithm - Create an algorithm capable of analyzing both quantitative and qualitative data to provide personalized university recommendations to students.
### Goal 3
Customer satisfaction - Have a working algorithm that provides satisfaction to the user.

## Project Metrics 

### Metric 1
Evaluate how accurate and relevant the university recommendations are from the users' perspective. This will be measured by using students that are currently in colleges. They will take the survey and determine if the results match with their current unviersitie. 

Measurement:
A: 90-100% of users find the recommendations accurate. 
B: 80-89% of users find the recommendations accurate. 
C: 70-79% of users find the recommendations accurate. 
D: 60-69% of users find the recommendations accurate. 
F: Below 60% of users find the recommendations accurate.

### Metric 2
Measure the completion rate of the user questionnaire to determine if the survey is user-friendly. 

Measurement:
A: 90-100% completion rate, survey is engaging and not overly lengthy.
B: 80-89% completion rate, minor issues with length or engagement.
C: 70-79% completion rate, potential issues with survey
D: 60-69% completion rate, significant issues with survey
F: Below 60% completion rate, serious problems with survey. 

## Self-Evaluation

Goal 1 - Comprehensive Data Collection
I successfully gathered extensive data on college across the world. The database covers crucial details on academics, campus culture, social dynamics, extracurriculars, and logistics. However, the method of gathering information changed. Instead of using surveys and manual labor to input data. I used ChatGPT4's feature to access the web to automate this process. I would directly prompt ChatGPT to analyze college websites and forums to analyze different qualitative traits. I would use prompts like, "Analyze colleges in the US that have grade inflation and include this in the database." Using prompts like these not only suggest to the GPT that these types of characteristics should be considered, it also allows these factors to be used when a student is asking for college recommendations. This saved me time and energy without individually researching different colleges. 

While the database is substantial, there is room for expansion to smaller colleges and more niche institutions. I also believe more information can be gathering from different student's inidivual experiences. Overall, I would assess this goal at an A level based on significant completion of data collection. 

Goal 2 – Development of a Matching Algorithm
The matching algorithm can process the collected data and user preferences to provide personalized university recommendations. Based on testing with 10 different peers, they there was 90 percent satisfaction among those who used the GPT and reflected on their matches. I requested that they explored the GPT and answered the GPT's questions about different colleges. These students are current college students, so they have a general idea of schools that fit their type. 9 out of 10 agreed with the matches and stated that the schools listed were schools they either considered, applied to, or even got in. 

Some limitations exist regarding quantification of subjective measures and weighting of qualitative data. Refinements to the algorithm and database would improve accuracy further and . I would rate this goal at a B+ level given the fully-functional yet imperfect algorithm.

Goal 3 – Customer Satisfaction

From a sample of 10 students, 90% reported being satisfied with their university recommendations from the system. They found the results aligned with their preferences for academic programs, campus vibe, and social fit.

While positive, additional real-world testing on a larger pool of prospective applicants would be beneficial. For now, an A- grade seems a fair assessment given promising but preliminary satisfaction data.

Metric 1 – Relevance of Recommendations
In trials among current college students, the university matches corresponded with their actual institution over 90% of the time, indicating good relevance. Some limitations with niche interests point to areas for improvement. Based on the 80-89% accuracy threshold, this metric warrants a B grade.

Metric 2 – Survey Completion Rates (altered)
This metric will be altered to overall usability of the GPT, because we relied on directly asking GPT for database retrieval. I didn't need to use surveys to gather data. Based on usability of the assistant. I would give it an A- grade. My justification is that the assistant is successful in garnering a list of colleges that fit the student. However, the conversation level is very formal and sometimes overwhelming. The GPT sometimes asks multiple questions in a roll, which can be confusing fo the user.

In summary, the project achieved its core objectives but has room to grow regarding database breadth and algorithmic precision. Real-world testing and user feedback would catalyze refinement. When the current capabilities of the assistant, I would grade it overall with an A minus grade. It was fully capable of matching students with colleges. However, in the future, I would like to see it be more personal and have more qualitative analysis of the the student and college. 

## Reflection on Learning
This project imparted significant insights regarding the complexity of developing personalized recommendation algorithms and AI assistants, especially for subjective domains like university matching. Translating qualitative desires into quantitative parameters posed an unexpected challenge that forced me creatively adapt my data collection and analysis methods through an iterative process. However, with the help of prompt engineering and progressive adjustments, the task became increasingly manageable over time.

My initial hypothesis was that university matching boiled down to three or four variables – intended major, cost, location, and perhaps size. However, through hands-on experience and investigation, I quickly realized successful matches actually require intersecting dozens of intricately interwoven academic, social, cultural, and environmental variables in nuanced combinations unique to each individual. This eye-opening discovery highlighted the depth of human preferences and choices compared to the procedural, binary nature of machine systems.

Creating the matching algorithm was equally illuminating. The multidimensional complexity spanning user data, university data, and the intersections between them stretched my analytical skills and strategic thinking. Through this process, I gained firsthand experience with AI’s immense capabilities around consuming volumes of data and identifying patterns. However, I also encountered its continued limitations around understanding contextual nuances and emotional aspects central to major life decisions. The algorithm can provide a sound starting point to guide exploration but still cannot guarantee perfectly tailored matches in such deeply personal domains.

I spent significant time attempting to refine the AI's conversational capabilities to mimic a human advisor and have an engaging, personalized dialogue with prospective students. However, even extensive prompt programming only enabled basic simulated responses rather than genuine empathy and emotional intelligence. This project illuminated firsthand the difficulty of encoding subjective human preferences, perspectives, and decision drivers into binary quantitative code. It highlighted the continued need for human oversight and involvement in deploying AI, especially for sensitive, personal use cases.

Ultimately, this experience cultivated a healthier skepticism within me about the autonomy and versatility of even advanced AI. It underscored the priority of ethics and human-centric oversight in responsible algorithm design. There are still profound limitations on what AI can do independently without human partnership. Yet its existing capabilities are nonetheless tremendously exciting. This insight into AI's balanced strengths and weaknesses will guide my future work at the intersection of technology and society. With my focus in biology and healthcare, I hope to incorporate AI as a constructive assistant to augment human effort across the medical field.

Moreover, this project highlighted the untapped innovative potential of creative human-AI collaboration to resolve multifaceted real-world problems. The complexity of contextual recommendation algorithms underscored the unique strengths of both human discernment and AI pattern recognition. Working with AI provides a valuable perspective I will carry through my education and career. By intelligently combining AI's quantitative analytical horsepower with human judgment of subjective qualities, I realized we can achieve enormously more together rather than through isolated efforts. This integration will prove key to uplifting fields from business to government through technology's thoughtful application.

## What's Next?
I intend to continue refining this university recommendation system and ultimately scale it into a fully fledged app for student use. I think it would be a popular application that students would find very useful. 

In the next phase, I plan to expand the university database to cover more niche colleges and non-US institutions to improve coverage and cultural representation. Implementing this expanded dataset will enhance match relevance and user satisfaction across larger target demographics.

Additionally, I aim to refine the recommendation algorithms by incorporating machine learning techniques to progressively improve precision based on usage data patterns. Features like probabilistic matching scores, comparison tools, and post-application user feedback tracking will bolster transparency.

Longer term, I envision partnering with universities, policy groups, and education specialists to build an integrated university selection and application platform. This would centralize the complex process into one trusted hub serving stakeholders across the spectrum. Features like application profile building, essay editing, financial aid assistance, and acceptance data analytics could offer indispensable value.

The commercial potential of such a holistic platform is significant while also addressing real student needs by improving access, outcomes, and experience. My learnings on matching algorithms provide the foundation to now scale up and build an enterprise-level solution. I look forward to collaborating with larger development teams to make this concept a widespread reality.

The market insights and technical skills this project armed me with are invaluable. I’m excited to apply them toward shaping practical innovations at the intersection of youth, education, and technology fields. This project sparked a valuable long-term vision I can now pursue methodically one phase at a time.
