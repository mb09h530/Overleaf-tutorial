![](header.png)
# Tutorial 3: Writing publications with Overleaf (Work in progress)

This tutorial in the context of the **Reproducible Research Workshop** provides you with the first steps on how to write publications in Overleaf.

**Objectives of this tutorial:**

* Subscribe to Overleaf
* Create a new Latex project in Overleaf
* Share your project with colleagues
* 

## Motivation
Overleaf is an online LaTeX editor with integrated real-time preview. 
It allows you to collaborate with your co-autors who can review, comment, and edit the document.
Your project is compiled in the background and you can see what it looks like right away.
It offers a rich text mode for those who do not like to work directly in the LaTeX code.

## Part 1: Subscription

**1. Sign up:** To get started you need to sign up for Overleaf on the **[Overleaf webpage](https://www.overleaf.com/)**.

![](sign_up.PNG)

**2. Sign in:** Once you have signed up, you can log into your account. The first time you sign in, you need to verify your e-mail address and to set a password.

## Part 2: Create a new project
**1. Create project:** You can now create your first project by pressing on the "create a new project" button. A window will pop up providing you with a choice of possible templates. For now, we choose the blank paper under the heading basics.

![](create_project.PNG)

A new window opens containing your new project.

![](elements.PNG)

The working surface is composed of three areas: 
* The area to the left where you manage the files being part of your document (tex file, bibliography, figures,...) and where you can download your project as a zip-file;
* The part in the middle showing the tex file containing your LaTeX code;
* and the part to the right where your document is displayed as a pdf after compilation (which is done automatically).

**2. Upload your own tex-file:** Currently, your document just consists of a blank file. However, we would like to continue working on the document you created in Tutorial 2: Writing publications with R. 
The easiest way to upload a new tex file is to upload it from your local computer. To do so, click on the add files button in the upper left corner and choose upload from computer.

![](replace_tex.png)

You can either drag your file (which you probably called publication.tex) to the uploading window opening or choose a file via the CHOOSE FILES button.

![](drag_file.PNG)

To make it your main tex file, you need to delete the existing file main.tex. This will make your publication.tex file the new main tex file. Overleaf will now try to compile your document. This will produce an error as indicated by the red square in the upper right corner.

![](compilation_error.PNG)

When you click on "go to first error", Overleaf will indicate you where in your tex file the error is caused. In our case, it is unable to load a picture you want to call from a pdf file. For Overleaf to find it, we need to add it and all other external files that are called in the main tex file to our files as well.
To do so, click on the add files button in the upper left corner again and upload all figures used.
Once you have uploaded all figures referenced to in the tex-file, Overleaf will compile a pdf of your document.

![](compiled_pdf.PNG)

**3. Modify document:** Now it is time to make changes to your document. Add text, figures, tables, lists,...
You can either work directly in the source code or switch to rich text if you are not that familiar with the LaTeX language.
To do so, just click on the button Rich instead of Source.

![](rich_text.PNG)


