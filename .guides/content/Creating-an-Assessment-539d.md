### Commonly Used Assessments
---
Assessments can be accessed through the **Assessments** button at the top of the page. 

![Assessment icon](.guides/img/assessmentsButton.png)

### Your First Standard Code Test
---
Create the assessment in page 2, titled *"Adding a Code Window."*

*Note: The assessment you create should be placed after the directions, so highlight the corresponding line in the Guides Editor, then follow the steps below:*

![.guides/img/cursorcodewindow](.guides/img/cursorcodewindow.png)
#### Creating the Assessment

1. Click on the **Assessments** button and select **Standard Code Test**.

![Assessment dropdown to standard code test](.guides/img/assessmentlibrarystandardcode.png)

2. Make sure **GENERAL** is selected.

3. Enter Assessment 1 in the NAME field.

4. Paste the following into the INSTRUCTIONS window:

```
Change the print statement to say "Hello Python!"
```

![Standard code test_General](.guides/img/generalAssessment.png)

5. Select the **EXECUTION** tab.

6. Copy and paste the following into the COMMAND field.

```
python3 test.py
```

![Standard code test_Execution](.guides/img/standardcodeexecution.png)

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
![Standard code test_Grading](.guides/img/gradingAssessment.png)

12. When you go back to **Split view**, you will see the assessment in the Guides Editor on left and how it is rendered in the preview on the right.

![Rendered standard code test](.guides/img/renderedcodetest.png)

It is important to note that the `Check It!` button submits students' code for auto-grading. Students should submit only when their work is finalized and they feel confident it is correct. So how do they test out their code before submitting it for grading?

... with a `Try it!` button!

#### Creating the Try It! Button


The `Try it!` button is what students will use to check their code as they work, before submitting their finalized assignment.

13. Click above the assessment in the Guides Editor to create some space for the button. Select the clipboard to copy and paste:

```
{Try it!}(python3 test.py)
```

This is how it will look once rendered:

![Rendered try it button and standard code test](.guides/img/buttonrender.png)

#### Test It Out

Click the **Preview** eye icon to test out your Standard Code Test!

<table><tbody ><tr><td><details><summary>
Example of Correct Code
</summary><hr>
	
![Correct code example](.guides/img/correctcode.png)
	
The `Try it!` button shows the output of the program and the `Check it` button shows that the code passed the auto-grader.
</details></td></tr></tbody>
</table>

<table><tbody ><tr><td><details><summary>
Example of Incorrect Code
</summary><hr>

![Incorrect code example](.guides/img/incorrectcode.png)
	
The `Try it!` Button shows there was a syntax error in the program and the `Check it` button shows that the program failed the auto-grader.
	
</details></td></tr></tbody>
</table>




|||important
[**For more information on assessments, click here.**](https://docs.codio.com/instructors/authoring/assessments/add-assessment.html#add-assessment)
|||
