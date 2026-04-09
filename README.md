 



# Web Application Security Lab – Unprotected Admin Functionality

## Overview
This repo contains my work on the PortSwigger Web Security Academy lab called **Unprotected admin functionality with unpredictable URL**. The lab is about access control issues and how hidden admin panels can be discovered and abused.

## Lab Description
- Topic: Access Control  
- Focus: Privilege escalation through unprotected admin functionality  
- Task: Find the hidden admin panel and delete the user `carlos`  
- Difficulty: Apprentice level  

## What I Did
1. Looked through the application and checked the source code.  
2. Found a script that revealed the admin panel path (`/admin-4edqnv`).  
3. Went directly to that URL to access the admin panel.  
4. Deleted the user `carlos` from the panel.  
5. The lab was marked as solved after that.

## Contents
- Screenshots of the process.  
- HTML snippets showing how the admin panel link was hidden in the code.  
- Final confirmation message: *“Congratulations, you solved the lab!”*  

## What I Learned
- How unprotected admin panels can be exploited.  
- Why it’s important to check source code for hidden functionality.  
- How privilege escalation works in practice.  
- Why developers need proper access control to secure applications.  
---

Would you like me to also add a short **“How to run/view”** section (like instructions for opening the PDF or browsing the screenshots) so anyone visiting your repo knows exactly how to use the files?
