# Small-Scripts
This repo mainly to save the small scripts I wrote to automate small tasks that I do not to repeat every time.

## require.py

__The store of the script__

Because there are many tools that need many libraries to run and in every time we create new VM or OS that files need to install the same requirement.txt file.

__What does it do__

I wrote this script to list & install all requirement.txt files once you run it.

__Usage__

You can run it with "sudo python3 require.py"

## check-status.py

__The story of the script__

During bug hunting activity I get URL's from web archive and I need to know which one are still alive or valid before I do the test that's why I wrote this script. 

__What does it do__

By accepting txt file with all the target URL's inside the script make normal request to each URL and past it in the terminal if the response status is of 200, 301 or 302. 

__Usage__

You can run it with "sudo python3 check-status.py file_name.txt"

<!-- 
To add new script you need to follow this instruction

## The file name

__The story of the script__

Descripe the story behind the script or why you wrote it in the first place

__What does it do__

Here you should descript what this script do and optionally how it works

__Usage__

Here you should descripe how anyone can use this script

-->
