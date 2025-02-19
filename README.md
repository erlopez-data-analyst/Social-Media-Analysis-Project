# Soical Media Consumption Impact on Mental Wellbeing

## Purpose/Goal
The primary goal of this project is to provide data-driven insights into the ways social media can affect mental well-being.  Specifically, this analysis seeks to:
* **Identify Correlations:** Determine if and how various aspects of social media use (e.g., total time spent, device type, platform, scroll rate) correlate with mental well-being indicators (e.g., satisfaction, productivity loss, addiction level, self-control).
* **Uncover Trends:**  Explore trends within the data to understand if certain demographics, age groups, or usage patterns are more susceptible to negative impacts.
* **Quantify Impact (Where Possible):**  While causation is difficult to establish definitively, this project will attempt to quantify the potential impact of social media on mental well-being wherever the data allows.  For example, can we observe statistically significant differences in mental well-being metrics between different usage groups?
* **Inform and Educate:**  Ultimately, this project aims to inform a broad audience, including individuals, parents, educators, and policymakers, about the potential risks associated with excessive or unhealthy social media use.  The findings will be presented in a clear and accessible way, highlighting key takeaways and actionable recommendations.
* **Empower Healthier Habits:**  Beyond simply identifying problems, this project will offer insights and recommendations for developing a healthier balance with social media.  This could include strategies for mindful usage, setting boundaries, and promoting positive online interactions.

