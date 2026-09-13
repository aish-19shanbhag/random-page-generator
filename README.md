# Random Webpage Generator

A landing page that randomly redirects to one of several small web-app demos, built as a team project for a Web Technologies course.

## Overview

The home page presents a single button. Clicking it navigates to a randomly selected demo from a set of small web applications, each showcasing a different web technology:

- **Calculator** (`calci.html`) — a basic calculator built with HTML, CSS, and JavaScript
- **Rock, Paper, Scissors** (`rock_paper.html`) — a simple browser game
- **To-Do List** (`todo_list.html`) — a task list built with HTML/CSS/JS
- **Snake** (`snake.html`) — a browser-based game
- **Login & Registration** (`login.php`, `registration.php`) — a PHP + MySQL login system with session handling

## Team Project

This was built as a 3-person team project (Sai Shruthi S, Kokila K N, Aishwarya Ramanath Shanbhag) for a Web Technologies course.

## Tech Stack

- HTML, CSS, JavaScript
- PHP
- MySQL

## Known Limitations

The login system hashes passwords with MD5, which is not a secure hashing algorithm by modern standards (a production system should use `password_hash()` in PHP instead). This reflects the original scope of the assignment rather than a production-ready implementation.

## Author

Aishwarya Ramanath Shanbhag
