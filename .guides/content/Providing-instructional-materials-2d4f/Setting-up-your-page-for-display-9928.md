## Types of Pages

| Type of Page | Description |
| :------ | :----------- | 
|**1 panel** ![One panel view: the Guide, with rendered text and a "next" button under it.](.guides/img/onepanel.png)| This page has only one panel. There is no need for a code window or terminal. |
|**2 panels** ![Two panel view. Left panel, Panel 0, labeled "Code Window" is a view of a code file, test.py. Right panel, Panel 1, labeled "Guide" shows the Guide's rendered text and "next" button.](.guides/img/twopanel.png) | This page has two panels: the code window and the Guide. |
|**3 panels** ![Three panels view. Top left panel, Panel 0, labeled "Code Window" is a view of a code file, test.py. Bottom left panel, Panel 1, labeled "Terminal" displays a terminal tab. Right panel, Panel 2, labeled "Guide" shows the Guide's rendered text and "next" button.](.guides/img/threepanel.png) | This page has three panels: the code window, the terminal and the Guide.|

## Creating a Page with 2 Panels

Follow the steps below to create a page with a code window:

1. Click the **index** icon to see the **Page List**. Click into Page 2. 

2. Highlight **Page 2** and rename it “Adding a Code Window.”

3. Add some text to your Guide. Click the clipboard to copy the text below. Paste into your page.

```
### Code Window
---

Directions/instructions on what students should do in the code window would go here.

```
4. Select the **Layout** button in the right hand corner. 

![Button with grid icon and the text 'Layout'.](.guides/img/layoutbutton.png)

5. Select **2 Panels** from the LAYOUT menu.

![The text '2 Panels' displayed in the field under LAYOUT.](.guides/img/layout2panel.png)

6. Toggle the **Close Tabs** button ON (this will generate the Close Terminal Session button, which we want ON). 

![Below the CLOSE TABS text, the Toggle is on, highlighted green with a check mark.](.guides/img/layoutCloseTabs.png)

7. Drag over the `test.py` file into the space under the **ADD TAB** button. Make sure the location of the panel is 0. 

8. **Save and Close** settings.

![Step 4) Select 'Layout' button. Step 5) In the LAYOUT field, select '2 Panels'. Step 6) Toggle on CLOSE TABS. Step 7) Click and drag the test.py code file from the file tree into the empty field under 'Open Tabs'. Step 8) Select the SAVE AND CLOSE SETTINGS button.](.guides/img/addcodewind2.png)

9. Now, when you click **Preview**, you should see two panels: the code window and the Guide! 

![In the left panel, the test.py code file is open. In the right panel is the Guide text.](.guides/img/layout2panelPreview.png)

## Creating a Page with 3 Panels

Follow the steps below to create a page with a code window and a terminal:

10. In **Edit** mode, click the **index** icon to see the **Page List.** Select the "Add Page" button to add your third page.

11. Highlight **New Page** and rename it “Adding a Terminal.”

![Step 10) Select 'Toggle sections list' button. Step 11) Highlight the New Page text, and replace it with 'Adding a Terminal'.](.guides/img/addNewPage.png)

12. Add some text to our Guide. Click the clipboard to copy the text below. Paste into your page.

```
Terminal 
---

The terminal allows us to work with code that requires input. 
```

13. Click the **Layout** icon at the top of the Guide Editor window. 

14. Select **3 panels** from the LAYOUT drop-down menu

15. Toggle the **Close Tabs** button ON. 

16. First, add the code window. Drag over the file `test2.py` into the space under `Open Tabs`. Make sure the location of the panel is 0. 

![Step 13) Select 'Layout' button. Step 14) In the LAYOUT field, select '3 Panels'. Step 15) Toggle on CLOSE TABS. Step 16) Click and drag the test2.py code file from the file tree into the empty field under 'Open Tabs'. ](.guides/img/addterminal1.png)

17. Now, add the terminal. Click the **ADD TAB** button and specify that the TYPE is **Terminal.** Make sure the location of the panel is 1. 

![Step 17) Select ADD TAB button. Select drop-down menu under type; select 'Terminal'. Optional: Add a command to run when the terminal opens in the COMMAND text field. Optional: Add a value to the PANEL field. Step 18) Select the SAVE AND CLOSE SETTINGS button.](.guides/img/addterm2.png)

<table><tbody ><tr><td><details><summary>
Helpful Advice!
</summary><hr>

Type `clear` into the Terminal's COMMAND field to get a much cleaner Terminal!</details></td></tr></tbody>
</table>
	
18. Click **SAVE AND CLOSE SETTINGS**.

19. Now, when you click **Preview**, you should see three panels: the code window, the Terminal and the Guide! 
