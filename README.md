# Extracting-Social_network_groups_from_Videos
Use of motion similarity and network clustering to find the social network groups from videos

The code is divided into main parts
1. Analysis code - Actually performs the extraction task
2. Query code - Creates a GUI that enables the user to query the results and find out who belongs in what group.

The analysis codes needs to run once and it will create all the files that are used to run the query code
Query code can be run multiple times after the analysis code has run once.

In the analysis code, there are options to run different simulations or UCLA video code.
Query code is required to be run only for UCLA video code .
The part of the code that needs to run requires to be uncommented in the function "Analysis Code"

Video paths and ground truth file paths need to be changes in the global variable section if the user is running the UCLA video.
Nothing needs to be done in case of simulation videos

