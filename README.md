# **Data Processing in Shell**<br/>by **Susan Sun**

Live training sessions are designed to mimic the flow of how a real data scientist would address a problem or a task. As such, a session needs to have some “narrative” where learners are achieving stated learning objectives in the form of a real-life data science task or project. For example, a data visualization live session could be around analyzing a dataset and creating a report with a specific business objective in mind _(ex: analyzing and visualizing churn)_, a data cleaning live session could be about preparing a dataset for analysis etc ... 

As part of the 'Live training Spec' process, you will need to complete the following tasks:

Edit this README by filling in the information for steps 1 - 4.


## Step 1: Foundations 

This part of the 'Live training Spec' process is designed to help guide you through session design by having you think through several key questions. Please make sure to delete the examples provided here for you.

### A. What problem(s) will students learn how to solve? (minimum of 5 problems)
- How to download single file and multiple files using `wget` and `curl`.
- How to convert, preview, filter, and manipulate data files using `csvkit` library commands.
- How to perform database operations via the commandline using `csvkit` library commands.
- How to chain commands together using operators
- How to install Python libraries using `pip` and execute Python scripts via the command line.

### B. What technologies, packages, or functions will students use? Please be exhaustive.
- `wget`
- `curl`
- `csvkit` library
- `pip`

### C. What terms or jargon will you define?

_Whether during your opening and closing talk or your live training, you might have to define some terms and jargon to walk students through a problem you’re solving. Intuitive explanations using analogies are encouraged._

- Documentation manuals
- Option flags
- Multi-file processing
- ETL: extract, transform, load
- Database operations
- Package manager (`pip`)
- Version control 

### D. What mistakes or misconceptions do you expect? 

- Depending on the students' operating system, the installation will look different when they take the notebook course content and apply it locally on their machines.  This can be alleviated by specifically speending time in the course to call out how each OS will handle the installations differently.

- Students with less grounding in command line basics might be confused by how the course content is taught inside a notebook.  Extra time spent on disambiguating this and showing screenshots of what the content will look like on a Terminal will be helpful.

### E. What datasets will you use? 

- Spotify music attributes dataset. Similar to the data used in [Data Processing in Shell](https://learn.datacamp.com/courses/data-processing-in-shell).


## Step 2: Who is this session for?

Terms like "beginner" and "expert" mean different things to different people, so we use personas to help instructors clarify a live training's audience. When designing a specific live training, instructors should explain how it will or won't help these people, and what extra skills or prerequisite knowledge they are assuming their students have above and beyond what's included in the persona.

- [ ] Please select the roles and industries that align with your live training. 
- [ ] Include an explanation describing your reasoning and any other relevant information. 

### What roles would this live training be suitable for?

*Check all that apply.*

- [ ] Data Consumer
- [ ] Leader 
- [x] Data Analyst
- [x] Citizen Data Scientist
- [x] Data Scientist
- [x] Data Engineer
- [ ] Database Administrator
- [x] Statistician
- [x] Machine Learning Scientist
- [x] Programmer
- [ ] Other (please describe)

### What industries would this apply to?

Across all industries that requires product data analysts and scientists.  

### What level of expertise should learners have before beginning the live training?

*List three or more examples of skills that you expect learners to have before beginning the live training*

- Can write a basic SELECT SQL query.
- Can do basic EDA in Python and understand why this needs to be done and can interpret summary statistics output.
- Has done data analysis from beginning to end (e.g. from extracting the data to cleaning data to analyzing and summarizing results)
- Has very basic understanding of command line (e.g. can open terminal, do file navigation, print log)


## Step 3: Prerequisites

List any prerequisite courses you think your live training could use from. This could be the live session’s companion course or a course you think students should take before the session. Prerequisites act as a guiding principle for your session and will set the topic framework, but you do not have to limit yourself in the live session to the syntax used in the prerequisite courses.

- [Introduction to Shell](https://learn.datacamp.com/courses/introduction-to-shell)
- [Intermediate Python for Data Science](https://learn.datacamp.com/courses/intermediate-python-for-data-science)
- [Introduction to SQL](https://learn.datacamp.com/courses/introduction-to-sql)


## Step 4: Session Outline

A live training session usually begins with an introductory presentation, followed by the live training itself, and an ending presentation. Your live session is expected to be around 2h30m-3h long (including Q&A) with a hard-limit at 3h30m. You can check out our live training content guidelines [here](_LINK_). 

### Introduction Slides
- Introduction to the webinar and instructor (led by DataCamp TA)
- Introduction to the topics
  - Why use command line for data processing
  - Go over session outline
  - Set expectations about Q&A

### Live Training
#### 1. Downloading data
- Command Line 101: File navigation, manuals, option flags, interpreting output
- Download a single file 
- Download multiple files
  - via file names
  - via wildcards
  - via a saved list
- Q&A & break
#### 2. Exploratory Data Analysis 
- Introducing the `csvkit` library
- Unzip data
- Extract data 
- Preview data
- Filter and subset data
- Q&A & break
#### 3. Database Operations 
- Database 101: What is a database? Basic SQL queries review.
- Extract data from database 
- Store SQL query as shell variable
- Command line operators and linking commands
- Pushing data back to database 
- Q&A & break
#### 4. Python on the Command Line
- Python 101: running .py files
- `pip` and installing dependencies
- Bringing everything together to create a mini data pipeline.
- Q&A & break

### Ending slides
- Recap of what we learned
- The data science mindset
- Call to action and course recommendations



## Authoring your session

To get yourself started with setting up your live session, follow the steps below:

1. Download and install the "Open in Colabs" extension from [here](https://chrome.google.com/webstore/detail/open-in-colab/iogfkhleblhcpcekbiedikdehleodpjo?hl=en). This will let you take any jupyter notebook you see in a GitHub repository and open it as a **temporary** Colabs link.
2. Upload your dataset(s) to the `data` folder.
3. Upload your images, gifs, or any other assets you want to use in the notebook in the `assets` folder.
4. Check out the notebooks templates in the `notebooks` folder, and keep the template you want for your session while deleting all remaining ones.

You can author and save your progress on your notebook using **either** of these methods.

_**How to author your notebook: By directly saving into GitHub**_

1. Preview your desired notebook, press on "Open in Colabs" extension - and start developing your content in colabs _(which will act as the solution code to the session)_.  :warning: **Important** :warning: Your progress will **not** be saved on Google Colabs since it's a temporary link. To save your progress, make sure to press on `File`, `Save a copy in GitHub` and follow remaining prompts.
2. Once your notebooks is ready to go, give it the name `session_name_solution.ipynb` create an empty version of the Notebook to be filled out by you and learners during the session, end the file name with `session_name.ipynb`. 
3. Create Colabs links for both sessions and save them in notebooks :tada: 

_**How to author your notebook: By uploading notebook into GitHub**_

1. Preview your desired notebook, press on "Open in Colabs" extension - and start developing your content in colabs _(which will act as the solution code to the session)_.  Once you're done, press on `file` - `download .ipynb` file - and overwrite the notebook by uploading it into GitHub. 
2. Once your notebooks is ready to go, give it the name `session_name_solution.ipynb` create an empty version of the Notebook to be filled out by you and learners during the session, end the file name with `session_name.ipynb`. 
3. Create Colabs links for both sessions and save them in notebooks :tada: 


You can check out either of those methods in action using this [recording](https://www.loom.com/share/1eeb148129244edd93fbc34bf5dc7f0d).
