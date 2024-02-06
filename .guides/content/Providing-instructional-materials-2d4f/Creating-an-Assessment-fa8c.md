### Commonly Used Assessments
---
Assessments can be accessed through the **Assessments** button at the top of the page. 

![Drop-down button with clipboard icon labeled 'Assessments'.](.guides/img/assessmentsButton.png)

### Your First Standard Code Test
---
Create the assessment in page 2, titled *"Adding a Code Window."*

*Note: The assessment you create should be placed after the directions, so highlight the corresponding line in the Guides Editor, then follow the steps below:*

![Markdown editor shown in left panel with placeholder shown at line 6. Guide shown in right panel.](.guides/img/cursorcodewindow.png)
#### Creating the Assessment

1. Click on the **Assessments** button and select **Standard Code Test**.

![Step 1) Select 'Assessments' button and select Standard Code Test from the drop-down options.](.guides/img/assessmentlibrarystandardcode.png)

2. Make sure **GENERAL** is selected.

3. Enter Assessment 1 in the NAME field.

4. Paste the following into the INSTRUCTIONS window:

```
Change the print statement to say "Hello Python!"
```

![Step 2) Select GENERAL tab. Step 3) Enter assessment name into NAME field. Step 4) Enter instructions for students into INSTRUCTIONS field.](.guides/img/generalAssessment.png)

5. Select the **EXECUTION** tab.

6. Copy and paste the following into the COMMAND field.

```
python3 test.py
```

![Step 5) Select EXECUTION tab. Step 6) Enter command to execute student code file into COMMAND field.](.guides/img/standardcodeexecution.png)

7. Select the **GRADING** tab.

8. Copy and paste the following into the EXPECTED OUTPUT window.
```
Hello Python!
```
9. Click the **SHOW ERROR FEEDBACK** toggle to ON.

10. In the ERROR FEEDBACK field enter the following:
```
Did you use the correct punctuation?
```

11. Click **CREATE**.
![Step 7) Select GRADING tab. Step 8) Add text to EXPECTED OUTPUT field. Step 9) Toggle on SHOW ERROR FEEDBACK. Step 10) Add text to SHOW ERROR FEEDBACK field. Step 11) Select CREATE button.](.guides/img/gradingAssessment.png)

12. When you go back to **Split view**, you will see the assessment in the Guides Editor on left and how it is rendered in the preview on the right.

![Markdown text and `Assessment 1` button on line 6 are emphasized in editor in left panel, and corresponding rendered assessment is emphasized in Guide in right panel.](.guides/img/renderedcodetest.png)

It is important to note that the `Check It!` button submits students' code for auto-grading. Students should submit only when their work is finalized and they feel confident it is correct. So how do they test out their code before submitting it for grading?

... with a `Try it!` button!

#### Creating the Try It! Button


The `Try it!` button is what students will use to check their code as they work, before submitting their finalized assignment.

13. Click above the assessment in the Guides Editor to create some space for the button. Select the clipboard to copy and paste:

```
{Try it!}(python3 test.py)
```

This is how it will look once rendered:

![Markdown text formatting of 'Try it' button is emphasized on line 9 of Guide in left panel, and corresponding rendered button is emphasized in Guide in right panel.](.guides/img/buttonrender.png)

#### Test It Out

Click the **Preview** eye icon to test out your Standard Code Test!

<table><tbody ><tr><td><details><summary>
Example of Correct Code
</summary><hr>
	
![Guide page after 'TRY IT' and 'Check It' buttons have been selected: below 'TRY IT' button is a field with a check mark, indicating successful execution, with the program output 'Hello Python!', and below 'Check It' is a field with a check mark and the text 'Check 1 passed'.](.guides/img/correctcode.png)
	
The `Try it!` button shows the output of the program and the `Check it` button shows that the code passed the auto-grader.
</details></td></tr></tbody>
</table>

<table><tbody ><tr><td><details><summary>
Example of Incorrect Code
</summary><hr>

![Guide page after 'TRY IT' and 'Check It' buttons have been selected: below 'TRY IT' button is a field with an 'x', indicating unsuccessful execution, with the relevant error message text, and below 'Check It' is a field with an 'x', the text 'Check 1 failed', the code file's current output, and the expected output.](.guides/img/incorrectcode.png)
	
The `Try it!` Button shows there was a syntax error in the program and the `Check it` button shows that the program failed the auto-grader.
	
</details></td></tr></tbody>
</table>




|||important
[**For more information on assessments, click here.**](https://docs.codio.com/instructors/authoring/assessments/add-assessment.html#add-assessment)
|||
