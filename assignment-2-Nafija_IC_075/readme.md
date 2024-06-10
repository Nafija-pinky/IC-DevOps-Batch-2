

Name: Nafija 
ID : Nafija_075 

Assignment_2 (Linux Fundamentals)


# Change directory to /home
cd /home

# Print current working directory
pwd

# List files in /home in long format, sorted by modification time in reverse order
ls -lrth

# Change directory to /var/log
cd /var/log

# List files in /var/log in long format, sorted by modification time in reverse order
ls -lrth

# Find the location of the bash executable
which bash

# Print the shell being used
echo $SHELL

# Create a directory named linux_fundamentals
mkdir linux_fundamentals

# Change directory to linux_fundamentals
cd linux_fundamentals/

# Create a directory named scripts with superuser privileges
sudo mkdir scripts

# Create an empty file named example.txt with superuser privileges
sudo touch example.txt

# Create a directory named backup with superuser privileges
sudo mkdir backup

# Move the file example.txt to the backup directory with superuser privileges
sudo mv example.txt backup/

# Change directory to backup
cd backup/

# Change permissions of example.tx to 644 with superuser privileges
sudo chmod 644 example.tx  # Note: There's a typo in the filename

