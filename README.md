# web-security
Week 7

# Project 7 - WordPress Pentesting

Time spent: **8** hours spent in total

> Objective: Find, analyze, recreate, and document **at least 3 vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. WordPress 2.5-4.6 - Authenticated Stored Cross-Site Scripting via Image Filename
  
  - [X] Summary: 
    - Vulnerability types: Cross Site Scripting
    - Tested in version: 4.2
    - Fixed in version: 4.6.1
    
  - [X] GIF Walkthrough: <img src= "https://github.com/noodlesny/web-security/blob/master/myGIFS/Week%207-Exploit%201%20Real.gif">
  - [X] Steps to recreate: 
  <ol>
  <li> Create a  new page. </li>
  <li> Add a title, and any text you want to include.</li>
  <li> Find an image and paste it onto the page.</li>
  <li> Add a cross site scripting exploit within the img src tags</li>
  </ol>
  
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/branches/4.2/src/wp-admin/includes/image.php)
    
    
2. 

  - [X] Summary: 
    - Vulnerability types:
    - Tested in version:4.2
    - Fixed in version: 
    
  - [X] GIF Walkthrough: 
  - [X] Steps to recreate: 
    <ol>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  </ol>
    
  - [X] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

3. 
  - [X] Summary: 
    - Vulnerability types:
    - Tested in version: 4.2
    - Fixed in version: 
    
  - [X] GIF Walkthrough: 
  - [X] Steps to recreate: 
    <ol>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  </ol>
    
  - [X] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)


4. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
    
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
    
5. (Optional) Vulnerability Name or ID
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

Describe any challenges encountered while doing the work

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
