# Grav Course Hub Skeleton

[![Demo](https://img.shields.io/badge/Demo-CourseHub-blue.svg?style=flat-square)](http://demo.hibbittsdesign.org/grav-course-hub-bootstrap/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://github.com/hibbitts-design/grav-skeleton-course-hub/blob/master/LICENSE)

[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/hibbitts-design/grav-skeleton-course-hub)

### Grav Course Hub is an open source project intended to help tech-savvy instructors enhance the learning experience for their students by providing multi-device delivery and a collaborative workflow not present in their current Learning Management System (LMS). As an open platform under the full control of the instructor, a broader choice of online course components can be integrated into the Course Hub to help reach unmet pedagogical goals.

Built with the modern flat-file CMS Grav ([https://getgrav.org/](https://getgrav.org/)), the multi-device ready Grav Course Hub can partner with your existing LMS, where it serves as an alternative and customizable front-end to any required LMS elements for your students. With this approach, instructors have the freedom to move beyond the confines of the LMS while sensitive student data remains located within your institutional or organization’s LMS.

Content in Grav is stored and maintained as individual files rather than inside a database, so services such as [GitHub](https://github.com/) and [GitLab](https://gitlab.com/) (which can be hosted on your own server) can be easily partnered with your Course Hub for open collaboration and version control. Being file-based also means that instructors have their choice of tools for editing their Course Hub content, and site updates can be performed in as little as one button press.

**Table of Contents**  
[Why Use the Grav Course Hub Project?](#why-use-the-grav-course-hub-project)  
[Student Experience Goals](#student-experience-goals)  
[Instructor Experience Goals](#instructor-experience-goals)  
[Course Hub Screenshot](#course-hub-screenshot)  
[Course Hub Highlights](#course-hub-highlights)  
[Quick Install (Web server only)](#quick-install-web-server-only)  
[Recommended Install (Desktop + Server)](#recommended-install-desktop--server)  
[Page Templates](#page-templates)  
[Site Structure](#site-structure)  
[Site Configuration](#site-configuration)  
[Page Header Options](#page-header-options)

## Partnering your LMS with the Grav Course Hub

### Why Use the Grav Course Hub Project?
* To make online course materials more open and accessible
* To support collaboration and version control of online course materials
* To integrate a broader range of online course materials
* To provide multi-device access for online course materials
* To more quickly and easily update online course materials

### Student Experience Goals
  * Engaging
  * Organized
  * Relevant
  * Convenient
  * Enjoyable

### Instructor Experience Goals
  * Controllable (i.e. manageable)
  * Pliable (i.e. flexible)
  * Efficient
  * Portable (i.e. platform agnostic)
  * Enjoyable (hey, us instructors are people too...)

### Course Hub Screenshot
![Course Hub Screenshot](/assets/screenshot.jpg)  
_Figure 1. Example Grav Course Hub website, with GitHub collaborative page editing enabled.  Explore an example **single** course site at [demo.hibbittsdesign.org/grav-course-hub/](http://demo.hibbittsdesign.org/grav-course-hub/) and a **multiple** course site at [demo.hibbittsdesign.org/grav-multi-course-hub/](http://demo.hibbittsdesign.org/grav-multi-course-hub/)._

### Course Hub Highlights
* A complete ready-to-run Grav package (open source)
* Blog-format, with 'featured' (sticky) posts
* [Single course](http://hibbittsdesign.org/demo/grav-course-hub-bootstrap/) per Hub, [multiple courses](http://hibbittsdesign.org/demo/grav-multi-course-blog-hub/) per Hub or even [multiple course sub-sites](http://hibbittsdesign.org/demo/grav-multi-course-pages-hub/) (blog + multiple pages per course) per Hub
* Optional important reminders & class preparations areas
* Hub pages can be easily added/removed/changed
* Uses [Markdown](https://daringfireball.net/projects/markdown/) for streamlined cross-platform content
* Image header area above Hub navigation bar
* Sidebar is a simple markdown file, which can also contain HTML
* URL flag to only display page content (for display within LMS). For example, [http://demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/onlydisplaypagecontent:true](http://demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/onlydisplaypagecontent:true)
* External links are automatically opened in a new Tab/Window
* Built-in support for entire Hub to be collaboratively maintained on GitHub or GitLab (for local hosting)
* Since everything is built with Grav it can be _entirely_ customized

To learn more about how to most effectively use the Grav Course Hub, visit [hibbittdesign.org](http://hibbittsdesign.org/blog/)

## Grav Course Hub Installation  

### Quick Install (Web server only)
**Pre-flight Checklist**  

1. Confirm Web server PHP version (PHP 5.5.9 or higher)
2. Web server login credentials (username and password)

**Installation Steps**  

1. Download the ready-to-run [Course Hub Skeleton Package](http://hibbittsdesign.org/blog/downloads/grav-skeleton-course-hub-site.zip)
2. Unzip the package onto your desktop  
3. Copy the entire Grav Course Hub folder to your Web server  
4. Point your browser to the Web server folder  
5. Create your site administrator account when prompted  
6. And you're done! (press the ![Right Arrow Circle Icon](/assets/fa-arrow-circle-right.png) icon in the Admin Panel to preview site)

### Recommended Install (Desktop + Server)
With the flat-file (no database) nature of Grav, there are lots of benefits of installing Grav on your computer and then having your site files mirrored onto a Web server:
* Always have access to your site, regardless of Web server status
* Develop and test changes to your site privately without any downtime of the live site
* Store your site files on a Git service (i.e. GitHub) to better track your development and enable anywhere, anytime editing of your site
* Enable others (i.e. students, fellow instructors, colleagues, etc.) to collaboratively contribute to the site, including both site content _and_ code  

![Grav recommended install using Grav, GitHub, and Deploy to support a flipped-LMS approach](/assets/flipped-lms-grav-github-automatic-deployments.png)  
_Figure 2. Grav recommended install using Grav, GitHub, and and automatic deployment service to support a flipped-LMS approach._

**Pre-flight Checklist**  

1. Confirm Web server PHP version (PHP 5.5.9 or higher)  
2. Web server login credentials (username and password)  
3. Download and install MAMP   ([https://www.mamp.info/](https://www.mamp.info/))  
4. Git server account (e.g. GitHub ([https://github.com/](https://github.com)) or local GitLab or Gogs app, etc.)  
5. Download and install GitHub Desktop ([https://desktop.github.com/](https://desktop.github.com/))  
6. Automatic deployment service (e.g. Deploy ([https://www.deployhq.com/](https://www.deployhq.com/)) or Buddy ([https://buddy.works/](https://buddy.works)))  

**Desktop Installation Steps**  

1. Download the ready-to-run [Course Hub Skeleton Package](http://hibbittsdesign.org/blog/downloads/grav-skeleton-course-hub-site.zip)
2. Unzip the Grav package onto your desktop
3. Create a folder called 'MAMP Websites' in your 'Documents' folder
4. Copy the _entire_ Grav folder into your 'MAMP Websites' folder
5. Launch MAMP
6. Change the 'Document Root' MAMP preferences setting to the 'MAMP Websites' folder (within 'Documents')
7. Press the MAMP 'Start Servers' button
8. Enter 'localhost:8888' as the URL in your Web Browser
9. Choose the displayed Grav folder name
10. Create your site administrator account when prompted
11. And you're done! (press the ![Right Arrow Circle Icon](/assets/fa-arrow-circle-right.png) icon in the Admin Panel to preview site)  

Once you have confirmed that Grav is running locally on your computer, the final step is to create a Git server repository to store your site files and setup an automatic deployment service to push any changed files to your Web server. An example step-by-step walkthrough this process is available in the article [Using Grav with GitHub Desktop](http://hibbittsdesign.org/blog/posts/using-grav-with-github).

## Grav Course Hub Details  

### Page Templates
* Blog template (blog.html.twig)
* Important reminders template (important_reminders.html.twig)
* Weekly preparations template (preparations.html.twig)
* Blog item template (blog_item.html.twig)
* Item template (item.html.twig)
* Page with Sidebar template (sidebarpage.html.twig)
* Full width Page template (fullwidthpage.html.twig)
* Sidebar template (sidebar.html.twig)

### Site Structure

```
/user
  - /pages
    - /01.blog | blog.html.twig and blog_item.html.twig
      -/_important-reminders | important-reminders.html.twig
      -/_class-preparations | class-preparations.html.twig
      -/week-01 | item.html.twig
      -/week-02 | item.html.twig
      - etc..
    - /02.resources | sidebarpage.html.twig
      -/sidebarpage.md
    - /03.syllabus | fullwidthpage.html.twig
      -/fullwidthpage.md
    - /sidebar | sidebar.html.twig
        -/sidebar.md
    - /headerimage | default.html.twig
        -/default.md
    - /footer | default.html.twig (Course Hub Bones theme element)
        -/default.md
    - /logo | default.html.twig (Course Hub Bones theme element)
        -/default.md
    - /mobilemenu | default.html.twig (Course Hub Bones theme element)
        -/default.md
```

### Site Configuration
The 'site.yaml' file located in the '/user/config/' folder contains the following default values:
```
title: CPT-363
metadata:
    description: 'A short description of your course would go here'
displaymenuentries:
    enabled: true           # display of additional menu entries
menu:                       # menu entry for adding external sites/tools
    - text: Grav
      icon: arrow-circle-right
      url: http://getgrav.org/
icon:                       # default Font Awesome icons for preparation and post entries
    post: calendar-o
gitrepo:
    editlinklocation: none    # menu | page | none
    editlinkicon: github
    editlinktext: Edit this Page
    edittreeurl: https://github.com/hibbitts-design/grav-skeleton-course-hub-site/edit/master/user/pages/
twittertimeline:
    enabled: false          # display of Twitter timeline on sidebar
    url: https://twitter.com/hibbittsdesign/lists/cpt-363
    text: A Twitter List by hibbittsdesign
    height: 700
hidehomemenulink: false     # suppress Home menu link
```

| Setting | Child Setting | Description                                                                                                            |
|---------|---------------|------------------------------------------------------------------------------------------------------------------------|
| title   |               | The course number/id, to be displayed at the top of every page.                                                      |
| metadata  |  description | The short description of the course hub site.                                       |
| displaymenuentries  |  enabled | Can be set to `true` or `false`. When set to `true`, all defined menu items are added to the navbar.                                       |
| menu  |  text | Text label for an external link to be included on navbar.                                       |
| menu  |  icon | Font Awesome icon code for an external link (optional).                                        |
| menu  |  url | URL for an external link. |                                    
| icon  | post          | Change the default Font Awesome icon for the weekly blog posts (i.e. weekly summaries).           |
| gitrepo  | editlinklocation       | Can be set to `page`, `menu` or `none`. When set to `page` or `menu`, it will display the Git repository edit page link to your Git repo in the indicated location. |
| gitrepo  | editlinkicon       | Set the Font Awesome icon for the Git repository edit page link. |
| gitrepo  | editlinktext       | Set the text for the Git repository edit page link. |
| gitrepo  | edittreeurl          | Set the Git tree URL by which your site's content is based. Generally the Git repo your site's content is pulled from.            |
| twittertimeline  | enabled       | Can be set to `true` or `false`. When set to `true`, it displays the Twitter timeline on your sidebar. |
| twittertimeline  | URL       | The URL of the Twitter timeline you want to embed on your sidebar. |
| twittertimeline  | text       | The text label of the Twitter timeline you want to embed on your sidebar. |
| twittertimeline  | height       | The height of the Twitter timeline you want to embed on your sidebar. |
| hidehomemenulink  |       | Can be set to `true` or `false`. When set to `true`, the Home menu link in the navbar is not displayed.|

##Page Header Options

### Page Options for Blog Items
Blog item pages support the following additional options:
```
icon: users             # optional Font Awesome icon for page title
header_image: false     # display of header image located within page folder
continue_link: false    # display entire post on blog listing page
taxonomy:
  tag: Featured         # setting to make post 'sticky' (i.e. remain at top)
hidefrompostlist: true  # hide post from blog index
```

### Page Options for All Pages
All pages support the following additional options:
```
hidegitrepoeditlink: true    # hide Git Repository edit link for this page
gitrepoeditlinkurl: https://github.com/hibbitts-design/grav-skeleton-course-hub/tree/master/pages/01.home   # to override the automatically calculated Git Repository URL
hidepagetitle: true     # hide the display of the title of this page
```
---
