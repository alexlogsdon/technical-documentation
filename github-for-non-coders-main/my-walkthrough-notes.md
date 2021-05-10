# My walkthrough notes

Before writing any documentation, I walked through the process myself. I placed myself in the mindset of a user and took notes as I went. Read them below! Notes include what I was feeling and thinking (as a user) as well as reminders to myself for later (as a writer).

<br />

#### Contents
- Tutorial: [Creating your profile README](#tutorial-creating-your-profile-readme)
- How-to guide: [Adding images to a README](#how-to-guide-adding-images-to-a-readme)

<br />

## Tutorial: Creating your profile README

### Setup

- I had an old repo in my profile. Deleted to see what a brand new user’s home page looks like. Thought I would need 3 possible starting points for accuracy and repeatability but then found a single simple solution:
  - [x] Use “+” in header nav because you can do it from any page  
- Account creation process is just like other standard websites. 
  - [x] Start tutorial at “create repo”
  - [x] **Prerequisite:** create account
  
### Create repo
  
- "You found a secret" pop-up **made me feel excited and successful** even though I haven't even pressed "go" on anything.
  - [x] Point it out in doc as celebratory moment. Sets a tone for GitHub's personality (despite the "scary" tech stuff for newbs).
  - [x] **INTRO the tutorial with the "secret" language to set that tone. Let user know they'll achieve something, and it's "special."** Even though they aren't programmers, they are welcome/worth it.
- Confused if I need a description, and what it would achieve/where it would appear.
  - [x] Put in a placeholder to see what happens- decide once I see result  
- Gut wants me to make it private by default (bc I don't know what I'm doing, and also privacy is important.)
  - [x] Note requirement for "public", for clarity/emphasis even though it also tells you in the pop-up 
- Don't know what any of the terms are for initializing options, descriptions are helpful but don't feel relevant to this task
  - "long description for project" doesn't feel helpful in this use case because there was a description form field above.
  - [x] Note README, tell them not to worry about the others. Say that the README file is where they'll write the info about themselves.
- Don't know what repo is, word shows up everywhere
  - [x] At **INTRO, do bare minimum explanation of repo** as storage place for files. Programmers use it to store code. We are going to use it to store a text file that will show up on your profile. Your "about me."

### Feedback on subtask success

- After creating, the repo page is *sort of* positive feedback... I know I did something but I can't really understand all the elements of the unfamiliar UI that I'm looking at.
  - Option to click "edit README" is helpful and clear, but **I want user to have positive feedback** that they successfully put a thing on their profile. Need to have **clarity that task is complete before switching** tasks in their mind to "now I can have fun deciding what to write."
  - [x] Note that they're looking at the home of their repo that contains all the information about it. Repos can contain multiple files and folders, and you could access them all here. But for this tutorial for your profile, you are only using one README file.
- [x] Next step - go to your profile via nav bar = success

### Edit README

- [x] Now change the placeholder text "hi there"
- There's suddenly more text in this box than "hi there"
  - [x] Note the 2 tabs, edit and preview
- Adding their text could happen before or after deleting the commented-out placeholder text (and the "hi there").
  - [x] **Pick a prescriptive path for user.** First instinct is: 
    1. Change header text
    1. Press enter and write your body text on the line right below the header. Use the ideas to get you started (like it says in the placeholder).
    1. Make bold and italic. List? **Basically, pick some markdown skills for them to learn** (Link to markdown reference - all sorts of interesting options, images, formats that they can explore.)
    1. Delete all the placeholder text within the angle brackets (including the brackets)
    1. Preview changes in the tab
- Wonder what I should write in place of "Update README.md" 
  - [x] Describe purpose (to easily keep track of the changes you made in your file). So name can be simple but indicative of what you did.
  - [x] INTRO include version control bare minimum explanation in addition to repo as storage place. 

### Feedback on task success

- Feel success seeing the repo update. But want to see it on my profile. 
  - Just noticed I can click on username in top-left file path. But it's confusing because the name of the repo is the same as the username, 
  - [x] ...so I'm going to **send users down the more intuitive/web standard path of going to the navbar/profile icon.** Otherwise would require explanation of file path UI. Unnecessary at this point even tho technically best practice.  
- SUCCESS!

### Conclusion

- [x] Add a **list of what they learned at the end,** to restate some key terms/concepts. (INTRO will be "this is the task you are going to do.")
- [x] Decide what to link to next? Explanation (uses for non-coders)... or would that come before, so that they have a reason/motivation to actually make an account? Other link option is the how-to. Or to a GitHub "be social" guide.

<br />

## How-to guide: Adding images to a README

### Setup

- Went to repo on sidebar. Other options are: 
  - repo name on profile (for profile README)
  - Profile > Repositories > repo name
  - Navbar avatar > Your repos > repo name
- Telling them to navigate to repo doesn't need the above detail because it's a prerequisite to be familiar with the GitHub repo UI
  - [ ] Link to explainer doc
- [ ] Other prerequisite: Have a repo, have an image on your computer ("Local" terminology? Check.)

### Creating an empty folder

- Create new file or Upload files? Not obvious because you need to create a folder first, not upload the image.
  - [ ] Specify CREATING A FOLDER as the subtask. Clear steps to click Add file, Create new file, because none of that intuitively communicates FOLDER.
- [ ] Clarify can name it anything, only requirement is `/` at the end. But example should show `img/` best practice.
- [ ] Same as above with .gitkeep
  - Q: Does it need `.`? A: No. Any name works.
  - Note to self: When I deleted my test .gitkeep files, it deleted the folder automatically because now it's empty.

### Uploading an image

- It automatically directs you to the img folder, so ready to select Upload file
- [ ] Drag or click to choose, 2 options
- [ ] PREREQUISITE: Have an image on your local comp. 
  - Tried to break that by dragging an image from another web browser, didn't work.
  - [ ] Research - Is there a list of accepted file formats? Link to it if so.
- Commit changes doesn't need elaboration/break down

### Adding the image to a README

- No visual feedback that it's in the folder, that's ok bc more familiar with the UI now. But still need to go back into the folder to get the file path.
  - Or they can use "go to file." Should I give that option? 
    - That seems like an advanced use case of the UI. With a basic understanding of the repo UI, you could easily understand going into a folder, and clicking copy path. And if you are familiar with "Go to file," you could do that too (especially if you have multiple paths you want to grab). But that's a UI issue, not part of the image adding task.
    - [ ] So I won't give concrete steps to go into the folder and find the image. I'll just say "navigate to the image file" and they can do that however they want. As long as you click "copy file path" and let GitHub do the work, you can't mess up the path for the image link in markdown.
- Then navigate to README and open the editor. (Like above, making UI knowledge assumptions.)
- [ ] Show empty markdown format inline `![]()` and example `![Image of the USS Enterprise in space with meme text that reads: "Get in loser. We're going to boldly go."](img/boldly-go.png)`.
- [ ] Mention "paste" the file path, since it was copied.
- "Commit" without further breakdown - assume knowledge.
  - Could have also previewed changes with their own knowledge.
- Yay it worked! I get feedback and I don't need to do anything else to feel confident that I did it. I went to view my profile because it was my profile README, but this is for all types of repo use cases so don't mention it. 


  
