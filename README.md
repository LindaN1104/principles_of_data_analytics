# Principles of Data Analytics

Author: Linda Nikolajeva

## Abstract

## Table of Contents

note to self include anchor points that jump straight to the relevant sections

## About Myself ... the Author
A quick summary about myslef. I hold a Honours Bachelor of Business in Marketing and Management, and a Honours Master of Science in Human Resource Management. I attended the Technological University of the Shannon and the University of Limerick.

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQb5nVR28Ehlrax3IAo5yIwYH33zhJ71R_QSA&s" width="150" title="University of Limerick">

<p align="center">
  <img src="data:image/png;base64,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" width="150" title="Technological University of the Shannon">
</p>

I am interested in how a business functions, I love to observe patterns, and come up with business solutions. I believe this is where my interest in data analytics began. I love pulling data and transforming it into a user friendly format, which hopefully then benefits the business decision making process.

## What is principles_of_data_analytics (The Repository)
### Purpose of This Repository
This repository contains tasks.ipynb jupyter notebook.
**[For quick access to the notebook click here.](tasks.ipynb)**

tasks.ipynb is my submission for grading for Priniples of Data Analytics module. It is one of X modules for Higher Diploma in Science - Computing (Data Analytics), at the Atlantic Technological University Galway-Mayo. 
This module is an introduction to the principles and fundamentals of data analytics, including the acquisition, cleaning and exploration of data sets. 

As such, by the end of this module, 04 May 2025, this repository should showcase my ability to
* Source and investigate sets of data.
* Programmatically explore and visualise data.
* Apply basic mathematical data analysis techniques to data sets.
* Model real-world problems for analysis by computer.
* Provide evidence in a decision-making process using a data set.
* Appreciate the limitations of graphical representations in data intensive workflow

*[Source for above info](https://springboardcourses.ie/details/14016)*

### tasks.ipynb Description

What it is... what data set it uses... main points it looks at... etc...

## Setup needed for tasks.ipynb in a GitHub Codespace
This goes through the steps needed to access tasks.ipynb
1. Sign Up for a GitHub Account
    
    If you don’t already have a GitHub account, go to [GitHub](https://github.com/) and sign up for a free account.

2. Navigate to the Repository

    Open your web browser and go to the repository page where tasks.ipynb is located. You can find the repository by searching for it on GitHub or by using this [direct link](https://github.com/LindaN1104/principles_of_data_analytics).
    
    [Navigate to the Repository](github_search_bar.png)

3. Open the Code Options Menu
    
    On the repository page, click the green "Code" button, which is located near the top right of the file list. This will open a dropdown menu with multiple options for accessing the code.

4. Select the Codespaces Tab
    
    In the dropdown menu, click on the "Codespaces" tab. This tab allows you to launch an online development environment directly in your browser.

5. Create a New Codespace
    
    Click the "Create new Codespace on main" button. GitHub will then set up a cloud-based development environment, which may take a few moments. Once the Codespace is ready, you will have access to the repository files, including tasks.ipynb.

Note to self... insert screenshots for above steps
https://stackoverflow.com/questions/10189356/how-to-add-screenshot-to-readmes-in-github-repository

Now, you can open tasks.ipynb and start working on it within the Codespace environment! 

## Technologies

- Python
- Git
- GitHub
- Code Spaces
- Jupiter

## Requirements

what is required to run this notebook...

## References Used to Format README
note to self... maybe put this into table?

[About READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

[Managing your profile README](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)

[Insert/overwrite shortcut key in Jupyter](https://stackoverflow.com/questions/37606190/insert-overwrite-shortcut-key-in-jupyter)

[How to add images to README?](https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github)

[Markdown for Jupyter notebooks cheatsheet](https://www.ibm.com/docs/en/watson-studio-local/1.2.3?topic=notebooks-markdown-jupyter-cheatsheet)

[How to indent a bulleted list in a README](https://stackoverflow.com/questions/26960735/how-do-you-indent-a-bulleted-list-in-a-readme-file-using-github-flavored-markdow)

[15 Elements to Include in Your README](https://www.archbee.com/blog/readme-document-elements#:~:text=The%20README%20file%20guides%20users,%2C%20license%20information%2C%20and%20more.)

[Help from Chat GPT - Set Up section](https://chatgpt.com/c/67d34263-9220-8005-b2e8-afe81ccc05ef)

## End