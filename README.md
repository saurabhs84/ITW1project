#!/bin/bash

echo "Welcome  To File Installer S"

sleep 1

echo "please Enter Your project Name: "

sleep 2

read projectname

mkdir $projectname #root folder

echo "Root folder created..."

cp main.html $projectname/main.html

cp main.css $projectname/main.css

echo "File has been copied.."

cd $projecrtname

mkdir file1

mkdir file2

mkdir file3

mkdir file4

mkdir file5
