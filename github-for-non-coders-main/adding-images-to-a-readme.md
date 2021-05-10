# Adding images to a README *(In progress draft)*

Images stored in a repository can be added to the README using image paths.

<br />

**In this guide:**

[Introduction](#introduction)  
[Creating a folder](#creating-a-folder)  
[Uploading images](#uploading-images)  
[Adding image paths to the README](#adding-image-paths-to-the-readme)  

<br />

## Introduction

*Prerequisites*

<br />

## Creating a folder

1. Navigate to your repository.

1. Click "Add file" and select "Create new file."

1. Type the folder name in the "Name your file" field. To identify it as a folder, type `/` at the end of the name.

1. Type `.gitkeep` in the new field that appears. This is a placeholder file that is necessary because GitHub doesn't allow empty folders. It can be deleted once you add images to the folder.

   > **Note:** Any file name works, but '.gitkeep' is a GitHub convention. 

1. Click "Commit new file."

<br />

## Uploading images

1. Within the folder you just created, click "Add file" and select "Upload files."

1. Follow instructions to drag or choose an image from your computer.

   >**Note:** *PLACEHOLDER List accepted file formats*

1. Commit changes.

<br />

## Adding image paths to the README

1. Navigate to an image file. Click the "•••" menu and select "Copy path." The path to the image's location in the repository is now on your clipboard.

1. Navigate to the README.md. Click the pencil icon to open the editor.

1. Markdown uses the format `![]()` to display images. Paste the image path within the parentheses `()`. Type alt text within the brackets `[]`. For example: 

    ````
    ![Image of the USS Enterprise in space with meme text that reads: "Get in loser. We're going to boldly go."](img/boldly-go.png)`
    ````
    
1. Commit changes.
