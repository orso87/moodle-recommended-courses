<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Moodle plugin for recommended courses

Final project for the Building AI course

## Summary

An AI plugin that recommends courses to the student based on their courses history.
This plugin is based on the last 5 courses completed by users. 


## Background

The idea is to increase the number of courses attended by users and grow their knowledge.
I work in a training office and I know that it is difficult to find the right course among many.
With a plugin like this, it will be easier to find the right next course based on your learning history.
Moodle is the most used LMS in the world. Many can take advantage of this plugin.


## Data sources and AI methods

The data comes from the company's LMS db (standard moodle database). They are collected autonomously by automatic procedures.
The algorithm used is the KNN. Based on the user's learning path, it returns the most likely course.


## Challenges

Big limitations are the context bubbles.
By recommending courses, based on the choices of other users, the number of courses shown is limited after a period of time.
A possible solution could be to create a second plugin like this one that recommends courses that are not consistent with your learning path and display it next to the first.
In this way it is possible to move the curiosity of users.


## What next?

This project could grow to become an official Moodle LMS plugin.
To do this I need someone who can develop in the Moodle environment system. 
