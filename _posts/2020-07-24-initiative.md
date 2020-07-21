---
layout: post
---

My first software development position was nothing like what I had pictured.
Like any young programmer in uni, I completely expected to work with a team of like-minded tech people in a nice
open room with bean bag chairs and string lights. Requirements would come to us and we'd churn out changes and MAKE things.

What actually happened was quite a bit different. I joined a team managing an instance of a monolithic Java application that about 8000 nurses used each day
in their work with Medicare and Medicaid patients.

The problem with this app being a monolith was that it was the singular integration point for a huge part of the IT department.
Every other team would have to use it's API's and various services.

Our team was responsible for *EVERY* single integration point.

I knew nothing about medical management or literally anything healthcare related.
The workspace was pretty tech-ish but so much of the entire enterprise was insanely corporate.
The management was great and the people were insanely nice and supportive, but it always seemed like nothing was going on.
Requirement hell would go on for sprint after sprint. Stories were closed half-way through because no one knew what to do with them.
People came and went so fast that their unique responsibilities were dropped on the next person in line.
And that responsibility could vary immensely from the next. So much fell upon random scrum teams.
Reporting, logging, app changes, new implementations, production support, database questions, medical management questions, etc, etc. 
The tech stack was quite large: SQL Server, Oracle, Tibco (Old Low-Code Tool), Java, Go, Teradata, random apps that used old obscure js frameworks, Jenkins script, Powershell, etc.

Now, in hind-sight, this was not the worst of environments to grow. The people in and around this team were extremely open and patient with junior devs.
The problem that I faced was complete confusion in regards of what to do and how to contribute.
Everyone was always very focused with their own tasks that they simply didn't have the bandwith to educate new devs.

At a certain point, I came to be a SME in regards to some of the API's and older application flow. 
What I ended up doing was very little. Essentially the bare minimum amount of work with a couple nice projects on the side to show that I was useful and had ideas. 
These ideas looked cool and helped grow my image but, all in all, they really never amounted to anything.
They fizzled out and sat in the Bitbucket repo for the rest of the time.  

I know now that what I should have done was take more control into my own hands. I was the SME. People came to me for guidance. 
I should have taken advantage of this and took more time to think through the project on a bigger level. 
You don't have to know the entire feature set of the project. Just think about the most common time-wasters or blockers that teams face. 
For example, in my current team, we were often getting asked if we could lookup in our DB whether or not some data was there. 
I was inspired to create a small app that with a search tool with a super basic Go backend API that allowed these teams to see this data whenever they want. 
This allowed us to skip multiple meetings per week that took up a couple hours of our team's time and even more when more than one person joined those calls. 

All in all, it comes down to fighting complacency. Don't let a cushy job get the better of you.
Decide if you wanna stay. If you do, think of ways to improve your project, team, or workflow. If you don't... Well you already know.

