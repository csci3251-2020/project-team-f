# This team has started yet...
 
 # Introduction

Hello! We are __team F__! Our team will do a total of __8 tasks__. There is a summary, if you want to know more, feel free to go to __task.md__ for more information and folder "issues" for the informations of every issues.

1. Start the issue - Go to issue tab and create a new issues for every tasks
1. Create a project board - Click project tab, use __Basic Kanban__ template to make three automations: _To Do_, _In progress_, _Done_
1. Set up readme.md - Set three headings: __Introduction__, __Code__ and __Contributors__, and write summary of project
1. Show team to the internet - update `https://csci3251-2020.github.io/(repo name)`, add a loop in folder "_stu" under __Contributors__, the loop go through the file in "stu" and show the information from file.
1. Keep checking - To check whether the issues are __all labeled__ in project, whether the __pulled requests__ are added in __proper columns__, and remind to include their __.md file in "_stu"__, and their __"hello" card __in project.
1. Write C code - write a simple code in __code.c__, set up a __GitHub Action__ with a workflow to run code
1. Get a status badge - update the `https://csci3251-2020.github.io/(repo name)`, edit __readme.md__ and highlight the code using __C syntax highlighting with markdown__
1. Promote your repo - look at the team's page: `https://csci3251-2020.github.io/(repo name)` , edit and include the repo last updated time using __site.time__, go to __csci3251-2020.github.io__ , edit and add the link, and request for review of __@chuckjee__


# Code
Will be added soon...

# Contributors
{% for s in site.stu %}
  <p>
   &emsp;>><img src="{{ s.image }}" height="50" width="50">
   @{{ s.user }} ({{ s.name }})
  </p>
  <p>&emsp;&emsp;>>{{ s.content | markdownify }}</p>
{% endfor %}

---
### Last Update:
<p> {{ site.time }} </p>
