# About Me

How do we use HTML (Hypertext Markup Language) to create a website? As Dan Lawrence (2022) points out, self-teaching is "the most important skill for any professional," and we must "learn to become a patient and resourceful self-teacher" (pp. 42-43). Thus, we'll take a learn-as-go approach to coding. I'll help you along the way, but the best way to learn how to code is to try, troubleshoot, and revise.

The content in this folder, modeled after Stephen Quigley's (2022) [Open Fuego coding tool](https://kairos.technorhetoric.net/26.2/disputatio/quigley/openfuego.html), will help you learn how to code and draft the About Me portion of your final project.

You'll work through the prompts in the index.html file to construct a webpage that introduces who you are. Imagine you're presenting this webpage to a future employer. Your About Me should tell them your values and principles and how such qualities connect to your work as a professional writer.

I encourage you to play and explore. Coding can be frustrating, but it's highly rewarding when your piece goes live.

## Start Here

1. Go to the [eng-388-about-me repository](https://github.com/am-beardsley/eng-388-about-me.git).

2. Click the green "Code" button, and then click "Download ZIP" to your local computer.

3. Find this folder in your downloads.

4. Use your preferred browser to go to your GitHub page.

5. Click the "+" button and "New repository."

6. Name this repository about-me. **Note: Your repository will be public. Do not change any settings.**

7. Click the green "Create repository" button.

8. In the "Quick setup" section, click "uploading an existing file."

9. Drag the folder from your downloads to add it to the repository.

10. Click the green "Commit changes" button.

You now have code to play with! Next, you'll need to set up your codespace. GitHub Codespaces are instant cloud development environments where we can build and test websites without having to download software. This means you'll be able to access your work from any computer.

11. Click the dropdown menu on the left and click "Codespaces."

12. Click the green "New codespace" button.

13. Use the "Select a repository" dropdown menu to clone your about-me repository. **Note: Do not change any settings.**

14. Click the green "Create codespace" button.

15. Customize the VS Code for the Web source code editor.

16. Click around and familiarize yourself with the source code editor.

17. Click the index.html file and follow the instructions to begin modifying your About Me page.

## FAQ & Common Errors
### How do I add files to a GitHub Repository? 
!WARNING! Make sure you "unzip" the files you downloaded during Step 2 before you upload them to your repository (Step 9). Uploading zipped files, or a folder with content in it, will not work because the server does not know where to start displaying information on a website.
1. Right-click the zipped file.
2. Click "Extract All..."
3. Save the files to your Downloads folder.
4. Open the unzipped eng-388-about-me folder.
5. Select all of the files.
6. Drag and drop them into the GitHub repository.

### How do I open my Codespace to keep working?
1. Log in to your GitHub account.
2. Click the dropdown menu on the left and click "Codespaces."
3. In the "Owned by [your-username]" section, click the meatball menu (three dots) on the right, then "Open in..." and "Open in browser."

You will now be able to pick up where you left off! 

### What is a tag? 
A tag is a piece of hypertext markup language used to indicate the beginning and end of an HTML element. They are written using angle brackets: (<) and (/>). 

### How do I add files, like images, to my active Codespace?
1. Open your about-me Codespace.
2. Close any open files. For example, if index.html is open on your screen, click the "X" to close it.
3. Right-click in the empty space in the "Explorer" tab on the left side of the editor. **Note: Make sure none of the files are highlighted. Click in the empty space to unselect files.**
4. Click "Upload..."
5. Select the file(s) you'd like to add to your project.
6. Click "Open."
   
Your file should now be listed in your project folder!

### Do I really need to go through the steps to open a port to view my website while I work? 
Yes! Ports create temporary connections to servers that need to be recreated when we want to view our work again. 
1. If the Terminal isn't open, click "Toggle Panel" located on the top right of the screen.
2. The Terminal is open and ready for you to type! After the $, type **npm i -g http-server** and hit enter.
3. After the $, type **http-server** and hit enter.
4. A pop-up notification that says your application is running will appear. Click the "Open in Browser" button.
