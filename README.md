# upgrad-car-dent-detection-system
# Problem Statement
The company wants to provide an effective pricing strategy for any listing of used cars. Earlier, this problem was solved by a manual inspection conducted by a representative, who would inspect every feature of a used car. This solution was effective, as the representative considered every factor affecting the resale value (especially the damage); however, this solution is not scalable, as the company is growing.

Using the millions of images of used cars the company has collected over the years, you must build an object-detection model that can detect the presence of any damage in cars. 

Among the various types of damage, the model should be able to detect two: scratches and dents. It should return “None” if no damage is detected. The product team will use these results to map the resale value of a car based on the type of damage detected.

Note: You have a large repository of images, where the count of each damage is almost equal. However, some of the images are not yet labelled.

You must create an ML system that has the features of a complete production stack, from experiment tracking to automated model deployment and monitoring. The framework should also be able to train if additional annotations are available later. 

The solution approach should be able to answer the following questions:
Q1. System design: Based on the above information, describe the KPI that the business should track. 

Q2. System design: Your company has decided to build an MLOps system. What advantages would you get from building an MLOps system rather than a simple model?

Q3. System design: You must create an ML system that has the features of a complete production stack, from experiment tracking to automated model deployment and monitoring. For this problem, create an ML system design (diagram) 
(Note: The MLOps tools you want to use are up to your judgement. You can use open-source tools, managed service tools or a hybrid. You can use draw.io or any other convenient tool to create the architecture.)

Q4. System design: After creating the architecture, please specify your reason for choosing the specific tools you chose for the use case. 

(Note: The MLOps tools you want to use are up to your judgement. You can use open-source tools, or managed service tools or a hybrid.)

Q5. Workflow of the solution: 
You must specify the steps that should be taken to build such a system end to end. 
The steps should mention the tools used in each of the components and how they are connected with one another to solve the problem.
Broadly the workflow should include the following:

Data and model experimentation
Automation of data pipeline
Automation of training pipeline
Automation of inference pipeline
Continuous monitoring pipeline
 

The workflow should also explain the actions to be taken under the following conditions:
After you deployed the model, you noticed that there was a sudden increase in the drift due to the poor lighting in the image taken.
1.What component/pipeline will be triggered if there is any drift detected? What if the drift detected is beyond an acceptable threshold?
2.What component/pipeline will be triggered if you have additional annotated data?
