# About me

My name is Sylwia, and I’m a technical writer. I create, write, design, and explore. In most cases, this applies to the project and product documentation – I prepare templates and drafts, write content based on provided materials, delve into project nuances and details to better understand the purpose and usage, and then share my knowledge with the world. I wear many hats, as sometimes technical writers are considered copywriters, content designers, information architects, usability experts, and translators (with a focus on localization and inclusive language). After hours, my passion is linguistics (both English and Polish), cinematography, modern art, and psychology.

![alt text](https://scontent.fwaw3-2.fna.fbcdn.net/v/t39.30808-6/296100327_5897417550273197_5069724767594378578_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=6J6teHubQPkAX8YzoMc&_nc_oc=AQmXYFrT-vSAl1n-an0bIktFVG-tqDRBepZTQ9LJbygeK096IxA1ndbEHMie_B-jdXQ&_nc_ht=scontent.fwaw3-2.fna&oh=00_AfC7lYGCVjiUPpGwngBQF8o21lXdzyYEsuuU0UZYRG085A&oe=637249E4)


## Case study #1 (redesign)

Let me introduce you a project I worked on and I’m going to use it as an example to present my mindset on design and users well-being. 

I described the final product - a database in the form of a web application to be used by the HR department as well as the Sales department in case of a need to introduce candidates to customers. A solution to gather information on professional experience, skills, and competencies of employees with the possibility to generate a resume or CV; the solution can also be used to track the progress and performance of employees in their organization. 

I prepared manuals for two types of users: generic users (employees) and those of higher level (team managers and team leaders). 

The view designed for the generic users differs from what managers see. The employees of an organization fill in particular sections of their profiles. Some information is uploaded from an internal system (such as the name of the job’s position, seniority level, department, and supervisors) – it’s not editable. Sections such as Work experience, Education and language, Additional information on courses, certificates, honors and awards, Skills and technologies, Publications, Projects, and Endorsements are editable by the employees themselves. Additionally, there’s the About me section, where a person can write a few words of introduction. TMs and TLs can add to their employees’ profile information under the Cover letters section, for example, recommendations or a summary of the overall employee performance. Still, this is a part of the view prepared for employees. 

Personal profiles of TMs and TLs can be used for project recommendations and recruitment. But there are some extra options available for them to manage their teams and employees. Each TM and TL have an extended menu on the left side of the page with access to, among others, Dashboard, Employee search, Report & Analysis, Candidates (for recruitment purposes – recruitment within the organization that is in search of the future employees that can be outsourced to a customer). 

Based on my experience with this particular tool, I’d like to share my thought about the final product. Since I was not involved in the design process, I had no possibility to report my ideas. However, I believe some of my proposals might improve the user experience of the solution’s end-users. 

What’s important, I’m aware that the entire application development was preceded by a thorough analysis of the users’ needs. The below design changes serve the purpose of showing my way of thinking. 


I've decided to prepare for you a new view of the Employees search available in the tool. Let's first take a look at the product the way it was developed.

### Before

![alt text](https://i.ibb.co/m0Z7bVw/employees-search-before.jpg)


1.	**No alignment – misalignment** (filtering fields are of different sizes, arranged unevenly).
2.	**Filters are** ordered in a **messy** way (different types of information).
3.	**The Previous company field is unnecessary** (would you search for your employee by their last place of work?).
4.	The Clear button is first, then we have the Search button. **The ultimate goal is to search, not clear**.
5.	**The Star icon is used to search by employees added to favorites**. At first, I thought this was for adding set filters to favorites so that once filters are set, I could use them again in the future.
6.	The buttons: **Download XLS and Generate CV do not belong here**. Until the user clicks Search, these have no use (they operate with the search results).

The below *After* version is how I would change the view. See the description for more information.  

### After 

![alt text](https://i.ibb.co/bzrTFSD/employee-search-after-2.jpg)

1.	**The filtering fields are rearranged** – the distance between the fields is the same, and the filters are centered. 
2.	**The filters are arranged in order of the information**; first, we have filtering fields directly related to basic information on an employee – their name, job position, type of user (whether it’s a candidate or already employed person), and location. Below these, we have filters regarding competencies. 
3.	**The Previous company field is removed; not relevant**. 
4.	The buttons **Search and Clear changed their order** – Search comes first. 
5.	Let’s imagine that **the Star icon is used to add set filters to favorites and reuse those setting later, eventually**. 
6.	The **Download XLS and Generate CV buttons are moved to the lower section** (where the search results are displayed).


## Case study #2 (user guide)

Additionally, I’d like to present you with another project I worked on as an example of my human-centric approach. This time, I’m focusing on my favorite part of my technical writer’s job: creating user guides (also called manuals).

A user guide is a document helping to understand end-users how to navigate through a tool, system, app, and so on. It supports users with visual materials and text content; it’s an overview of the tool’s capabilities.

The project aimed at reorganizing the existing process of workflows and requesting at an organization (request management solution). The project has two sides: building workflows (Salesforce-based solution) within which users can request various needs (web application-based). 

A *builder* (or a *designer*) is a person who creates Workflows in Salesforce. Considering different processes and procedures, such a person prepares a form using customized elements from the toolbox. These items used to build a form have many extra options and settings and sometimes operate with some other elements in order to achieve a specified goal.

A *requester* is a person who fills in a form within a particular Workflow (for example, a business area). The user guide for this part of the project does not focus on how to provide information in the form, as it can vary depending on the request. It focuses on the process that the submitted request goes through – approval, rejection, need for updates on the requester’s side, and so on. 

What was challenging about the system was explaining to *builders* how particular toolbox elements work depending on their properties settings and how to fully understand the capabilities of their usage. 

The first stage was to introduce layouts of different objects for both types of users. The below figures show how specific interface elements are explained to the users. 

![alt text](https://i.ibb.co/QDjHKkz/navigation-panel-ug-for-requesters.jpg)
*The navigation panel and what it contains - from the manual for requesters*

***

![alt text](https://i.ibb.co/0Kf9kvf/layour-for-builders.jpg)
*An overview of a specific Workflow: functionalities and how they work from the manual for builders*

***

![alt text](https://i.ibb.co/TWsw24z/note-for-builders.jpg)
*Additional information in the green panel includes gifs for better understanding - from the manual for builders*

***

![alt text](https://i.ibb.co/PhDR77s/user-guide-for-builders-properties.jpg)
*Creating new Workflows: filling in the Properties tab - from the manual for builders*

***

