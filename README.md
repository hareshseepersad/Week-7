# Project 7 - WordPress Pentesting

Time spent: 10 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) User Enumeration, WordPress 4.2:

The following is a vulnerability that allows anyone the ability to enumerate a list of valid usernames on a WordPress site. Just by guessing common usernames the site will tell you if they exist, allowing the creation of a list of valid usernames. This can potentially lead to numerous guesses of passwords on numerous accounts! A solution can be when a correct username but wrong password is given, do not elude to the fact the account exists. Reply with "either username or password is incorrect."
  
  ![](https://github.com/hareshseepersad/Week-7/blob/master/Username%20Enumeration.gif)
  
1. (Required) XSS , Patched In: WordPress 4.7.4

In older versions of Wordpress it is possible for a carefully crafted file name to execute cross site scripting. This is due to the lack of file name sanitation. 

![](https://github.com/hareshseepersad/Week-7/blob/master/Wordpress%20XSS.gif)
  
