# Building-a-regression-model-to-predict-automobile-prices-using-Azure-Machine-Learning-Designer
Agenda:

1.Create an Azure Machine Learning workspace

2.Set up compute clusters for model training

3.Explore and transform the dataset for optimal results

4.Train a regression model to predict automobile prices

5.Evaluate the model's performance using key metrics

6.Create an inference pipeline for real-time price prediction

7.Deploy the trained model as a web service using Azure Container Instance

Important links:

https://learn.microsoft.com/en-us/azure/machine-learning/how-to-troubleshoot-online-endpoints?view=azureml-api-2&tabs=cli

https://archive.ics.uci.edu/dataset/10/automobile?darkschemeovr=1

https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-designer-automobile-price-train-score?view=azureml-api-1

Process:

1.Create a Resource group-Create an Azure Machine Learning workspace and launch studio

2.go to Manage-compute-compute clusters-new

![image](https://github.com/user-attachments/assets/8e7e23e3-6152-4e9e-b5fd-9f485c545feb)

![image](https://github.com/user-attachments/assets/bd695ffd-1a2c-42db-b956-1b30bdf11568)

3.Go to Authoring-Designer-create a new pipeline-component

![image](https://github.com/user-attachments/assets/5816f5bd-7876-4b77-915c-a3fabaff1839)

4.Drag the result to the working area-right click and check preview is required.

5.search for select columns in Dataset-Drag the result to the working area and double click on that Dataset-Edit column

![image](https://github.com/user-attachments/assets/9f3fab92-fbf8-4a81-be6a-42f1a4efb2e5)

remove the columns which you feel are not required

![image](https://github.com/user-attachments/assets/575372db-897a-4483-a8e5-f383a0a039b3)

6.lly search for clean missing data,Normalize data

![image](https://github.com/user-attachments/assets/47a45f71-0b9b-4abd-9bfb-f605850ee47a)

7.double click on missing data -edit column

![image](https://github.com/user-attachments/assets/39a49699-ddb2-4f95-84b0-46ea4ffad79d)

8.remove the column is there is missing data present in these 3 columns

![image](https://github.com/user-attachments/assets/86999f18-a9e6-4922-be97-c48f56269905)

9.For normalizing the data

![image](https://github.com/user-attachments/assets/df11f95c-6bb4-44e2-baa3-4927872bf521)


![image](https://github.com/user-attachments/assets/6f18bfc3-4d72-4c62-b691-5c85d97314d2)

10.click on Configure and submit

![image](https://github.com/user-attachments/assets/d8899854-bae9-47c0-9012-eb8e38fb1e1c)

![image](https://github.com/user-attachments/assets/53d51bb4-52bc-4473-b7cc-d6449cb4ccc0)

11.split the data because some data need to be kept for testing purpose

![image](https://github.com/user-attachments/assets/47ca0a3b-563c-4947-bbb0-571c79084443)

![image](https://github.com/user-attachments/assets/e1017192-b45f-4576-b3a8-2a6d0d3aa297)

12.In train model-edit column

![image](https://github.com/user-attachments/assets/87049a78-cca0-40c2-b9df-80c8a6bf18b1)

13.Configure &Submit-select existing-submit

![image](https://github.com/user-attachments/assets/5f0d72fb-3ea2-4522-9865-8dcaf2ee0e18)

14.

![image](https://github.com/user-attachments/assets/41d5e71d-754c-4db5-89cb-083316e60b20)

15.since we have tested it with our input data,now test it with entering manual data

![image](https://github.com/user-attachments/assets/7f03754f-5ed0-468f-97e9-c9712a84687a)

16.Remove price if included

![image](https://github.com/user-attachments/assets/7b2833ce-6e64-43ba-b3b2-d40cb9228423)

17.Remove evaluate model and add python code model

![image](https://github.com/user-attachments/assets/ff440564-360e-43bd-84f0-50bdbdea4463)

![image](https://github.com/user-attachments/assets/8ffd3214-1638-4edf-9dee-9a8556d0eda1)

18.Deploy the model

![image](https://github.com/user-attachments/assets/4bd7070c-0e33-4d7f-8b8f-e1e2e6581507)

19.Click on End-points and give any input and click on test you can see the results.























































