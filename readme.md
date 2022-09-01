Hi all, 

In this session, I have got Demo using Azure Data Factory(ADF), Azure Functions and Azure Logic Apps. I am going to show you here Data driven workflow uisng thise three Azure Services. Also I am going to provide you quick overview about above three services so you can use them in your data driven solution.

ADF 
It is Cloud based Data integration Azure Service. It helps you to do Data Movements, Data Traformation,orchestration and  Automation of your pipeline or work flow with low code or no code .You can build your pipeline very quickly, very easily with cost effective .

Azure Function 
It is Azure Platform as Service, its small peace of code in Cloud. It is a Azure Integration Service.You can use it for do some calculation or task independently from your IOT solution, Data solution or App Solution. It can be reusable. It is cost effective.

Azure Logic Apps
Its Azure service for integration with your app, service, data and system. Its easily integration with them. It is no code or low code Azure Service.

ADF+AZure Function+ Azure Logic Apps work great todather!!!

Here, ADF for Pipeline creation, orchestration and automation.
      Azure Function to create menifest file or calling dynamic ADF child pipeline or resizing Image.
      Azure Logic Apps to create a customized Email functionality
      
      In below both example , Azure Logic Apps is used to send customized Email
Here is high level design for it 
In this example, ADF directly calling Azure Function using Azure Function Activity
![image](https://user-images.githubusercontent.com/64379307/187998004-85e5c757-ee6b-4c40-9170-382893d8738f.png)

Here is another Example
In this Example, ADF is not going to call Azure Fucntion Directly. However Azure Function trigger based on file arrives in Azure Blob Storage.
![image](https://user-images.githubusercontent.com/64379307/187998173-bc0f1fc1-25f6-44b5-baee-cab501a7aa6a.png)

