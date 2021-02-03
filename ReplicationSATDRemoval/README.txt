RQ1.csv
You find a line for each SATD effectivelly removed. 

For each SATD Removal we report the project name to which it belongs to; the file_path containing the SATD comment; the SATD comment body; the commit in which the SATD has been removed; the classification varying in: "Class Removal, Method Removal, Method Changed, Method Unchanged". 

RQ2.csv
You find a line for each SATD Removal for which the cosine similarity computed between the SATD comment body and the commit message is greater or equal to 0.3.

For each instance we report the project name to which it belongs to; the file_path containing the SATD comment; the SATD comment body after pre-processing; the commit in which the SATD has been removed; the commit message after pre-processing; the cosine similarity and finally the categorization obtained as results of the manual labeling (five-level Likert scale).

RQ3Quantitative.csv
You find an instance for each SATD Removal occurred changed the method attached to it. 

For each instance we report the project name;the file path containing the SATD Comment; the SATD comment body; the commit in which the SATD has been removed; and finally the type of changes done on the method attached to the comment that has been obtained by parsing the output of Gum Tree.

RQ3_qualitative_API.csv
You find an instance for each SATD Removal that involves changes in both external APIs imported and method calls.

For each instance we report the project to which it belongs to, the commit in which the SATD comment has been removed, the file path containing the SATD comment, a list of added APIs, a list of delete APIs, the relevance assigned with the manual labeling and the category obtained applying the card-sorting approach.

RQ3_qualitative_Conditionals.csv
You find an instance for each SATD Removal that involves changes in conditional statements.
Project;File_Path;SATD_Comment;Commit_Removal;Is_Conditional_Change_Related_To_SATD;Category
For each instance we report the project to which it belongs to; the file path containing the SATD comment; the SATD comment body; the commit in which the SATD comment has been removed; the relevance assigned with the manual labeling and the category obtained applying the card-sorting approach.