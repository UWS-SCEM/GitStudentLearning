# Introduction

Git allows teams to collaborate on common files, maintains versions of files and provides “branching” possibilities to develop different ideas that can be then incorporated into “main” branch.

# Learning

1. Create account on GitHub: http://www.github.com
1. Send me your Username (to t.trescak@uws.edu.au)
1. I will add you to the UWS SCEM organisation
1. On widows download and install DiffMerge tool https://sourcegear.com/diffmerge/
1. Download and install the SourceTree software (https://www.sourcetreeapp.com)
1. Watch this video (30 mins): https://www.youtube.com/watch?v=srXdUml4_HM
1. If you are still not sure, watch this one as well (14 mins): https://www.youtube.com/watch?v=1lBdlh3AGSc

# Practice

Following the instructions in the video and after I have confirmed you as a member of UWS-SCEM organisation:

1. Clone following repository onto your computer: https://github.com/UWS-SCEM/GitStudentLearning
1. Create a file “<yourname>1.md” and put some Markdown formatted (http://daringfireball.net/projects/markdown/syntax) text in it
1. Create a file “<yourname>2.md” and put some markdown text in it
1. Check in  “<yourname>1.md” file with some meaningful text (do not check in the <yourname>2.md file)
1. Now check in “<yourname>2.md” file
1. Check out the “Documentation” branch or create a new branch of your choice
1. Modify one of the previous files <yourname>1.md or <yourname>2.md and add a new file.
1. Check in all your changes on this branch 
1. Check out the “master” branch. Please note that all changes that you have created on the other branch are gone and that a newly create file is missing (AWESOME!)
1. Since we are happy about what we did in the isolated branch, we will merge the changes to the “master” branch. 
1. Right click on “Documentation” branch (or on the branch you have created) and click on “Merge changes into master”. Please note that you always have to have the branch active that you are merging TO, not the one you are merging from.

1. The newly create file will magically appear on your drive, but most probably (depending on the changes you did to <yourname>1 or 2.md file in the non-master branch) you will run into merge conflicts.
1. This is shown with an orange exclamation mark next to the file name, see image below (Tomi1.md file):
1. Right click on that file and click “Merge changes running external diff tool”. On mac a file merge is launched, on widows DiffMerge should launch (if not, just configure paths to the tool)
1. Merge files to your likings (The right most window in DiffMerge contains merged file, the bottom window on Mac contains the merged file)
1. Save your changes, make sure the merged file looks the way you like.
1. Commit all your changes to the master branch. 
1. Your tree should look similar to this:
1. In case you create errors along the way, make sure you play with “RESET to commit” that undoes your latest commit or “RESET Files” that undoes changes to your files
1. If you are happy with results, “Push” changes onto server and let me know you are finished.


# For enthusiasts

If you want to work with git like Pros in the console (I don’t), check out this video
http://git-scm.com/video/what-is-git
