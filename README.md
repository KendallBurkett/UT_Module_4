# pandas-challenge
The purpose of this readme is for the grader. There are two jupyter notebooks in this repo.
The starter is the untouched file that came with the assignment.
the PyCitySchools_Homework_Copy is the copy that is gradeable. 

There were two things that I needed help with on this assignment.
    1. total budget... i was using .nunique().sum() to get the total when i should have just been using .unique().sum() - thanks chatGPT
    2. displaying the bins under Scores by School Spending #24-26. I could not get the bins to display and kept getting an error of TypeError: '<' not supported between instances of 'int' and 'str' 
        chat GPT corrected my formatting and gave me a line of code to help display the bins properly.
