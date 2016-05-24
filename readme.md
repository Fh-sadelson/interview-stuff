# Requirements for Job

1. We want someone who writes code not just for their day job, but for their 
   own interests as well. I want to see a project on Github, an app the person 
   built, or any other programming done for themselves.
1. Experience with PHP. Bonus for knowledge of Yii2. Further bonus for knowing 
   other frameworks.
1. Experience with Javascript. Bonus for knowing Backbone.js or other front end 
   frameworks. 
1. Experience with Linux web servers (LAMP stack). Bonus for knowing Nginx, 
   Fedora, Ubuntu, selinux, shell scripting and automation.
1. Experience with MySQL. Bonus for DBA experience, optimizing queries, 
   automating backups, replication. More bonus for other databases, MS SQL 
   Server, MongoDB, Postgres, etc.
1. Experience with AWS (EC2, RDS, S3). Bonus for knowledge of security, VPN, 
   VPC, groups and roles. More bonus for Ansible, Chef, Puppet, Docker, or other 
   modular deployment methods.
1. Experience with software architecture. Here’s where we do a really hard 
   interview question.
1. Experience with git, GitHub, and branching workflows. Bonus for understanding 
   how to manage feature branches, test branches, deploy branches, and staging 
   servers (with examples).
1. Experience with project management tools (issue tracker, sprint planning, 
   requirements, test case management). Bonus for having documented use of those 
   tools (not just talking about it.)
1. Awesome communication skills. Explain something complicated. Convince me of 
   something. Ask me a difficult question.
1. Interested in things. Everyone has interests. We want someone who is 
   interested in a lot of things and learns and experiments all the time. We 
   want the person who figures things out. We’ll ask about that in the 
   interview.
1. Understanding of Customer Service. As employer, the company would be the new 
   hire’s customer. Co-workers are customers. Customers are customers. How do 
   you provide a product to someone? How do you follow up? How do you find out 
   how happy they are with what you’ve done? We’ll ask for specific examples in 
   the interview. 

# Pre-screening

1. Link to github profile.
1. Link to web application created by applicant.
1. Link to web application maintained by applicant.
1. Link to resume.

# Interview Questions

1. What is something you have done which generated revenue for a past
   employer?
1. What is something you have done which saved money for a past employer?
1. What is something you have done which has cost money or lost revenue for
   a past employer?
1. What languages would you advise a client to use or avoid, and why?
1. SQL: What is the difference between WHERE and HAVING? Why is this
   important?
1. Algorithm: Describe a sort algorithm with the worst time complexity you can.
   Then describe a sort algorithm with the best time complexity you can. Why
   is this important, and how are they different?
1. What do you do when writing code to make it easier to write unit tests?
   Why does this make it easier?
1. Briefly explain something you are interested in which is not job related.
1. What are your favorite tools and how do they help you get things done
   faster?
1. What is your favorite front-end framework, and why?
1. What is your favorite language and/or framework for building an API? Why?
1. What is your favorite database? Why?
1. What does it mean to scale horizontally instead of vertically? Why is
   this valuable?
1. Write a FizzBuzz solution quickly in your favorite language. There are
   bugs. Where are they? Change it to use map on an array. Solve with the
   modulus operator. Solve with counters. Solve with composable functions.
1. Design our Investment Manual Options system. (Really.) We'll add
   requirements as you draw the design. And then add more so you have to
   adapt.
1. Design Google Calendar.(See below)

# Fizzbuzz

   Write a program that prints the numbers from 1 to 100. But for multiples of 
   three print “Fizz” instead of the number and for the multiples of five print 
   “Buzz”. For numbers which are multiples of both three and five print 
   “FizzBuzz”.

# IM Options

We have a large number of parts which can go into a given home construction.
Here are some of the attributes of that design problem:

1. Multiple plans, some requiring certain options, some forbidding certain
   options.
1. Mutually exclusive or required options.
1. Option Packages which require or exclude options or other packages.
1. Region, Division, Community, Site, Plan, Location inclusions, exclusions, 
   requires, and overrides.
1. Vendor part numbers, prices, and availability.
1. Margin calculation.
1. Square footage calculation for price.
1. Pictures by Option, Plan, Style, Location, with default images or best of
   available.
1. How to manage options when creating a new plan?
1. How to audit option configuration for an existing plan?

# Design Google Calendar
1. How do you represent events on the calendar?
1. How do you represent events that repeat?
1. Repeat every Monday and Friday.
1. Repeat the third Friday of every month.
1. Repeat the first Monday after the third Friday of every month.
1. Repeat the first Wednesday of the month, every other month.
1. Store the repeating schedule in the database in such a way that you can
   search for any repeating activity that occurs on a specific date.

