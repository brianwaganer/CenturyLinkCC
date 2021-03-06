# CenturyLinkCC
[![HitCount](http://hits.dwyl.io/thetotaljim/CenturyLinkCC.svg)](http://hits.dwyl.io/thetotaljim/CenturyLinkCC)

>CenturyLink Coding Challenge: Github API

Here is my response to the CenturyLink Coding Challenge. It uses Github APIs to get three levels of follower data when given an initial Github ID.  This file was written using AngularJS, JavaScript, Bootstrap, and HTML.  It was completed in an attempt to secure a position at CenturyLink. Thanks for checking it out!

## Requirements

Web browser.

## Installation

To use this file, download it and then copy the file's path and paste into a browser search bar. 

## Usage Example

After loading the file into a browser window, enter a Github ID into the search bar, and press the search button.

![Picture](https://github.com/thetotaljim/CenturyLinkCC/blob/master/centuryLinkAPI.png)

The given Github ID will be used to find the user's first 5 followers.  After the first 5 users have been found (first level), then a second level search will be done on these 5 followers to find the first 5 followers of each one (second level). This process will then be repeated for each of those followers (third level). The JSON returned from each API call will be displayed on the page separated by what level of search it belongs to. 

## Contents 

centuryLinkCC.html

## Meta

Jim Steimel [@jimsteimel](https://twitter.com/jimsteimel) - jim@thetotaljim.com - www.thetotaljim.com
