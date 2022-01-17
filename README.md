# WebStimuli

Multimedia files for web-based experiments

## Accessing your stimuli and telling Lookit where to find them (or: what do I put for ``baseDir``?)

You have two options:

### 1. Use the latest version

If you always want to point to the latest version of your stimuli, you can access those at 
 
 `https://raw.githubusercontent.com/YOUR_USERNAME/lookit-stimuli-template/master/DIRECTORY/FILENAME.EXT`
 
 For instance, if your GitHub username is `kimberscott`, and you have a `cats.jpg` file in the `img` directory, you could link to it at 
 
 `https://raw.githubusercontent.com/kimberscott/lookit-stimuli-template/master/img/cats.jpg`
 
 Most Lookit frames allow you to specify a `baseDir` or base directory for your files, and then only provide filenames instead of full paths. You can learn more about that in the [docs](https://lookit.readthedocs.io/en/develop/researchers-prep-stimuli.html#directory-structure). **In this case, your `baseDir` would be**:
 
 `https://raw.githubusercontent.com/YOUR_USERNAME/lookit-stimuli-template/master/`
 
 This option has the advantage that if you make slight adjustments to your stimuli, you don't also have to update your study to use the new versions. However, if you delete any files or make other unexpected changes, it may break something in your study.

### 2. Use a specific version

If you want to point to a specific, fixed version of your stimuli - a 'snapshot in time' - you can select a particular "commit" to point to. From your fork of this repository, click the "N commits" at the top to view a list of commits. Click the "clipboard" icon next to the commit you want to use. This copies the COMMIT_ID. 

The URLs for the stimuli as they were at the time of this commit are:

`https://raw.githubusercontent.com/YOUR_USERNAME/lookit-stimuli-template/COMMIT_ID/DIRECTORY/FILENAME.EXT`

And **the `baseDir` to use is:**

`https://raw.githubusercontent.com/YOUR_USERNAME/lookit-stimuli-template/COMMIT_ID/`

## Making changes to your stimuli 

**Deleting files**: You can delete individual files by navigating to them in GitHub and then clicking the "trash" icon. You'll be prompted to commit this change. 

**Changing files**: You can upload new versions of your files in the same directory where the old ones are to replace them.

Each time you delete a file or upload a new file, you will need to commit the change and can write a short message about what you changed and why. Your commit history then shows a complete record of the changes you've made over time, which is very helpful for your future self.
