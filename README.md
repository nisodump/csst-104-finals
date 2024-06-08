# Fitness Consumer Analysis

**Submitted by:** Neil Ivan S. Orencia

**Section:** BSCS-3A

## Introduction

This analysis evaluates consumer fitness behaviors and decisions by examining a range of demographic, socioeconomic, and engagement parameters. By analyzing the dataset, we aim to uncover how factors such as age, gender, education level, occupation, exercise frequency, duration of wearable device usage, and frequency of tracking fitness data impact individuals' fitness-related decisions and outcomes. 

The study focuses on understanding the influence of various motivational, enjoyment, and community connection aspects on key decisions such as exercising more, purchasing fitness products, joining a gym, and changing dietary habits. The findings will help identify critical elements that affect fitness behaviors and decisions, providing insights that can be used to enhance fitness programs, products, and policies to improve consumer health and well-being.

## Files
<a href="https://github.com/nisodump/csst-104-finals/blob/main/01_Title_Page_ML.pdf" target="_blank">1. Title Page</a><br>
<a href="https://github.com/nisodump/csst-104-finals/blob/main/02_Table_of_Contents_ML.pdf" target="_blank">2. Table of Contents</a><br>
<a href="https://github.com/nisodump/csst-104-finals/blob/main/03_Main_Page_ML.pdf" target="_blank">3. Main Page (Documentation)</a><br>
<a href="https://htmlpreview.github.io/?https://github.com/nisodump/csst-104-finals/blob/main/Fitness_Consumer_Analysis.html" target="_blank">4. Code Snippet PDF</a><br>
<a href="https://github.com/nisodump/csst-104-finals/blob/main/05_Sample_Dataset_Content.csv" target="_blank">5. Sample Dataset Content</a><br>
<a href="https://colab.research.google.com/drive/1GvWsWECFTKWwOTcXmrHUKFa_O0XFzL4V?usp=sharing" target="_blank">6. Google Colab Link</a><br>
<a href="https://htmlpreview.github.io/?https://github.com/nisodump/csst-104-finals/blob/main/Fitness_Consumer_Analysis.html" target="_blank">7. Code Snippet HTML and Jupyter Preview</a>

## Conclusion

### Visual Insights
The demographic analysis reveals that fitness products and services are particularly appealing to young, educated individuals, especially those who are still in school or at the early stages of their careers. To effectively reach this demographic, marketing efforts should focus on popular platforms such as social media, online fitness communities, and campus events. By doing so, fitness providers can align with the preferences and expectations of their primary consumers.

In terms of fitness habits and tracking behavior, the results emphasize the importance of supporting an active lifestyle and offering robust tracking features. There is a notable demand for educational content that helps new users maximize their use of wearables and data tracking. Highlighting the long-term benefits of consistent exercise and wearable usage can enhance customer retention and growth.

The impact distribution analysis indicates that the examined factors significantly enhance users' fitness experiences, leading to more consistent and enjoyable routines, improved health outcomes, and a stronger sense of community. These positive impacts highlight the necessity of incorporating these factors into the design of fitness programs and interventions to ensure maximum user satisfaction and effectiveness.

Lastly, the consumer behavior analysis suggests that addressing various aspects of fitness, including exercise, nutrition, and community support, is crucial for motivating participants to adopt healthier lifestyles and commit to their fitness goals. By focusing on these elements, fitness products and services can achieve greater user satisfaction, retention, and market success.

### Key Findings and Business Impact
The Cramér's V heatmap reveals fascinating insights into user behavior and preferences. Strong associations between `GoalImpact`, `HealthImpact`, `SleepImpact`, and `WellbeingImpact` underscore the importance of a diverse approach in wellness industries. Similarly, the interplay between `RoutineImpact`, `MotivationImpact`, and `EnjoymentImpact` suggests that businesses focusing on user engagement, like fitness apps or e-learning platforms, should prioritize creating impactful routines to boost motivation and enjoyment. Interestingly, the weak associations with decision-related variables and ExerciseFreq highlight the complexity of user decisions and habits which calls for deeper data analysis and personalized strategies. The moderate association between occupation and gender could inform targeted marketing efforts.

These insights exemplify the power of data-driven decision-making. By using such data, businesses can move beyond guesswork, optimize resources, adopt a customer-centric approach, and gain a competitive edge. In today's data-rich environment, companies that harness these insights can craft more resonant products and services, driving growth and user satisfaction. This heatmap underscores that success in various domains, from wellness to user engagement, is multifaceted and best navigated with the compass of data analytics. By understanding the multifaceted nature of user behavior and preferences, businesses can craft more effective strategies, optimize their resources, and ultimately achieve better outcomes in terms of growth, user satisfaction, and competitive advantage.

### Data Analysis Techniques
Based on the analysis of the Fitness Consumer Analysis dataset using statistical analysis df.describe(), several critical insights for businesses in the fitness industry has been revealed.

The data indicates a diverse customer base across age groups and genders, with varying exercise frequencies and moderate engagement with wearable fitness technology. Notably, the impact of fitness data on consumers' routines is generally positive, suggesting that data-driven insights can significantly influence behavior.

Moreover, fitness activities show a moderate to high impact on motivation, enjoyment, health, and overall wellbeing, underscoring the need for engaging and holistic fitness experiences. These findings have substantial business implications, from product development opportunities in wearable tech to refining marketing strategies that emphasize benefits.

The data also points to potential for improved customer retention through personalized insights, market segmentation based on diverse fitness habits, and cross-selling opportunities in fitness gear and nutrition. Interestingly, despite low community connection scores, high engagement and motivation metrics suggest untapped potential in community-building features.

