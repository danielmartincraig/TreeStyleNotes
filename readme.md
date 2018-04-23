    "For some years I have been successfully using the following rule of thumb for scheduling a software task:
        ⅓ planning
        ⅙ coding
        ¼ component test and early system test
        ¼ system test, all components in hand."
        
    Frederick P. Brooks, Jr.


Tree Style Notes
----------------------

This project is live at www.danielmartincraig.net

Tree Style Notes is a web app designed to allow you to take notes that have child notes.

Current Stories:
----

*I want to use Postgres to store app data*

| Task                                        | Notes                                                                            | Time Estimate | Time Remaining |
| --------------------------------------------| ---------------------------------------------------------------------------------| --------------| ---------------|
| Investigate how to use Postgres with Spring | This will include investigating how to write database schema for use with Spring | 1 Hr.         | 1 Hr.          |
| Write database schema                       |                                                                                  | 1 Hr.         | 1 Hr.          |
| Investigate AWS DB options                  | Is a database in memory a good enough solution?                                  | 1 Hr.         | 1 Hr.          |
| Create/manage DB credentials                |                                                                                  | 1 Hr.         | 1 Hr.          |
| Stand up DB                                 |                                                                                  | 3 Hrs.        | 3 Hrs.         |
| Create PL methods for creating/deleting notes and adding/removing custom colors |                                              | 5 Hrs.        | 5 Hrs.         |
| Decide whether to front DB with an API      |                                                                                  | 2 Hrs.        | 2 Hrs.         |
| Test the PL methods by creating/deleting notes and colors |                                                                    | 2 Hrs.        | 2 Hrs.         |
| Defect Bucket                               |                                                                                  | 8 Hrs.        | 8 Hrs.         |
 
*I want to use Spring Boot and Thymeleaf to form and serve the page content* 

| Task                                             | Notes                                              | Time Estimate | Time Remaining |
| -------------------------------------------------| ---------------------------------------------------| --------------| ---------------|
| Write Node Class                                 |                                                    |               |                |
| Write Color Class                                |                                                    |               |                |
| Learn About Spring                               |                                                    |               |                |
| Learn About Thymeleaf                            |                                                    |               |                |
| learn to form DB calls                           | Learn to perform reads and writes programmatically |               |                |
| Create UI Methods                                |                                                    |               |                |
| Learn to integrate UI elements w/ backend stuff  | Perhaps with listeners?                            |               |                | 
| Learn about TL foreach, other control structures |                                                    |               |                |
| Write TL templates                               |                                                    |               |                |


| Task | Notes | Time Estimate | Time Remaining |
| -----| ------| --------------| ---------------|
||||


*I want to use CSS to style my page* 

[![Build Status](https://travis-ci.org/danielmartincraig/TreeStyleNotes.svg?branch=master)](https://travis-ci.org/danielmartincraig/TreeStyleNotes)
