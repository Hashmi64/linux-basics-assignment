Linux Basics Assignment
This repository contains the Linux basic commands and screenshots used to complete the assignment.
STEP 1 — Creating and Renaming Files/Directories
Commands:
mkdir test_dir
cd test_dir

touch example.txt
mv example.txt renamed_example.txt

STEP 2 — Viewing File Contents
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd

STEP 3 — Searching for Patterns
grep "root" /etc/passwd

STEP 4 — Zipping and Unzipping
zip -r test_dir.zip test_dir[Linux_Assignment_Final.docx](https://github.com/user-attachments/files/23417323/Linux_Assignment_Final.docx)

unzip test_dir.zip -d unzipped_dir

STEP 5 — Downloading Files
Note:
The given URL https://example.com/sample.txt showed 404 Not Found.
So I used a valid URL:
wget https://raw.githubusercontent.com/vinta/awesome-python/master/README.md

STEP 6 — Changing Permissions
touch secure.txt
chmod 444 secure.txt
ls -l secure.txt

STEP 7 — Environment Variables
export MY_VAR=HelloLinux
echo $MY_VAR


