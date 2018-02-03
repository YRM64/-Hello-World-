# -Hello-World-
1st Project

This project ("Hello-World") is designed to introduce to developers, commercial retailers, and the general public a multi-platform 
storage container application that is versatile and multi-faceted in that it combines a micro-service-based .NET application platform with other containerized multiple
various versions of the .NET Core, and other ASP.NET Core images.  All images are designed to share at least one layer, including a base layer, saving
disk space, thereby, making the project more cost effective.  I have also chosen the .NET Core production platform because of the speed   the build 
at which the application builds.

Micro-services will be sharing this storage container with confidential application files, a file-sharing feature, a queue 
(to start a new function when a new item is received on queue), tables, templates, graphs/charts, services, object/blob storage, 
subscriptions, a README.md file, and allowing permissions for reading, writing, delete, list, add, create, update, process, 
including granting access to http, html, and https protocols.  In terms of development, the micro-service feature is autonomous, although,
all functions and implementations of the container work together, each application is deployed independently of one another, and each micro-service owns its own 
related domain data model and domain logic, which is based on a different set of data storage technologies, such as SQL or no SQL.  In other
words, a micro-services architecture deploys independently.  With Micro-services, you can scale out only what you need in terms of bandwidth power
instead of delegating processing power to un-needed functional areas of the application, thus saving hardware, and making the deployment
more cost-effective. A Micro-service feature provides for versatility in application design, a functionality that meets the demands of the 21st
century, and a very business-oriented approach to developing, building, and deploying applications.

In terms of policy, devices must include tokens with security credentials along with every message sent to the hub.  Also, in terms of
a .gitignore file, although this project requires the submission of a .gitignore file, in my storage container it won't be necessary 
with "Hello-World" because my files in the container are all confidential files. However, the file-sharing feature in the container
pertains to those files that are non-confidential, and are easily tagged as a file-sharing feature, and that is one of the unique designs 
of the storage container.  I felt it necessary to separate the two types of files to avoid accidentally sharing a file across the internet that shouldn't be shared; especially 
because of a possible breakdown in debugging or the user experiencing hacking issues.  A safe precaution to take is just to separate the 
two types of files to avoid any mishaps. In other words, the user has the option to include a .gitignore file, or to create a keybinding 
or rule to bypass any requirement written into the code or configuration.
