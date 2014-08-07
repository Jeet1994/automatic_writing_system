<b>Foreword:-</b>

•	There are two types of user in this system namely Admin & Writer

•	The System needs to be developed in PHP (Code-Ignitor Framework) + MySQL + JQuery + Ajax +Plugins + APIs

•	At no part of the process should the Admin or Writer be redirected to an external link.

•	Use Google API for Plagiarism Search.



<b><u>Functional Requirement Stepwise:-</u></b>

1.	An admin has a panel where Admin can enter a pool of keywords/small phrases/long phrases/hint text along with their category (to be set by Admin).
 
2.	These categorized pool of Topics are displayed to all the writers in a particular category.

3.	Writers can book a topic of their choice by clicking on “I will write” button next to the name of the topics. If a writer books a topic, that topic is no longer visible to others.

4.	A writer can write 3 topics at a time. Example:- If the writer has already 2 topics pending to write, then he should be able to choose just 1 more topic.

5.	A writer has 2 days to write an essay on the topic. If the writer fails to write within 2 days, the Topic returns to the pool where it is visible to others.

6.	If a writer decides to write on a topic, then it goes on to the next page where a simple Text box and WYSIWYG Editor opens up. The writer can write the Essay in the WYSIWYG editor and write a suitable Heading for the essay in the Text box.  This page has 2 buttons:- Check & Save as Draft.

7.	The writer can save his unfinished work by click on   “Save as Draft” button.

8.	Once the writer feels that the writing is complete, they can click on “Check” Button to check their content.

9.	The Check button checks the following things in the content:-

    •	The Essay should be more than 500 words.
    •	The original keyword/phrase is repeated X times by the writer in the Essay (the X is pre-set by the Admin)
    •	Check the Grammar & Spelling errors in the Essay.
    •	Check the Essay for originality/plagiarism. Y % originality is considered safe. (The Y % is pre-set by the Admin)

10. If the Essay passes all the checks then it is submitted at the Admin side along with the Writer Name, Keyword/Phrase, Heading & Essay. If Essay fails at any of the Checks, it returns to the writer showing the Errors to be rectified or lines in the Essay which has suspected plagiarism. 
