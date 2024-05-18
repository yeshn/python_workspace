# Yesh Notes
Followed steps as mentioned in https://jupyterlite.readthedocs.io/en/latest/quickstart/deploy.html
 - Basically go to **https://github.com/jupyterlite/demo**
 - Click on “Use this template” to generate a repository of your own from this template
 - Use the repository name as ~~**yeshn.github.io**~~ any repo name you want
 - This will create a new repostory with this name
 - ~~Then had to create an empty index.html file for the webpage to come up @ https://yeshn.github.io~~
 - Followed steps from **https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-from-a-branch**

    Publishing from a branch
    
        - Make sure the branch you want to use as your publishing source already exists in your repository.
    
        - On GitHub, navigate to your site's repository.
    
        - Under your repository name, click Settings. If you cannot see the "Settings" tab, select the dropdown menu, then click Settings.
        
        - In the "Code and automation" section of the sidebar, click Pages.
    
        - Under "Build and deployment", under "Source", select Deploy from a branch.
    
        - Under "Build and deployment", use the branch dropdown menu and select a publishing source.
    
        - Optionally, use the folder dropdown menu to select a folder for your publishing source.
    
        - Click Save.

- Your repo can now be accessed as Jupyter Lite page **https://yeshn.github.io/<repo_name>** 

<br>
<br>
You can open the jupyter notebook via mybinder.org Refer below link on how to go about it **https://github.com/Build-a-binder/build-a-binder.github.io/blob/master/workshop/10-zero-to-binder.md**
<br>
<br>
<b>Note:</b><br>
- You can only make local changes to the Jupyter Notebook when using with mybinder.org You will have to download the updated Notebook locally and commit to github seperately<br>
- DO NOT UPLOAD THE FILE FROM YOUR ORGANIZATON MACHINE TO GITHIB. YOU WILL SEE A WARNING POP-UP FROM YOUR ORGANIZATION
<br>
<br>
Markdown examples **https://www.datacamp.com/tutorial/markdown-in-jupyter-notebook**
<br>
<br>
Other ways to run your Jupyter Notebook in the cloud **https://www.dataschool.io/cloud-services-for-jupyter-notebook/**
<br>
<br>
You can create multiple sub-folders in <b>yeshn.github.io/\<repo_name\>/content</b> to effectively organise your code.
Similar to the <b>crypto</b> folder I have  created

<br>
<hr>
<br>


# JupyterLite Demo

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://jupyterlite.github.io/demo)

JupyterLite deployed as a static site to GitHub Pages, for demo purposes.

## ✨ Try it in your browser ✨

➡️ **https://jupyterlite.github.io/demo**

![github-pages](https://user-images.githubusercontent.com/591645/120649478-18258400-c47d-11eb-80e5-185e52ff2702.gif)

## Requirements

JupyterLite is being tested against modern web browsers:

- Firefox 90+
- Chromium 89+

## Deploy your JupyterLite website on GitHub Pages

Check out the guide on the JupyterLite documentation: https://jupyterlite.readthedocs.io/en/latest/quickstart/deploy.html

## Further Information and Updates

For more info, keep an eye on the JupyterLite documentation:

- How-to Guides: https://jupyterlite.readthedocs.io/en/latest/howto/index.html
- Reference: https://jupyterlite.readthedocs.io/en/latest/reference/index.html
