---
layout: post
title: 'JEN Text File Editor'
---
This project could be described as a very simplistic file editor. The project consisted of a static web application, 
a NodeJS server, and a MySQL database. The web application consisted of simple HTML, CSS, and JavaScript. In 
practicality, the NodeJS server functioned as a wrapper for the database and served the static web application. The
MySQL server consisted of a few tables that related users to their profile information, users to their files, users to
their shared files, and users to their session tokens. Within this application, users could make files, edit them via
a text editor, and save them. They could also share these files with other users, giving them various permission levels.
Within this project, I handled almost the entirety of the NodeJS server, as well as the frontend JavaScript. For this
project, I relied on the experience I had in previous projects to build the server's API, allowing the frontend JS
to pull down and populate the appropriate information, including file lists, names, and file content.

The home screen for a user after they login. They are able to view their owned files, as well as any files shared
with them.
{% include image.html text="" image="jen-files.png" %}

This is the simplistic window used for editing a user's file.
{% include image.html text="" image="jen-edit.png" %}

In order to share a file, the user would simply choose a "Share" option, which would give them this screen.
{% include image.html text="" image="jen-sharing.png" %}