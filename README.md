# pyspark-installation-guide

Installing PySpark involves the following steps:
1.	Install Java Development Kit (JDK) 8 or higher
2.	Download and install Apache Spark
3.	Configure PySpark on your system

Here is a step-by-step guide to install PySpark on your windows machine:
Step 1: Install Java Development Kit (JDK) 8 or higher PySpark requires Java Development Kit (JDK) version 8 or higher. If you do not have it already installed on your machine, follow the steps below to download and install it:
•	Go to the official Oracle JDK download page: https://www.oracle.com/java/technologies/downloads/
•	Select the version of JDK that corresponds to your operating system
 ![image](https://user-images.githubusercontent.com/25885092/225222501-89336840-c30b-4f84-924d-e00334d7389e.png)

•	Accept the license agreement and click on the download link
•	Once the download is complete, double-click on the downloaded file to start the installation process
•	Follow the prompts to complete the installation
•	Verify your installation:
 ![image](https://user-images.githubusercontent.com/25885092/225222531-daf8927c-059e-4880-b1e2-7049f4beb85f.png)

 
Step 2: Download and install Apache Spark The next step is to download and install Apache Spark. Follow these steps:
•	Go to the official Apache Spark download page: https://spark.apache.org/downloads.html
•	Select the latest version of Spark
 ![image](https://user-images.githubusercontent.com/25885092/225222561-65384e77-ebad-4520-b34f-e2382c1e77ba.png)

•	Choose the package type that corresponds to your operating system and the version of Hadoop you have installed (if applicable)
•	Click on the download link to begin the download
•	Once the download is complete, extract the contents of the archive to a directory of your choice
 ![image](https://user-images.githubusercontent.com/25885092/225222591-feda1441-ab1c-46e5-82ed-0b6322ea3a46.png)

•	Download Hadoop winutils.exe
 https://github.com/steveloughran/winutils/blob/master/hadoop-2.6.0/bin/winutils.exe
 ![image](https://user-images.githubusercontent.com/25885092/225222613-20a54c9d-03d6-4450-8af3-b64a567ce2f5.png)

•	Once the download is complete, put the file to the directory of your choice
 ![image](https://user-images.githubusercontent.com/25885092/225222651-3ac8cc31-d255-4e61-b845-035213824345.png)


Step 3: Configure PySpark on your system The final step is to configure PySpark on your machine. Here are the steps:
•	Open your system environment variables
 ![image](https://user-images.githubusercontent.com/25885092/225222684-2c6d2998-6c01-43e4-ba33-a6bfba2ea43a.png)
 ![image](https://user-images.githubusercontent.com/25885092/225222748-f5d512f2-fb30-491f-9b32-b950afd7efc8.png)
 
•	Setup environment variable SPARK_HOME with your spark file directory “C:\BigDataLocalSetup\spark”
 ![image](https://user-images.githubusercontent.com/25885092/225222779-843ffb1a-b7da-4652-ab1d-a64fa56fbcbb.png)

•	Set the variable HADOOP_HOME for directory “C:\BigDataLocalSetup\hadoop” too and click ok.
 ![image](https://user-images.githubusercontent.com/25885092/225222802-84cb270b-d566-420c-9e57-5e66e0c94c63.png)

•	Next, open the Path variable
  ![image](https://user-images.githubusercontent.com/25885092/225222836-078b8474-043e-4ebe-a6ea-2fe065d16dec.png)

•	Add two variable below “%SPARK_HOME%\bin” and “%HADOOP_HOME%\bin” then click ok.
 ![image](https://user-images.githubusercontent.com/25885092/225222867-5f615ebc-2955-42be-9a50-f6a02e5a9259.png)

•	Then open cmd promt and run prompt : “spark --shell”
 ![image](https://user-images.githubusercontent.com/25885092/225222899-d0e6acf4-42aa-40fb-af0f-df3a2e3124e2.png)

•	Or simply check the version:
 ![image](https://user-images.githubusercontent.com/25885092/225222919-d6c288ff-7504-478c-b612-2289fd12e31f.png)

•	This will print the version of PySpark you have installed. And that means your pyspark is ready to use.

END
