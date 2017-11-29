# week7
# Project 7 - WordPress Pentesting

Time spent: **Somewhere in the 20-40 hours range** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php) 

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

 
 

 
 
 




I’ve worked on installing wordpress for about 7-8 hours now.  I have removed WPDistillery multiple times.  Figured out I was missing git, so I installed that.  I forgot to install the virtualbox extension, so I added that in.  I then deleted WPDistillery and started over from that point.  I check my wpdistillery/config.yml file and run it with the wpversion set to latest and a different time to nightly.  It will not successfully create the VM for wordpress.  I tried reinstalling vagrant.  That still did not fix the error that I was receiving.  
I tried going into the /etc/hosts file and manually and adding 192.168.33.10 wpdistillery.dev all in one line as was suggested when I asked for help.  It says that I can only edit it as an administrator.  So, I ran notepad as an administrator and I cannot find the file in that mode to edit it.  I tried to copy the doc and edit it on the desktop and save it there then drag it to the location of the hosts file, but it still says I don’t have permission.
 

Next, as suggested in the help forum I edited the permissions of the user and I got a screen saying that the process was in use.  I figure out with some research that my antivirus was protecting the hosts file.  So, I was able to tell the antivirus not to protect the hosts file and the installation of Wordpress completed.

 
After changes to antivirus protection:
 
 
 
 
 
 
Next step of going to the blog now gets me this:
 
 
 

 
Ip is 10.0.2.15 /24


## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

