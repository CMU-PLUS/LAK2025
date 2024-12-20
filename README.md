# Does Multiple Choice Have a Future in the Age of Generative AI? A Posttest-only RCT  

## Citation  

Thomas, D. R., Borchers, C., Kakarla, S., Lin, J., Bhushan, S., Guo, B., Gatz, E., & Koedinger, K. R. (2025). *Does Multiple Choice Have a Future in the Age of Generative AI? A Posttest-only RCT*. In *Proceedings of the 15th International Learning Analytics and Knowledge Conference (LAK 2025)*. Association for Computing Machinery. [https://doi.org/10.1145/3706468.3706530](https://doi.org/10.1145/3706468.3706530)  

```bibtex
@inproceedings{thomas2025mcqfuture,
    author    = {Thomas, Danielle R. and Borchers, Conrad and Kakarla, Sanjit and Lin, Jionghao and Bhushan, Shambhavi and Guo, Boyuan and Gatz, Erin and Koedinger, Kenneth R.},
    title     = {{Does Multiple Choice Have a Future in the Age of Generative AI? A Posttest-only RCT}},
    booktitle = {Proceedings of the 15th International Learning Analytics and Knowledge Conference},
    series    = {LAK 2025},
    location  = {Dublin, Ireland},
    publisher = {Association for Computing Machinery},
    address   = {New York, NY, USA},
    doi       = {10.1145/3706468.3706530},
    month     = {03},
    year      = {2025}
}
```
---
This project explores the application of Learning Analytics (LA) and Generative AI for scalable online tutor advocacy training. It contributes to the Learning Analytics and Knowledge (LAK) community by presenting a dataset comprising lesson log data, human annotation rubrics, and generative AI prompts, promoting transparency and reproducibility.

RQ1: What differences exist in tutor learning, as evidenced by posttest performance, across the pre-instruction activities, i.e., MCQ only, open response only, or both? <br/>
RQ2: Under which contexts, do MCQs, open-response questions, or a combination of both yield the highest accuracy and efficiency, thereby optimizing the impact of the lesson? <br/> 
RQ3: How effective is generative AI, specifically the large language model like GPT-4o, in assessing posttest performance during tutor training?  <br/>

---
## Accessing Lesson Log Data from DataShop  

This project uses the dataset stored in DataShop. The details for accessing the dataset are below. You can either click on the link to access the data or search for it based on the information provided.  

- **Project Name**: PLUS (public)  
- **Dataset Name**: All_Data_Advocacy_Lessons_LAK25  
- **DataShop Link**: [Link]([https://pslcdatashop.web.cmu.edu](https://pslcdatashop.web.cmu.edu/DatasetInfo?datasetId=6250))  
- **Dataset ID**: 6250  

### Steps to Access the Dataset  

1. To access any dataset, you must have a registered account with DataShop.  
2. Once logged in, navigate to the DataShop home page and use the search bar to find the dataset by its name:  
   - **Dataset Name**: All_Data_Advocacy_Lessons_LAK25  
   - **Project Name**: PLUS (public)  
   Alternatively, use the provided DataShop link directly (see above).  
3. From the **Dataset Info** tab, navigate to the **Files** tab and click on the file name:  
   - `All_Data_Advocacy_Lessons_LAK25 - All Data.csv (13 MB)`  
   to download the dataset.  
---

Below is a brief explanation of the provided data fields.

Sample_Name - Name of dataset sample - all lessons in this dataset are Advocacy lessons<br/>
Transaction_Id - Unique identifiers for each interaction on the tutor platform <br/>
Anon_Student_Id - Anonymized identifier for each student/tutor <br/> 
Session_Id - Unique identifiers for each student/tutor log-in session<br/> 
Time - Timestamp for when lesson response was recorded<br/> 
Time_Zone - The Timezone in which the time or lesson response was recorded<br/> 
Duration_(sec) - Duration of student/tutor interaction on platform<br/> 
Student_Response_Type - The type of response provided by the student/tutor<br/> 
Student Response Subtype - Additional classification for the student/tutor response type<br/>
Tutor Response Type - Type of response provided by the student/tutor (answer evaluator)<br/>
Tutor Response Subtype - Additional classification for the student/tutor response type<br/>
Level (Lesson) - Name of the lesson<br/> Level_(Level2) - Response classification<br/>
Level_Level2_corrected - Corrected version of response classification to have uniformity<br/>
Problem Name - Specific question that the student/tutor is answering<br/> 
Problem View - View of the problem number<br/> 
Problem Start Time - Timestamp for when the problem was attempted<br/> \Step Name - Action taken by the student/tutor by question<br/> 
Attempt At Step - Number of attempts for the specific step<br/> 
Is Last Attempt - Indicates whether this is the last attempt at the step (1 for yes, 0 for no)<br/> 
Outcome - Result of attempt for MCQ<br/> 
MCQ_score - Multiple-choice question score (1 for correct, 0 for incorrect)<br/> 
Selection - Selection made by the student/tutor<br/> Action - Action taken by the student/tutor<br/> 
Input - Input provided by student/tutor<br/> 
Rater1_codes - Codes assigned by rater1 for open response questions to student/tutor response (1 for correct, 0 for incorrect)<br/>
Rater2_codes - Codes assigned by rater2 for open response questions to student/tutor response (1 for correct, 0 for incorrect)<br/> 
Open_response_score_human_truth - Source of truth determined between two raters for open-response questions<br/> 
Feedback_Text - Textual feedback provided to response<br/> 
Feedback_Classification - Classification of the feedback<br/> 
Help_Level - Level of help provided<br/> 
Total_Num_Hints - Number of hints used<br/> 
KC (Single-KC) - Knowledge component (KC) linked to the step, representing a single skill or concept<br/> 
KC Category (Single-KC) - Category of KC for the step<br/> 
KC (Unique-step) - Unique identifiers for KC<br/> 
KC Category (Unique-step) - Category of unique KC identifier<br/> 
School - School or organization through which student/tutor takes the course<br/> 
Class - Class of the lesson<br/> CF (AI_Evaluation) - Evaluation of response by AI (1 for correct, -1 for incorrect)<br/> 
CF (AI_Rephrased_Response) - AI rephrased version of the incorrect response<br/> 
CF (AI_Request_Counter) - Counter for AI requests<br/> 
CF (Condition) - Condition of the question between Mixed, Open response, and MCQ<br/> 
CF (Counterbalanced) - Order of scenarios counterbalanced<br/> 
CF_Counterbalanced_corrected - Corrected version of the order of scenarios counterbalanced to have uniformity<br/> 
CF (Sequence) - Sequence in which events occur<br/> 
CF (tool_event_time) - Timestamp for the tool event<br/> 
CF (tutor_event_time) - Timestamp for the tutor event<br/> 
Event_Type - Type of event recorded<br/>
