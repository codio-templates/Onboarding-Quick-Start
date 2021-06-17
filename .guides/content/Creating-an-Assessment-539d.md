### Commonly Used Assessments
---
Assessments can be accessed through the chess piece icon. 

![.guides/img/chesspiece](.guides/img/chesspiece.png)

There are many types, but the most commonly used are below:

![.guides/img/commonassessments](.guides/img/commonassessments.png)

|||important
[**For more information on assessments, click here.**](https://docs.codio.com/instructors/authoring/assessments/add-assessment.html#add-assessment)
|||

### Your First Standard Code Test
---
Create the assessment in page 2, titled *"Adding a Code Window."*

#### Creating the Assessment
---
1. Click on the **Assessments dropdown menu** and select **Standard Code Test**.

![.guides/img/standardcode](.guides/img/standardcode.png)

2. Make sure **GENERAL** is selected.

3. Enter Assessment 1 in the **NAME** field.

4. Paste the following into the **Instructions** section:

`Change the print statement to say "Hello Python!"`
![.guides/img/generalAssessment](.guides/img/generalAssessment.png)

5. Select **EXECUTION** and type `python3 test.py` in the **COMMAND** field.

![.guides/img/newassess](.guides/img/newassess.png)

6. Select **GRADING**.

7. In the **EXPECTED OUTPUT** field enter `Hello Python!` 

8. Click the **SHOW ERROR FEEDBACK** toggle.

9. In the **ERROR FEEDBACK** field enter `Did you use the correct punctuation?` 

10. Click **SAVE**.
![.guides/img/gradingAssessment](.guides/img/gradingAssessment.png)

11. When you go back to **Split View**, you will see the assessment in the Guides Editor on left and how it is rendered in the preview on the right.

![.guides/img/renderedstandardcodetest](.guides/img/renderedstandardcodetest.png)

#### Creating the Try It! Button
---
It is important to note that the `Check It!` button submits students' code for auto-grading. Students should submit it when they feel confident it is correct. So how do they test out their code before submitting it for grading?

... with a `Try it!` button!

12. Click above the assessment in the Guides Editor to create some space for the button. Select the clipboard to copy and paste:

```
{Try it!}(python3 test.py)
```

This is how it will look once rendered:

![.guides/img/renderedbuttons](.guides/img/renderedbuttons.png)

#### Test It Out
---
Click the **Preview** eye icon to test out your Standard Code Test!

<table><tbody ><tr><td><details><summary>
Example of Correct Code
</summary><hr>
	
![.guides/img/correctcode](.guides/img/correctcode.png)
	
The `Try it!` button shows the output of the program and the `Check it` button shows that the code passed the auto-grader.
</details></td></tr></tbody>
</table>

<table><tbody ><tr><td><details><summary>
Example of Incorrect Code
</summary><hr>

![.guides/img/incorrect](.guides/img/incorrectcode.png)
	
The `Try it!` Button shows there was a syntax error in the program and the `Check it` button shows that the program failed the auto-grader.
	
</details></td></tr></tbody>
</table>
