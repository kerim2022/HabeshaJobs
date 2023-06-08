# HabeshaJobs  
![unnamed](https://github.com/kerim2022/HabeshaJobs/assets/111186592/7b1c76a7-86db-4e46-8bf9-3d6ba0b1bd4b)  
A job searching website that helps employers fill vacant positions and individuals find the right job of their dreams particularly, in Ethiopia. There are many different online job portal systems in Ethiopia, but they have many limitations like Recruitment Agencies have Limited Choices, They have no screening. Anyone can sign up for a profile and apply for a job and They’re ineffective for high-level positions. Because they have no screening process, we would like to solve these problems in our portal called Habeshajobs.  
## 1. Architecture  
We use SERVLETS to handle HTTP client requests, SERVLETS are an effective replacement for CGI scripts. They provide a way to generate dynamic documents that are both easier to write and faster to run. Servlets also address the problem of doing server-side programming with platform-specific APIs: they are developed with the Java Servlet API, a standard Java extension.  
![unnamed](https://github.com/kerim2022/HabeshaJobs/assets/111186592/b486dc3a-2191-456f-b81c-8bfc70814be2)
## 2. APIs  
In addition to the Session object, there are a few more classes that we use for servlet development.  
| Description                | Class                              |  
| -------------------------  | ---------------------------------- | 
| httpsessioncontext         | The httpsessioncontext is the object that contains all existing and valid sessions. The http session context can be obtained by calling get Session Context () on the Session object. The Http Session Context lets you find other Session objects by their IDs and list the IDs of all valid sessions. |   
| HttpSessionBindingListener | HttpSessionBindingListener is an interface that can be implemented by objects placed into a Session. When the Session object is invalidated, its contained values are also removed from the system. Some of these values may be active objects that require cleanup operations when their session is invalidated. If a value in a Session object implements HttpSessionBindingListener, then the value is notified when the Session is invalidated, thereby giving the object a chance to perform any necessary cleanup operations. | 
## 3. Data Modeling  
![unnamed](https://github.com/kerim2022/HabeshaJobs/assets/111186592/2c614df0-d13d-4eff-a508-a97500540c02)  
## 4. Progress  
This week, we were more focused on the technical aspects of our portfolio project and that some of our progresses and activities went as planned and some of them went far behind to none from our plan due to the fact that parts of the project demands studying new languages and tools. Therefore we would rate our progress as 6 out of 10.  
## 5. Challenges  
Learning new frameworks/technologies: Django, HTML, CSS, JavaScript, Docker, PHP. This will be solved by taking the time to study all the necessary materials from the alx program and other supplementary resources from different sources.  
## 6. Screenshots  
![unnamed](https://github.com/kerim2022/HabeshaJobs/assets/111186592/4f4e991d-e9c2-42b7-86bd-e795521d112b)
![unnamed](https://github.com/kerim2022/HabeshaJobs/assets/111186592/8e12c317-88da-408f-aec2-5ffdf048a5ff)

