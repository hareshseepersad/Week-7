# Project 7 - WordPress Pentesting

Time spent: 10 hours spent in total

> Objective: Find, analyze, recreate, and document **vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) User Enumeration, WordPress 4.2:

The following is a vulnerability that allows anyone the ability to enumerate a list of valid usernames on a WordPress site. Just by guessing common usernames the site will tell you if they exist, allowing the creation of a list of valid usernames. This can potentially lead to numerous guesses of passwords on numerous accounts! A solution can be when a correct username but wrong password is given, do not elude to the fact the account exists. Reply with "either username or password is incorrect."
  
  ![](https://github.com/hareshseepersad/Week-7/blob/master/Username%20Enumeration.gif)
  
2. (Required) XSS ,Test Version: WordPress 4.1, Patched In: WordPress 4.7.4

In older versions of Wordpress it is possible for a carefully crafted file name to execute cross site scripting. This is due to the lack of file name sanitation. 

![](https://github.com/hareshseepersad/Week-7/blob/master/Wordpress%20XSS.gif)
  

3. (Required)XSS, Test Version: WordPress 4.2, patched WordPress 4.6.1:

The following is a vulnerability that allows users with editor privileges to embed cross site scripting on their post. This may be used for privilege escalation if users of admin privileges were to view the page. This vulnerability was patched in 4.6.1.

![](https://github.com/hareshseepersad/Week-7/blob/master/Wordpress%20XSS2.gif)
  
## License

    Copyright [2018] [Seepersad]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
