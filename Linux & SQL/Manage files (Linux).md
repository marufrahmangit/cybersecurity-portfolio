# Scenario
As an analyst, you need to ensure that the `/home/analyst` directory is properly organized. You have to make a few changes to the `/home/analyst` directory and the files it contains. You also have to edit a file to record the changes or updates you make to the directory.

[Project reference](https://www.coursera.org/learn/linux-and-sql/home/welcome)

# Create a new directory
Create a new subdirectory called logs in the `/home/analyst` directory and list the contents of the `/home/analyst` directory to confirm that you’ve successfully created the new logs subdirectory.: `mkdir logs` > `ls`:

![image](https://github.com/user-attachments/assets/2f6ce4ae-4096-49b0-a41d-9eaf9b72a7e9)

# Remove a directory
Remove the `/home/analyst/temp` directory and list the contents of the `/home/analyst` directory to confirm that you have removed the temp subdirectory: `rmdir temp` > `ls`:

![image](https://github.com/user-attachments/assets/d1845655-2a10-4935-ac60-78a78e71f578)

# Move a file
Navigate to the `/home/analyst/notes` directory. Move the `Q3patches.txt` file from the `/home/analyst/notes` directory to the `/home/analyst/reports` directory. List the contents of the `/home/analyst/reports directory` to confirm that you have moved the file successfully: `cd notes` > `ls` > `mv <file> <directory>` > `cd .. ` > `cd reports` > `ls`

![image](https://github.com/user-attachments/assets/49460ad9-ade4-40c5-a841-368679d1cd0a)

# Remove a file
Remove the `tempnotes.txt` file from the `/home/analyst/notes` directory and list the contents of the `/home/analyst/notes` directory to confirm that you’ve removed the file successfully: `cd ..` > `cd notes` > `ls` > `rm <file>` ls

![image](https://github.com/user-attachments/assets/5e9babc9-08cd-4804-9ac7-dd13f4f2672b)

# Create a new file
Create a file named tasks.txt in the /home/analyst/notes directory that you’ll use to document completed tasks: `touch <file>` > `ls`

![image](https://github.com/user-attachments/assets/95b6e5c7-64d3-4a79-96b2-f1c301186f27)

