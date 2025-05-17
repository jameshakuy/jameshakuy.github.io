---
layout: project
type: project
image: img/sc.jpg
title: "AP Course Manager"
date: 2025
published: true
labels:
  - Course Manager
  - Recommendation System
summary: "Farrington High School’s lack of marketing for AP courses left many students unaware of available classes or misled about their workload, resulting in missed opportunities or poor academic performance. To solve this, we built an AP Course Manager that lists all AP offerings, lets teachers manage courses, and uses AI to recommend classes based on each student’s interests."
---

# What is the AP Course Manager?

This project came to life from an issue that Farrington Highschool faced, which they have little to no marketing on AP Classes. This is problematic in a few ways. The most obvious problem is that some students don't know these classes exist so they can't even sign up for it even if it's a topic they are interested in. Another problem is that say they did know the class existed but they don't really know the contents or the workload the course offered then they miserably fail the class. This will hurt their gpa and it's the administrator's fault for not properly advertising the class correctly. With these issues in mind, we decided to create an AP Course Manager in which displays all available AP classes, allows teachers to add/manage classes, and we used AI to return a list of recommended classes based off their interests.

# My contribution
My identity on the team was the "AI guy". I have previous experiences on AI so it only made sense for me to implement the AI work. Before I get into detail on that, I also worked on smaller issues such as configured the database and such. For the AI, we lacked data. We didn't have access to past records of students at Farrington and even if we did, I'm skeptical on even if that would be enough to train a classical ML model for classification tasks. So instead, I first decided for students to submit a form of interests. Then, using that data, I would input the data in a statistical model in which it looks for the most similair (in meaning) word class wise if that makes sense. Then, it returns the top k amount of classes. If you would like to know more, you can search up "cosine similarity".

# What I learned
Merge conflicts are a PAIN. (Not really a joke) Jokes aside, I've only twice worked on collaborative repositories with other people so it was a good experience working with version control and such. I also learned how to deploy, deploying Python code specifically. What's interesting is that I had to deploy my python code separately on a different service than Vercel. Setting up the deployment and making it point at Vercel was a challenge but I definitely learned a lot.

Here are a few screenshots of the project, if you would like to see more, you can visit the Github [here](https://github.com/farringtonap/apcoursemanager)

