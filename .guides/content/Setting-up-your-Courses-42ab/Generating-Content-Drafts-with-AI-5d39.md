Codio provides a suite of AI-assisted authoring tools that can speed up the content writing process. The Generate Content Wand in the editor ribbon lets you generate a page of instructional material for any assignment effortlessly.

![Generate Content Button](.guides/img/generate-content-button.png)

When you are in edit mode, you can start by clicking on the Toggle Sections List Button in the top right corner and click on Add Page. This will add an empty guide page in your assignment titled "New Page". Giving your page a thoughtful name before starting the Generate Content process is one of the best practices to ensure that the LLM generates exactly what you're looking for.

Next, click on the Generate Content button on the editor ribbon. It will open a tab in the right panel with information about the Course, Module, Assignment as well as the Page you're on. These titles will be used as context for the AI tool in order to get a well drafted page of content using Anthropic's Claude Large Language Models (LLMs).

||| info 
**Note:** If you haven't changed the name of your page from "New Page", it will not show up in the Generate Content tab as context.
|||

![Generate Content](.guides/img/generate-content.png)

The Optional Requirements text field allows you to specify every little detail about how you want the page to be generated.

You can include things like:

- The concepts that have been covered in the assignment so far.
- The topics that you wish the page to be about.
- The topics that should be excluded from the page.
- Whether you want the page to address novice or advanced learners, and much more!

You can also get very creative with it by specifying a tone or theme that the content should be presented in, and even ask for real world examples to be included as part of the instructional material. Just think of this as your "Vision board" for what you want the page to be and it will adhere to these guidelines and generate a page of content the way you want it to.

In this example, we're trying to get a page of content on Standard Input in Python and we've given it some instructions on what we want the page to look like:

![Generate Content Example](.guides/img/generate-content-example.png)

Now, click on Generate and the tool will preview the generated content for instructors to approve.

||| info
**Note:** LLMs are tools that will always try to generate whatever you ask for, and as a tool designed by humans, can provide incorrect or erroneous results sometimes. It is very important for instructors to review the generated material, approve and edit it as required.
|||

## Example Prompts

- Summarize other chart/plot types in Matplotlib that haven't already been covered in this list: Box plots, Histograms, Line Charts, Area charts, Scatter Plots, Bubble Charts, Pie and Donut Charts.

- Please explain what perfect arrays are in C++ and how they differ from other array types in that programming language.

- List the different Javascript frameworks available, their differences, and their advantages.

## Example of Creating the Page Title First and Then Supplying the Prompt

Page title: "Security Concerns for Websites"

Prompt: Use governmental websites for the information you provide and add citations. Also, provide information about security breaches to illustrate why you should use security measures.

## Approve and Apply Content to Guide Page

If you're happy with the content preview, you can click Approve to paste the generated content on the markdown page.

![Generate Content Edit Page](.guides/img/generate-content-edit-page.png)

![Generate Content Output](.guides/img/generate-content-output.png)

## Regenerate and Toggle Between Drafts

If you're not happy with the generated draft, the tool gives you an option to refresh or modify the content it generated for you.

Simply update the requirements with what you want changed on the page and click Regenerate - you'll have an updated draft with the required changes in seconds.
(for e.g., changing the examples, adding a paragraph on a concept, removing something, adding more code snippets or examples, etc.)

You can also toggle between drafts you generate (in case you like one better than the other and apply the generated draft of your choice to the guide page by clicking Approve)