Most importantly, this dataset underscores the indispensable value of data-driven decision-making in the fitness industry. By leveraging such data, businesses can optimize resource allocation, personalize user experiences, identify growth opportunities, measure and improve initiatives, and gain a competitive edge.

In an industry as personal and varied as fitness, the ability to make data-driven decisions can be the difference between a good business and a great one, driving growth, retention, and profitability.

Based on the analysis of the Fitness Consumer Analysis dataset using `Analysis of Variance (ANOVA)`, several key insights have been derived.

The dataset's p-values indicate that routine and motivation consistently show significant or near-significant impacts across various fitness-related decisions which highlights their critical importance. Community connection and enjoyment significantly influence the decision to exercise more, emphasizing the value of a supportive and enjoyable fitness environment. Additionally, the frequency of wearable technology usage and data tracking demonstrates significant impacts which suggests that integrating technology and data tracking into fitness programs can positively affect fitness decisions.

These insights can significantly impact decision-making processes within a fitness-related business or organization. By understanding the limited influence of demographic factors like age and gender, businesses can create more targeted and effective marketing campaigns that focus on motivational and technological aspects instead. Insights into the importance of wearable technology and exercise frequency can guide product development, leading to the creation of fitness solutions that integrate with users' lifestyles. Emphasizing community connection and enjoyment in fitness programs can enhance user engagement which lead to higher customer satisfaction and loyalty.

Using these insights for strategic planning ensures decisions are based on empirical evidence, leading to more effective outcomes. Understanding the key factors influencing fitness decisions helps create offerings to meet customer needs, improving overall business performance. In conclusion, the p-value analysis of the Fitness Consumer Analysis dataset underscores the importance of data-driven decision-making in the fitness industry. By focusing on factors that truly influence consumer behavior, businesses can develop strategies that enhance user experience, drive engagement, and ultimately achieve better business outcomes.

### Implementation of Machine Learning
The implementation of machine learning reveals that different machine learning models perform best for various prediction tasks related to fitness decisions.

For the decision to exercise more, the K-Nearest Neighbor (KNN) model stands out with an accuracy of 66.67%, precision of 72.22%, recall of 66.67%, and an F1 score of 65.48%, surpassing other models. Higher accuracy means the model correctly predicts more instances overall, higher precision indicates fewer false positive errors, higher recall means the model identifies more actual positive instances, and a higher F1 score shows a better balance between precision and recall.

In predicting the decision to buy products, the Gaussian Naive Bayes model excels, achieving the highest precision of 91.67% and an F1 score of 85.19%, with an accuracy of 83.33%, alongside other top-performing models. These metrics indicate the model's effectiveness in making correct positive predictions and maintaining a strong balance between precision and recall.

For the decision to join a gym, Random Forest, Gradient Boosting, and Support Vector Machine models perform equally well, each achieving an accuracy of 83.33%, precision of 100.00%, recall of 83.33%, and an F1 score of 88.89%. These high metrics suggest the models are reliable, make accurate positive predictions, and effectively identify positive instances.
Lastly, for the decision to change diet, both Logistic Regression and K-Nearest Neighbor (KNN) models are highly effective, each with an accuracy of 83.33%, precision of 87.50%, recall of 83.33%, and an F1 score of 82.86%, indicating great overall performance and balance between precision and recall.

These insights show the importance of selecting the appropriate machine learning model for specific prediction tasks to achieve optimal performance. By using these data-driven insights, fitness providers can make informed decisions to modify their products and services more effectively, enhancing user satisfaction and engagement. For instance, understanding which model best predicts the decision to buy products can help in targeted marketing strategies, while insights into gym membership decisions can inform membership retention programs.

### Advanced Analysis

The advanced analysis highlights the critical features influencing various fitness-related decisions, with each model revealing specific insights. For the decision to exercise more using the K-Nearest Neighbor (KNN) model, the most important features are EnjoymentImpact (0.1067), TrackDataFreq (0.0700), RoutineImpact (0.0600), CommunityConnection (0.0556), and Occupation (0.0511). These insights suggest that enhancing the enjoyment of fitness activities, providing frequent data tracking, positively impacting routines, fostering community connections, and considering the user's occupation are crucial in encouraging more exercise.

For the decision to change diet using the Gaussian Naive Bayes model, the key features are TrackDataFreq (1.8929), HealthImpact (0.9643), WellBeingImpact (0.8929), Gender (0.8929), and ExerciseFreq (0.8929). These results indicate that frequent tracking of data, emphasizing health and well-being impacts, considering gender differences, and encouraging regular exercise are significant factors in influencing dietary changes.

The decision to join a gym using the Random Forest model is primarily influenced by WellBeingImpact (0.1316), ExerciseFreq (0.0919), SleepImpact (0.0858), Occupation (0.0813), and Age (0.0713). This suggests that promoting the well-being benefits of gym membership, regular exercise, improved sleep, and targeting specific occupations and age groups can effectively drive gym membership.

Lastly, for the decision to change diet using the Logistic Regression model, the important features are TrackDataFreq (0.7748), ExerciseFreq (0.7074), Gender (0.6188), HealthImpact (0.3337), and WellBeingImpact (0.3251). These insights emphasize the importance of data tracking, regular exercise, considering gender-specific approaches, and highlighting health and well-being impacts in dietary decisions.

By understanding which features significantly influence fitness-related decisions, businesses can design more targeted marketing strategies, develop personalized fitness programs, and enhance user satisfaction and retention. For instance, promoting the enjoyment and routine impacts of exercise can encourage more people to exercise, while emphasizing the health benefits and data tracking features can influence dietary changes.
