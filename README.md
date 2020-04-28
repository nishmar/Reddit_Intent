# Reddit_Intent
<b>Venting or Seeking Advice? Classification of Reddit posts by intent.</b>

This project will explore sentiment patterns and model topics present in Reddit with a focus on identifying and classifying author intent in Reddit, an online discussion forumn composed of subreddits, or subforumn for particular topics. The subreddits r/Vent and r/Advice, along with other similar subreddits, will be used to model post intent for the general population, as by definition all posts submitted to these particular subreddits express the subreddit's intent (vent or seek advice). These analyses will be repeated and extended upon on populations of persons with mental health disorders.

In order to model intent on populations of persons with mental health disorders, subreddits focused on mental health which use "flairs", posts tagged with content or user intent ("Input", "Vent") will be used. One subreddit involving mental health disorders that will be explored is for persons with Borderline Personality Disorder (BPD) at the r/BPD subreddit. BPD is a mental disorder best characterized by emotional dysregulation, which is believed to be developed through a combination of genetic and early traumatic experiences. At /r/BPD, users posts on a variety of topics and since 2016 mark their posts with "flairs" denoting the intention of the post. For example, some are flaired "Venting" indicating the user does not want input or suggestions, while others are "Seeking Support", clearly requesting advice. Other identified mental health communities that tag their posts with intent are r/CPTSD, r/Anxiety, and r/depressionhelp. Anxiety and depression are mood disorders highly prevalent in the population, while CPTSD is complex Post-Traumatic Stress Disorder, a variant of the widely-known Post-Traumatic Stress Disorder (PTSD). 

<b>Justification: </b>

[In Progress ...] 

<b>Mental Health Applications:</b>

Phone applications for mental health can be useful tools aiding individuals to track and relieve symptoms. Popular applications include mood or symptom trackers and chatbots that suggest skills, such as CBT exercises or mindfulness. At present, mood trackers rely on users to manually input their mood, which must be tracked at regular intervals, and the the majority of mental health chatbots use limited, rule-based methods. Obstacles to technologies that would leverage supervised machine learning include lack of human annotated data regarding mood and intention that could be used to train chatbots to interact with users or suggest proper techniques, i.e. when is someone venting vs. asking for advice? In addition, there is a gap in mental health tools available: a comprehensive survey shows most apps are targeted towards depression and autism. There are not enough tools available to sufferers of trauma and emotional dysregulation for which evidence-based treatement DBT is available. 

For a Mental Health Chatbots overview, see: 
https://doi.org/10.1016/j.ijmedinf.2019.103978

<b>File Index </b>
- Get Reddit data.ipynb : Details Reddit data acquisition via PSAW API.
- Data_Cleanup_and_Sentiment.ipynb : Data clean-up and sentiment scores via Vader. 

[In Progress ...]