## Dataset Information
* **Source:** [Dark Side Of Social Media](https://www.kaggle.com/datasets/muhammedroshanriaz/dark-side-of-social-media) (Kaggle)
* **Size & Structure:** The dataset comprises 1000 rows of data and 31 columns, representing various user attributes and social media usage patterns.
* **Variables:** The dataset includes the following variables:
    * `User ID` (Primary Key)
    * `Age`
    * `Gender`
    * `Location`
    * `Income`
    * `Debt`
    * `Own Property`
    * `Profession`
    * `Demographic`
    * `Platform` (Social media platform used)
    * `Total Time Spent` (on social media)
    * `Number of Sessions`
    * `Video ID`
    * `Video Category`
    * `Video Length`
    * `Engagement` (with content)
    * `Importance Score`
    * `Time Spent on Video`
    * `Number of Videos Watched`
    * `Scroll Rate`
    * `Frequency` (of social media use)
    * `Productivity Loss`
    * `Satisfaction` (with social media use)
    * `Watch Reason`
    * `Device Type`
    * `OS` (Operating System)
    * `Watch Time`
    * `Self Control`
    * `Addiction Level`
    * `Current Activity`
    * `Connection Type`
* **Limitations:** This dataset has some limitations that should be considered when interpreting the results.  Notably, it lacks information on:
    * Sleep patterns
    * Previous/current mental health issues
    * Eating habits
    * Physical health habits

These missing variables could play a significant role in an individual's overall well-being and may influence their social media usage and its perceived impact.  Therefore, while the analysis can reveal valuable insights, it's important to acknowledge these limitations and avoid drawing overly conclusive causal relationships.  Future research incorporating these factors would strengthen the analysis.

## Key Research Questions
* **Demographics:**
    * **Q1**. How does Total Time Spent on social media platforms differ across demographic factors (age, gender, location)?
      * **Business Relevance**: Helps companies target marketing efforts, tailor content, and understand how different demographics engage with social media.   
* **Behavior:**
    * **Q2**. How are platform, content types, and usage frequency related to average Total Time Spent on social media?
      * **Business Relevance**: Provides insights into user engagement patterns, content preferences, and optimal times to reach target audiences.
    * **Q3**. Do different motivational factors (e.g., boredom, procrastination) lead to variations in social media usage patterns?
      * **Business Relevance**: Helps companies understand why users engage with social media and how to tailor content or features to meet those needs.
* **Well-being:**
    * **Q4**. Do high amounts of social media consumption impact individuals' mental well-being (addiction, self-control, satisfaction, productivity)?
      * **Business Relevance**: Raises awareness of the potential impact of social media on well-being, which is crucial for companies concerned about ethical considerations and user experience.
* **Content Preferences:**
    * **Q5**. How do content preferences vary across different demographic groups?
      * **Business Relevance**: Informs content creation and targeting strategies based on demographic preferences.
    * **Q6**. Are there associations between content preferences and motivational factors or well-being outcomes?
      * **Business Relevance**: Helps companies understand how content preferences relate to user motivations and well-being, which can inform content strategies and platform design.

## Methodology
* **Data Cleaning & Processing** The Data was cleaned using Microsoft Excel to ensure it was prepared for analysis. Overall, data was well prepared, and minor issues were noticed such as Typos, Misspelling, and Formatting errors. (e.g., Income not in currency, DeviceType -> Device Type, Barzil -> Brazil).
* **Statistical Analysis** Statistical processes used to get a better understanding of the dataset were descriptive, correlation, ANOVA, coefficient, and regression analysis. 
* **Visualization** Graphs and charts are developed in Tableau to grasp the trends and patterns found within the dataset.

## Analysis and Findings

This project employed a range of statistical methods to investigate the relationship between social media usage and various factors related to wellbeing, behavior, and preferences.  Key findings are summarized below:

**Correlation Analysis:**

A strong negative correlation was observed between "Productivity Loss" and "Satisfaction," indicating that higher productivity loss is associated with lower satisfaction with social media use.  A similar strong negative correlation was found between "Addiction Level" and "Self Control," suggesting that higher addiction levels are linked to lower self-control. These correlations highlight the complex interplay between social media use, self-control, productivity, satisfaction, and addiction.

**ANOVA Analysis:**

Multiple ANOVA analyses were conducted to explore the relationship between various independent and dependent variables related to demographics, behavior, content/platform preferences, and temporal factors.  However, no statistically significant differences (p > 0.05) were found between the tested variables.  Specifically:

* **Demographic Factors:** No significant relationships were found between total time spent, number of videos watched, or number of sessions and age group, gender, or location.
* **Behavioral Factors:** No significant relationships were found between engagement, total time spent, number of sessions, or number of videos watched and watch reason.
* **Content & Platform Preferences:** No significant relationships were found between total time spent, number of sessions, or number of videos watched and video category, platform, or device type.
* **Temporal Factors:** No significant relationships were found between total time spent, number of sessions, or number of videos watched and watch time or frequency.

**Regression Analysis:**

While individual predictors like age, gender, device type, platform, and watch reason generally did not show strong or statistically significant effects on social media usage patterns or related outcomes, the *frequency* of social media use emerged as a significant predictor of both productivity loss and addiction level.  Specifically:

* Individuals who use social media most frequently in the morning or evening tend to report higher productivity loss.
* Individuals who use social media most frequently at night tend to report higher addiction levels.

## Analysis and Findings

### Dashboard 1: Social Media Consumption Patterns

[Social Media Consumption: Demographic Insight Dashboard](https://public.tableau.com/app/profile/erik.lopez4836/viz/SocialMediaConsumptionDemographicInsight/SocialMediaConsumptionDemographicDashboard)

**Key Takeaways:**

* **Watch Reason:** Users spend significant time on social media due to habit, boredom, entertainment, and procrastination, with habit being the most prominent driver. This raises concerns about potential unhealthy usage patterns.
* **Watch Category:** Jokes/memes and life hacks are the most popular video categories across platforms. Facebook shows lower consumption in these categories, suggesting platform-specific content preferences.
* **Watch Time:** Social media activity peaks in the late afternoon and evening, particularly around 2:00 PM and 9:00 PM, indicating higher engagement during leisure hours.
* **Gender Differences:**  Individuals identifying as "Other" report higher productivity loss, importance, and time spent on social media but lower addiction levels compared to males and females. Males tend to spend more time overall on social media than females and those identifying as "Other."

**Critical Thinking and Insights:**

* **Habit Formation:** The high time spent due to habit may be linked to the addictive nature of social media platforms, designed to keep users engaged and potentially leading to habitual checking and scrolling.
* **Boredom and Procrastination:** Social media can serve as a means of escapism or procrastination, possibly due to its ease of access and constant stimulation. Users engaging with social media out of habit or boredom might lack alternative activities or hobbies.
* **Content Preferences:** The popularity of jokes/memes and life hacks could be attributed to their short-form, easily consumable nature, providing quick entertainment and information.
* **Platform Variations:** Facebook's lower consumption of jokes/memes and life hacks might be related to its older user base and focus on longer-form content, unlike platforms like TikTok or Instagram.
* **Time of Day:** Peak usage in the afternoon and evening aligns with typical lunch breaks and after-work hours, suggesting social media use is more prevalent during leisure time.
* **Gender Dynamics:** Higher productivity loss among females could be linked to social pressures and time spent curating online profiles. Gender differences in content preferences (e.g., females leaning towards trends, males towards life hacks and gaming) may reflect societal norms and expectations.
* **Social Norms and Expectations:** Gender differences in overall time spent on social media could be influenced by societal norms and expectations around technology use, leisure activities, and social interaction.

**Limitations and Future Research:**

* This analysis relies on self-reported data, which may not be entirely accurate. Future studies could incorporate passive data collection methods for a more objective view.
* Further research could explore the specific types of jokes/memes and life hacks consumed by different genders to understand potential differences in preferences.
* Investigating the impact of social media on various aspects of well-being, such as sleep quality, mental health, and self-esteem, could provide a more comprehensive understanding of its effects.

### Dashboard 2: Social Media Engagement and Well-being

[Social Media Consumption: Engagement & Well-being Insight Dashboard](https://public.tableau.com/app/profile/erik.lopez4836/viz/SocialMediaConsumptionMentalWellnessInsight/SocialMediaConsumptionMentalWellnessInsightDashboard)

**Key Takeaways:**

* **Number of Sessions:** Users tend to have more social media sessions when driven by boredom or procrastination compared to habit or entertainment, suggesting potential for distraction and procrastination.
* **Platform and Age:** Instagram usage is highest among 18-24 and 35-44 age groups, while TikTok appeals to a wider range (25-34 and 45-54). YouTube is dominated by the 18-24 age group. This highlights platform-specific demographics and content preferences.
* **Scroll Rate:** Higher scroll rates for pranks, ASMR, and trends suggest quick browsing, while lower rates for vlogs, entertainment, and life hacks indicate deeper engagement, possibly due to longer format or informative content.
* **Mental Well-being:** Users report high self-control but moderate productivity loss and importance of social media. Satisfaction is below average, potentially linked to habitual use and other factors.

**Critical Thinking and Insights:**

* **Boredom and Procrastination:** The higher number of sessions driven by boredom and procrastination reinforces the idea that social media can be a distraction and a means of avoiding tasks.
* **Platform-Specific Appeal:**  The varying usage patterns across platforms highlight how different platforms cater to different demographics and content preferences. Instagram's visual focus attracts younger adults and millennials, while TikTok's diverse content appeals to a broader age range. YouTube's long-form content draws in the 18-24 age group.
* **Content Engagement:** Scroll rates provide insights into how users engage with different content types. Deeper engagement with vlogs, entertainment, and life hacks could be due to their informative nature, longer format, or personal connection with creators. Higher scroll rates for pranks, ASMR, and trends might indicate quick consumption or less engaging content.
* **Well-being Paradox:**  Despite high self-control, the moderate productivity loss and below-average satisfaction suggest a complex relationship with social media. Users might feel in control but still experience negative impacts on productivity and well-being.
* **Potential Dissatisfaction Factors:** Several factors could contribute to lower satisfaction, including negative social comparison, content quality, addictive platform features, and habitual use leading to less intentional and fulfilling experiences.

**Limitations and Future Research:**

* This analysis relies on self-reported data, which may not fully capture the nuances of user experiences. Future studies could incorporate qualitative methods or passive data collection for a richer understanding.
* Further research could delve deeper into the reasons behind platform-specific preferences and how they relate to user demographics, content types, and platform features.
* Investigating the interplay between self-control, productivity loss, importance, and satisfaction could shed light on the complex relationship between social media use and well-being.
* Exploring interventions or strategies to promote more mindful and fulfilling social media experiences could be beneficial, especially given the prevalence of habitual use and lower satisfaction.

## Answering Key Research Questions
* **Demographics:**
    * **Q1**. How does Total Time Spent on social media platforms differ across demographic factors (age, gender, location)?
      * **Answer**: The ANOVA analysis indicated no statistically significant differences in Total Time Spent across age groups, gender, or location. However, you might still observe and discuss any trends or patterns, even if they weren't statistically significant. For example, did one age group tend to spend more time on social media, even if the difference wasn't statistically proven? Mentioning such trends can still be valuable for businesses. 
* **Behavior:**
    * **Q2**. How are platform, content types, and usage frequency related to average Total Time Spent on social media?
      * **Answer**: The ANOVA analysis didn't find significant relationships between Total Time Spent and video category, platform, or device type. However, your regression analysis showed that frequency of social media use is a significant predictor of both productivity loss and addiction level. Highlight this finding! Explain how more frequent use, especially in the morning/evening or at night, is associated with negative outcomes. This is valuable information for businesses.
    * **Q3**. Do different motivational factors (e.g., boredom, procrastination) lead to variations in social media usage patterns?
      * **Answer**: The ANOVA didn't find significant relationships between Watch Reason and usage patterns, your dashboard visualizations showed that users have more sessions when using social media for boredom or procrastination. Emphasize this finding! It suggests that certain motivations (boredom, procrastination) might lead to more frequent, potentially less intentional, social media use.
* **Well-being:**
    * **Q4**. Do high amounts of social media consumption impact individuals' mental well-being (addiction, self-control, satisfaction, productivity)?
      * **Answer**:  The analysis found strong negative correlations between Productivity Loss and Satisfaction, and between Addiction Level and Self Control. While your ANOVA didn't directly link usage amounts to these well-being factors, you can discuss the trends and the correlations together to paint a picture of how higher usage might be related to negative well-being outcomes. Also, highlight the finding from your second dashboard that overall satisfaction with social media is below average. This raises important questions about the impact of social media on well-being, even if direct causal links weren't established in this analysis.
* **Content Preferences:**
    * **Q5**. How do content preferences vary across different demographic groups?
      * **Answer**: The ANOVA didn't find significant relationships between video category and demographic factors. However, you can mention any observed trends or patterns, even if they weren't statistically significant. For example, did certain age groups tend to favor particular video categories? Also, highlight the finding from your first dashboard that Facebook has lower consumption of jokes/memes and life hacks, potentially indicating platform-specific content preferences.
    * **Q6**. Are there associations between content preferences and motivational factors or well-being outcomes?
      * **Answer**: Analysis displayed popularity of jokes/memes and life hacks is related to users seeking quick entertainment or information (Watch Reason). You can also speculate on how content preferences might relate to well-being outcomes, even if you didn't have the data to test those relationships directly.

## Recommendations

Based on the analysis and findings of this project, the following recommendations are offered to various stakeholders:

**For Social Media Companies:**

* **Promote Mindful Consumption:** Implement features that encourage mindful usage, such as screen time limits, usage trackers, and "take a break" reminders.
* **Prioritize Content Quality:** Invest in algorithms and content moderation strategies that prioritize quality content, diverse perspectives, and positive interactions.
* **Address Addiction:** Develop features that address potential addictive behaviors, such as limiting notifications, diversifying content recommendations, and providing resources for users concerned about their social media use.
* **Platform-Specific Strategies:**
    * **Instagram:** Leverage visual content, interactive features, and influencer marketing to engage younger demographics.
    * **TikTok:** Continue offering diverse content, including short-form videos, music, and comedy, to maintain broad appeal.
    * **YouTube:** Invest in long-form content, educational resources, and creator support to retain its dominance with the 18-24 age group.
    * **Facebook:** Explore strategies to revitalize the platform for younger audiences, potentially by incorporating features from other successful platforms or focusing on niche communities and interests.

**For Businesses Using Social Media for Marketing:**

* **Targeted Content:**
    * Tailor content to specific demographics, considering any observed trends in social media usage.
    * Align content with platform-specific preferences (e.g., shorter content for TikTok, longer-form content for YouTube).
    * Address user motivations for using social media (e.g., entertainment, information).
* **Timing and Frequency:**
    * Schedule posts and campaigns during peak usage times (late afternoon and evening).
    * Prioritize quality over quantity to maintain engagement and satisfaction.

**For Educators and Parents:**

* **Digital Literacy:**  Incorporate digital literacy and social media awareness into education, teaching mindful usage, critical thinking, and online safety.
* **Open Communication:** Encourage open conversations about social media use, its potential impacts, and strategies for a healthy balance.
* **Role Modeling:** Model healthy social media habits and set clear boundaries for children and teenagers.

**For Policymakers:**

* **Ethical Considerations:** Explore policies that address ethical concerns related to social media, such as data privacy, algorithmic bias, and mental health impacts.
* **Research Funding:** Support research on the long-term effects of social media use, especially on young people.

**For Individuals:**

* **Mindful Usage:**
    * Set screen time limits and "no-phone" times.
    * Curate content by following positive accounts and unfollowing those that trigger negative emotions.
    * Be mindful of why you're using social media and seek out meaningful content and connections.
* **Alternative Activities:**
    * Cultivate offline hobbies and activities that promote well-being.
    * Prioritize face-to-face interactions and meaningful relationships.
