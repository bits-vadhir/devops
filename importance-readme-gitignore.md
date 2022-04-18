### Why is a README.md file needed?

The readme file provides basic context and usage information for any project/library. It hightlights the important api and scripts that can be run to get the project up and running. When working in a distributed environment it is important for people who are setting up scripts or setting up new APIs/components to let other people know of the existence of these facilities, it can be done by updating the **README.md** file.

It can serve as a documentation for the library if you were to release it to the general public later on via npm.


### Why is a .gitignore file needed?

A _.gitignore_ allows us to tell git what files to ignore in any of the directories inside the codebase. This is done so that we only commit and use the really important tracking information needed to run the project, and nothing else. For instance in this project _node_modules_ directory has been ignored by git as it should be because node_modules is a heavy dependency that individual collaborators can download on their own and does not need to be committed or tracked on git. Other system or editor level config items can also be ignored in the same manner. Basically it is a file that explicitly tells git what files to ignore on a user's system.