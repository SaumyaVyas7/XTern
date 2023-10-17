Artificial Intelligence Work Prompt
FoodX Background

One of the biggest aspects of the Xtern program is showing off our wonderful state and all it has to offer. Indiana is not only home to amazing sites and attractions, but also several local and unique dining options, like Food Trucks. TechPoint is excited to help amplify the Indiana Food Truck scene and will open our very own FoodX franchise and we need your help! In order to spread the Food Truck love, you will be asked to help develop the concept of amplifying the food truck scene in Indiana and helping to launch the franchise, FoodX. 

Your Task

In the next section, you will be given your corresponding responsibilities for the amplification of the Indiana Food Truck scene and/or the launch of the food truck franchise. Read each task carefully and ensure you submit your work by the deadline! 

Disclaimer: The above description is fictional.  The TechPoint team does not have an app or a food truck and is not using your work sample assessment to finalize features of it.  Any work completed will be used for the application to the Xtern internship.

Situation

Given the launch of our food truck line, FoodX, we will be running an exciting and interactive promotion on college campuses to attract a massive initial student following.  When placing their order on our fancy new FoodX app they input basic information about their college experience and we predict what they are going to order.  If we don’t get it right they get a 10% discount.

While the promotion has done a great job of bringing in business our staff has not been great at guessing orders and are not happy with the combined workload of guessing and cooking.

Because of this you have been asked to consider implications, solutions and deployment of a mechanism to automatically guess orders, sounds like the perfect job for AI!

Your Task

Dataset: 

Xtern 2024 Artificial Intelligence Data Set



(25%)  Given the data set, do a quick exploratory data analysis to get a feel for the distributions and biases of the data.  Report any visualizations and findings used and suggest any other impactful business use cases for that data.

=> 
### Based on the analysis, it appears that there is an even distribution of orders among 10 possible choices. However, when we look at the University, Major, Year, and Time columns, we notice significant variations in the amount of data. Some universities and majors have a lot of data, while others have very little. For instance, Butler University and IU students are frequent customers, while there's only one data point for Purdue University Students. With this information, FoodX could adapt its business strategy to focus on the universities that order from them the most, as they constitute the majority of their customer base. Most customers are in their 2nd or 3rd year, with 1st and 4th-year students making up a tiny portion. Moreover, the bulk of orders occur during lunchtime (11-14), with very few orders at other times. Consequently, FoodX could consider adjusting its operating hours to maximize profits during this peak period and closing during other times.

(30%) Consider implications of data collection, storage, and data biases you would consider relevant here considering Data Ethics, Business Outcomes, and Technical Implications

Discuss Ethical implications of these factors
Discuss Business outcome implications of these factors
Discuss Technical implications of these factors

=> 
### Ethical Considerations: It is crucial to address the ethical aspects of using this dataset. Without the explicit consent of the students, it would be unethical to utilize their data for profit and decision-making. FoodX should inform users that their data may be used for analysis and guiding business decisions, providing an opt-out option at any time. Additionally, stringent security measures should be in place to protect the data from potential breaches, and personal identifiers such as names and birthdays must be removed to ensure the legality and ethics of data usage.

### Business Implications: The success of data analysis and machine learning hinges on the quality and relevance of the data collected. Therefore, FoodX must ensure the data is meaningful, as poor-quality or irrelevant data can lead to ineffective results. Compliance with data collection and storage laws is also paramount, as any legal controversies could harm the company's public image.

### Technical Considerations: Efficient database systems managed by experts are necessary to store and facilitate quick access to the collected data. Robust security measures are imperative to safeguard customer information from potential breaches. Moreover, ongoing data analysis and machine learning model updates are needed to account for emerging trends and insights in the dataset.

(35%) Build a model to predict a customers order from their available information.  You will be graded largely on your intent and process when designing the model, performance is secondary. It is strongly suggested that you use SKLearn for this model as to not take too much time.  You may use any kind implementation you would like though, but it must be pickelable and have a “.predict()” method similar to SKLearn

Outline your process for model selection, training and testing. Including data preparation.
Design a function that prepares your data by loading the provided dataset and processes it into an appropriate machine readable format if necessary.
Design a function to train your model and pickle it.
Train and test your model.  Submit any training, testing and model selection visuals or metrics.
Upload your work to GitHub and link the repository, make sure it is public.
(10%) Given the work required to bring a solution like this to maturity and its performance, what considerations would you make to determine if this is a suitable course of action?


Resources

SKLearn: https://scikit-learn.org/stable/
SKLearn Model Saving and Loading: https://scikit-learn.org/stable/model_persistence.html
