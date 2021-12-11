# cosc329project - Job Skills Analysis

### Table of Contents 

<!--ts-->
* [Website](#Website)
* [Location](#Location)
* [List of Jobs](#List-of-Jobs)
* [NLP Library Function](#NLP-Library-Function)
* [Original Plan](#Original-Plan)
* [File Structure](#File-Structure)
* [Milestones](#Milestones)
* [Team Members](#Team-Members)
* [Final Presentation](#Final-Presentation)
* [Project Demo](#Project-Demo)
<!--te-->

## Website
- Indeed

## Location
- Canada

## List of Jobs

- Accounting
- Nurse
- Dentist
- Engineer
- Digital Marketing
- Cashier
- Maching learning
- sales associate (on process)
- 
- Computer Programmer
- Software Developer
- Database Administrator
- Computer Hardware Engineer
- Computer Systems Analyst
- Computer Network Architect(on process)

## NLP Library Function
- word_tokenize
  - Seperate words in sentences. Prepare for future process steps
- stopwords
  - Help remove words like "and" that does not help with analysis
- PorterStemmer
  - Keep the root of the word
  - Remove extra "s" and "ing" at the end of words
- FreqDist
  - Count the number of frequency the same thing appear
- wordnet
  - Generate a list of synonym for skills
- ngrams
  - Generate ngram for skills

## Original Plan
- Week 8: Plan out the steps involved and explore relevant APIs
- Week 9: Collect and cleaning data, define the skill
- Week 10: Identify 5+ NLP library functions to use, and extract skills from the job website
- Week 11: Cluster skills
- Week 12: Make video
- Week 13: Submit project video, vote on other's projects
- Week 14: Finalize project deliverables and submit the required deliverables

## File Structure
- webscrpaeplus
  - Scrap job description from website to csv
- combin
  - Combine scrapped data to a master csv
- draftofskill
  - Organize predetermined list of skills into ngrams
- findskill
  - Find synonyms for predetermined skills
  - Use the master csv to identify popular skills(cluster skill)

## Milestones

- Project Presentation
- Final Project Deliverables


## Team Members

- Ann(Jingyi) Ni: I am Ann, year 4 Management student.
- Hecheng(Gabrielcha) Chen: I am Gabrielcha. I am a year 4 student, majoring in Computer Science.


## Project Presentation

- [Click here](https://www.youtube.com/watch?v=AiazW9A_Xes)

## Project Demo
- [Click here](https://youtu.be/BSsczBQuiO0)
