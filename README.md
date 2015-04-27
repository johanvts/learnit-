# learnit-
Some userscripts for learnit.
Tested with tampermonkey for Chrome.

![screenshot](http://i.imgur.com/csCTEQ8.png)

# learnit_cmd.py
A python command line tool for working with learnit.

    $ python3 learnit_cmd.py
    email: 
    password: 
    Logging in...
    Hello Thomas Dybdahl Ahle!
    > help
    Supported commands:
       list courses
       list assignments [course_id]
       grade [assignment_id]
       exit
    > list courses
    You have 2 courses:
    0) 3003023: Algorithms and Data Structures (Spring 2015)
    > list assignments 3003023
    Found 9 assignments:
    41508: Connected Components Warmup
    41889: GiantBook
    42653: Random Queue
    43327: Congress
    43574: Runsort
    44343: Gorilla–Sea Cucumber Hash
    44705: Word Ladders
    44952: Spanning USA
    45103: Super Vector Mario!
    > grade 44952
    Loading table...
    Found 63 groups.
    group> A
    --------------------------------------------------
    Grade: Approved
    Feedback: Your input reading is slightly too complicated for anyone to know for sure whether it works. Other that that everything looks fine!
    Submission status: Submitted for grading
    Grading status: Graded
    Last modified: Friday, 24 April 2015, 08:12
    Comments:
    Files: 29767_Route66AAEN.java, 29767_Spanning_USA_AAEN.pdf
    Show files? [y/N]:
  