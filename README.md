In this project, we'll work with a dataset of submissions to popular technology site Hacker News.

![image](https://github.com/user-attachments/assets/fdd55cb7-2b79-48cc-b440-c0713ffe28aa)

Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") receive votes and comments, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of the Hacker News listings can get hundreds of thousands of visitors as a result.

Below are descriptions of the columns:

id: the unique identifier from Hacker News for the post
title: the title of the post
url: the URL that the posts links to, if the post has a URL
num_points: the number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
num_comments: the number of comments on the post
author: the username of the person who submitted the post
created_at: the date and time of the post's submission

Here are the first few rows of the dataset:

![image](https://github.com/user-attachments/assets/452c4832-e013-448c-bfb2-880e59f733a2)

We're specifically interested in posts with titles that begin with either Ask HN or Show HN. Users submit Ask HN posts to ask the Hacker News community a specific question. Below are a few examples:

![image](https://github.com/user-attachments/assets/4eccf111-5523-4291-8e8d-699e5fbcca8f)

Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just something interesting. Below are a few examples:

![image](https://github.com/user-attachments/assets/d19d0845-32f1-431e-b0bf-f9d761166137)


Let's start by importing the libraries we need and reading the dataset into a list of lists.
