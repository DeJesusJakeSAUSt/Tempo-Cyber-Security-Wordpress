# Tempo-Cyber-Security-Wordpress
This is just a temporary storage for lab 7 and 8 of homework assignment

# Project 7 - WordPress Pen Testing

Time spent: 7 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pen Testing Report Updated

### 1. (Required) Authenticated Stored Cross-Site Scripting (XSS) in YouTube URL Embeds

- [ ] Summary: 
  - Vulnerability types: XSS
  - Tested in version: 4.0-4.7.2
  - Fixed in version: 4.2.13
- [ ] GIF Walkthrough: wordpress1.gif, wordpress1.2.gif
- [ ] Steps to recreate: 
- [ ] Affected source code:
  - [Link 1]http://wpdistillery.vm/xss-youtube/
  
### 2. (Required) Authenicated Code Execution 

- [ ] Summary: 
  - Vulnerability types: Authenticated Code Execution
  - Tested in version: 3.7-5.0
  - Fixed in version: 5.0.1
- [ ] GIF Walkthrough: userAsnip.gif
- [ ] Steps to recreate: 
- [ ] Affected source code:
  - [Link 1]http://wpdistillery.vm/wp-admin/post.php?post=14&action=edit

### 3. (Required) Authenticated SQL injection

- [ ] Summary: 
  - Vulnerability types: 
  - Tested in version: 2.3.0-4.7.4
  - Fixed in version: 4.7.5
- [ ] GIF Walkthrough: sqli1.1.gif, sqli1.2.gif
- [ ] Steps to recreate: 
- [ ] Affected source code:
  - [Link 1]http://wpdistillery.vm/wp-admin/post.php?post=9&action=edit

### 4. (Optional) None

- [ ] Summary: 
  - Vulnerability types:
  - Tested in version:
  - Fixed in version: 
- [ ] GIF Walkthrough: 
- [ ] Steps to recreate: 
- [ ] Affected source code:
  - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

### 5. (Optional) None

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

GIFs created with  ...
<!-- Recommended GIF Tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

I mostly had a very rough time trying to make all of my 6 snips into .gif files because I didn't know how to initially make them work for submission on Units 7 & 8. Really sorry about this late issue Codepath. Have a great rest of your day and week. 

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
