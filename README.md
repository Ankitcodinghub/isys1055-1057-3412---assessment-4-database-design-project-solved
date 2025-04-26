# isys1055-1057-3412---assessment-4-database-design-project-solved
**TO GET THIS SOLUTION VISIT:** [ISYS1055-1057-3412 – Assessment 4: Database Design Project Solved](https://www.ankitcodinghub.com/product/isys1055-1057-3412-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;107169&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISYS1055-1057-3412 - Assessment 4: Database Design Project  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
ISYS1055/1057/3412 Database Concepts

You are required to investigate and understand a publicly available dataset, design a conceptual model for storing the dataset in a relational database, build the database according to your design and host the data, and develop SQL queries in response to a set of requirements.

The objective of this assignment is to reinforce what you have learned in the whole course. Specifically, it involves how to build a simple application that connects to a database backend, running a simple relational schema.

• Part A: Part A: Understanding the Data (0 Marks, Preliminary Work)

• Part B: Designing the Database (10%)

• Part C: Creating the Database (10%)

• Part D: Data Retrieval (15%)

Assessment criteria

This assessment will measure your ability to:

• Analyse the requirements outlined in the problem description

• Develop a conceptual model to assist you with the design of the database backend required for the system

• Use an industry-standard ER modelling tool to draw the ER model

• Use 7-step mapping process to create relational database schema

• Use normalisation process to evaluate the schema and make sure that all the relations are at least 3NF

Page 1 of 7

• Create tables on SQLite Studio and populate them with data available from the sources outlined above

• Write SQL statements required for CRUD (create, read, update, and delete) operations on the database you built

Course learning outcomes

This assessment is relevant to the following course learning outcomes:

CLO1 Describe various data modelling and database system technologies.

CLO2 Explain the main concepts for data modelling and characteristics of database systems.

CLO3 Identify issues with, compare and justify relational database designs using the functional dependency concepts.

CLO4 Apply SQL as a programming language to define database schemas and update database contents.

Page 2 of 7

Assessment details

Part A: Understanding the Data

In this assignment, we are working with the publicly available dataset: A Global Database of COVID19 Vaccinations. Further details about this dataset are available in the article available through the following URL: https://www.nature.com/articles/s41562-021-01122-8. The abstract of the article is as follows.

A live version of the vaccination dataset and documentation are available in a public GitHub repository at https://github.com/owid/covid-19-data/tree/master/public/data/vaccinations. These data can be downloaded in CSV and JSON formats.

FILE NAME DESCRIPTION

1 locations.csv Country names and the type of vaccines administered. Each line represents the last observation in a specific country. Refer to README.md for the details.

2 us_state_vaccinations.csv History of observations for various locations in the US.

3 vaccinations-by-age-group.csv History of observations for vaccinations of various age groups in each country.

4 vaccinations-bymanufacturer.csv History of observations for various types of vaccines used in each country.

Refer to README.md for the details.

6 country_data/Australia.csv Daily observations of vaccination in Australia.

7 country_data/United States.csv Daily observations of vaccination in the US.

8 country_data/France.csv Daily observations of vaccination in France.

9 country_data/Israel.csv Daily observations of vaccination in Israel.

Table 1: List of data files

To complete the tasks in the following sections, you are required to review and analyse the dataset that is available in the named files.

Part B: Designing the Database (10%)

Task B.1 Produce an ER diagram for a relational database that will be able store the given dataset.

It is important to note that the given CSV files are not necessarily representing a good design for a relational database. It is your task to design a database that will adhere to good design principles that were taught throughout the course.

The ER diagram must be produced by Lucidchart similar to the exercises that were completed in class. UML notation is expected and using other notations will not be acceptable. For downloading a high-quality version of your models from Lucidchart, use the Export function.

To complete this part, you are also required to transform the ER diagram into a database schema that will be used in the next part of the assignment.

The expected outcome of completing this task is an ER diagram, a reasonable set of assumptions, and a database schema. The answers to this part must be saved as one PDF file named design.pdf.

Part C: Creating the Database (10%)

Task C.1 Produce one SQL script file named database.sql. This script file requires all the SQL statements necessary to create all the database relations and their corresponding integrity constraints as per your proposed design. The script file must run without any errors in SQLite Studio. Note that this script is not supposed to store any data into the relations.

The expected outcome of completing this task is one script file with the specific name of database.sql.

Your script file needs to contain SQL comments to clearly separate scripts from each other and note the question number each one is related to.

Task C.2 Create a database file named Vaccinations.db. Import the given dataset into your database.

To complete this task, you will need to change the format of the CSV files to match the attributes of your designed database. You can use a spreadsheet editor such as Microsoft Excel.

The next step is to import the spreadsheets into the database you create in SQLite Studio. To complete this task, use the menu option Tools – Import in SQLite.

The expected outcome of completing this task is one database file named Vaccinations.db, which must contain all the data that is stored in the CSV files named in Table 1.

Part D: Data Retrieval (15%)

The following queries are to be supported. Each one of the queries below must be one SQL statement. It is acceptable to use several nested queries, combine several SELECT statements with various operators etc. However, it is not acceptable to have multiple and separated queries for each task.

The expected outcome of completing this task is as follows.

1. One SQL script file named Queries.sql containing all the queries developed for the tasks in this section. It is important that you add comment lines to separate the queries and indicate which task they belong to. Note that valid SQL comments must not generate errors in SQLite Studio. The marker of your work will use this file to execute and test your queries against your database.

1. A PDF file named QueryResults.pdf containing the query for each of the following tasks together with a snapshot of the first 10 results of your query. The snapshot must also show the total number of results retrieved by the query. A sample snapshot is provided below for your reference.

Figure 2: Column Headers in the Result Set for Task D.1

Task D.2 Produces a result set containing cumulative number of COVID-19 doses administered by each country. That is, the name of each country and the cumulative number of doses administered in that country. Each column in the expected result set will have the following structure.

Country Cumulative Doses

Figure 3: Column Headers in the Result Set for Task D.2

Task D.3 Produce a list of all countries with the type of vaccines (e.g., Oxford/AstraZeneca, Pfizer/BioNTech) administered in each country. For a country that has administered several types of vaccine, the result set is required to show several tuples reporting each type of vaccine in a separate tuple.

Country Vaccine Type

Figure 4: Column Headers in the Result Set for Task D.3

Task D.4 There are different sources of data used to produce the data set. Produce a report showing the total number of vaccines administered according to each data source. Order the result set by the total number of administered vaccines.

Source Name Total Administered Vaccines Source URL

Figure 5: Column Headers in the Result Set for Task D.4

Figure 6: Column Headers in the Result Set for Task D.5

Submission Format

You are required to submit the files with the exact names as below.

1. Design.pdf

2. Database.sql

3. Vaccinations.db

4. Queries.sql

5. QueryResults.pdf

In the previous sections of the assignment, the expected content of each of the files is explained in detail.

Referencing guidelines

Use RMIT Harvard referencing style for this assessment.

You must acknowledge all the courses of information you have used in your assessments.

Refer to the RMIT Easy Cite referencing tool to see examples and tips on how to reference in the appropriated style. You can also refer to the library referencing page for more tools such as EndNote, referencing tutorials and referencing guides for printing.

You should take extreme care that you have:

• Acknowledged words, data, diagrams, models, frameworks and/or ideas of others you have quoted (i.e., directly copied), summarised, paraphrased, discussed, or mentioned in your assessment through the appropriate referencing methods.

• Provided a reference list of the publication details so your reader can locate the source if necessary. This includes material taken from Internet sites.

• Failure to properly document a source

• Collusion between students

Assessment declaration

When you submit work electronically, you agree to the assessment declaration.
