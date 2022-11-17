# CMPG-323-OVERVIEW-34962913
Overview of CMPG 323 and all its projects

NB!! My student nuber for repository is incoorect it should be 34962913.

1 Project Structure for semester:
One OVERVIEW Repo (this repo) will be linked to all projcets and other repos that forms part of the CMPG 323 projects 2-5. //Name(CMPG-323-OVERVIEW-34962913)
For each project 2-5, I will create a repository, thus 5 different repositories not including the overview repository
Thus for project 2 there will be a repository called:  "34926913Project2V2"
     for project 3 there will be a repository called:  "Project3 Repo"
     for project 4 there will be a repository called:  "Project4 Repo"
     for project 5 there will be a repository called:  "Project5 Repo"
     for POE there will be a repository called: "POE"
     
The following diagram aims to explain how the projects and repositories will be integrated

![DiagramFF](https://user-images.githubusercontent.com/84916225/202378442-34a3ba22-3d97-449b-a248-3c4f25504e06.png)

2 Branching Strategy:
I will have a main or master branch and work directly on that branch.

3 .gitignore: 
I will use gitignore to ignore certain files when my projects are being commited. 
I will ignore files that are not part of my project or if it contains passwords.


 Credentials stored: 
 I will use gitignore to ignore the files that contains usernames and passwords, preventing them to be accessed by the public. I will use git-credential-store to store  password, protected by persmisions of the file system and save credentails in plaintext files on the cloud.


The link to Project 1 : https://github.com/users/Abrie282/projects/3

Tabular View:

![P1Tabular](https://user-images.githubusercontent.com/84916225/202381253-682b81d2-a34c-42c3-9207-f6b0475c96fb.jpg)


Status View:

![P1Status](https://user-images.githubusercontent.com/84916225/202381549-99c26d68-b26c-4645-8173-e698d09dce8a.jpg)

Linked Assessment View:

![P1LinkedAss](https://user-images.githubusercontent.com/84916225/202381909-917474eb-7d5d-49d1-bcd4-4ff4f7fda917.jpg)

Sprint View:

![P1Sprint](https://user-images.githubusercontent.com/84916225/202382344-6037217c-df36-4f89-82f3-35576cb148e7.jpg)

Date View:

![P1Date](https://user-images.githubusercontent.com/84916225/202382633-3067e574-fa10-483c-a659-77d23193c7d1.jpg)


The link to the repository for project 2: https://github.com/Abrie282/34926913Project2V2.git


My API works 100% locally and all the endpoints work with the methods created, but when I try it on the cloud I run into a 500 Internal Error and I have tried to solve this for a few days and could not get it to work.

As seen my initial commit for this repo was not 7 days ago, this is because I ran into alot of errors leading me to create new repo for project 2 each time. THus my first repo for project 2 was created more than 7 days ahead of the submission date.
I ended up with this repo as my final project 2 repo. And my student number ended up being incorrect it should be 34962913.


I have three different controllers: categories, zones and devices. They have their own methods as follows:

Categories have get - gets items from categories, post - adds items to categories, get, put and delete methods.
Devices have get - gets items from devices, post - adds items to devices, get, put and delete methods.
Zones have get - gets items from zones, post - adds items to zones, get, put and delete methods.

List of endpoints: 

Categories GET:    /api/Categories
          POST:    /api/Categories
          DELETE:  /api/Categories/{id}
          GET:     /api/Categories/{id}  
          PUT:     /api/Categories/{id}
          
 Devices  GET:     /api/Devices
          POST:    /api/Devices
          DELETE:  /api/Devices/{id}
          GET:     /api/Devices/{id} 
          PUT:     /api/Devices/{id}
         
  Zones   GET:     /api/Zones
          POST:    /api/Zones
          DELETE:  /api/Zones/{id}
          GET:     /api/Zones/{id}
          PUT:     /api/Zones/{id}
          
Endpoints 1 on Azure:

![APIEndpoints1 34962913](https://user-images.githubusercontent.com/84916225/202383462-51e0b7e7-ad07-4da3-8fa0-3a394d17bb08.png)

Endpoints 2 on Azure:

![APIEndpoint2 34962913](https://user-images.githubusercontent.com/84916225/202383574-58db3ab2-6f71-4b7e-8434-1aa6bad0eae2.png)







This is the link to my Project 3 repo: https://github.com/Abrie282/CMPG-323-34962913-Project3.git


This Readme will be used to describe project 3 and it's functionality.

The brancging strategy used: I cloned the repo onto my computer and worked on the main/master branch and commited the changes using github desktop.

This repo was not created 7 days ago, I had to create a new one and refork the original repo because I ran into an error that I could not fix for the longest time.

The Home page will include the Zones, Categories, Devices and Logout. Users can be registered and login.
Zones, Devices and Categories can be managed, thus added, deleted and or edited.

Home: 

![P3Home](https://user-images.githubusercontent.com/84916225/202387356-e32a6717-5ec8-4b95-8d7d-959f7611ad7a.jpg)

Users can login:

![P3login](https://user-images.githubusercontent.com/84916225/202387725-d7dafc2d-5b27-4629-877c-a29c74a59149.jpg)

Users can register:

![P3Register](https://user-images.githubusercontent.com/84916225/202388025-07a063ce-5bac-44f6-8cd6-3735c270c68f.jpg)

This is the link to my Project 4 repo: https://github.com/Abrie282/CMPG-323-Project-4-34962913.git

This repo will be used for project 4 of 323.RPA using Uipath and UiPath Studio
 
 The aim of this project is to perform UAT(user acceptance testing) on the web application that was created in project 3.
 
 The automation navigates to the web app and create, update, delete and view zones, categories and devices.
 The automation will also update and write to the excel file sheet "Test Results" based on if it was done  successfuly.

This is the link to my Project 5 repo: https://github.com/Abrie282/CMPG-323-Project-5---34962913.git

The report created from the data provided and imported into Power BI was separated into 3 pages.
The high-level metrics page, the device monitoring page, and the device registration page.



![Pages2](https://user-images.githubusercontent.com/84916225/200821796-7ddc59f2-88cf-4c3f-9c59-6850bbb45529.png)


The datasets were leaned and all duplicated were removed where it made logically sense. The data types of all the field were checked and fixed to the correct type if needed. In order to enhance the quality of the my visualizations I created a calculated column called StatusID where the id of an active device is = 1 and an inactive device = 0.I also created a key measure to enhance the data visualizations.


![StatusID](https://user-images.githubusercontent.com/84916225/200823417-6d56f538-3083-47ee-9989-58e07548be58.png)



The High Level Metrics page of the report provides a summarized view of all the important data that could have a large impact on decision making, according to me that would be the key visualizations of Devices per Category, Device Registered over a time period, Active vs Inactive Devices and the number of devices per category.


![HighLevel](https://user-images.githubusercontent.com/84916225/200824665-faf2460a-b448-4946-a05a-f92db7ad8768.png)



I created a visual for users to monitor the devices per category:

![DevicesPerCategory](https://user-images.githubusercontent.com/84916225/200825923-c783c77a-1973-44d3-ad63-473f0959cdca.png)



I created a visual for users to monitor the devices per zone:


![ActiveVSInactive](https://user-images.githubusercontent.com/84916225/200826848-9ba4dd86-f248-44fb-a12b-12c7ba9a1653.png)





I created a visual for users to monitor online devices versus offline devices: 


![DevicesPerZone](https://user-images.githubusercontent.com/84916225/200826332-921d4e05-f563-4ba2-a135-2c30855ed9aa.png)



These visualizations all formed part of the Device monitoring page, the full page view can be seen here:


![DeviceMonitoring](https://user-images.githubusercontent.com/84916225/200827472-a2401656-65ea-4468-b815-627152bc90ed.png)


The following is the Device Registration page which will be discussed in greater detail:


![DeviceReg](https://user-images.githubusercontent.com/84916225/200827978-06f275bb-ee3a-4a8b-8e32-3f1ccecae9f7.png)

I created a visual for users to see how many devices have been registered over a timespan:

![DevicesPerTime](https://user-images.githubusercontent.com/84916225/200828535-b539ce1c-a639-4b0b-96bd-54fad825a60b.png)

I created a visual for users to see how many categories of devices have been created: 
 

![DevicesPerCat](https://user-images.githubusercontent.com/84916225/200829025-f06ac169-e8cb-4d32-825c-e32112d454cc.png)

I created a visual for users to see how many zones contain registered devices on a timeline: 

![ZonesRegDev](https://user-images.githubusercontent.com/84916225/200829543-35f45221-37fd-4796-85ef-036b320b28ca.png)



Thereafter I created filters for the following: Filters that can be used and applied across pages to o filter the 
report based on device category, filter the report based on the device platform, filter the report based on the device zone and lastly to filter the 
report based on the device registration date:



![Filters](https://user-images.githubusercontent.com/84916225/200830415-21ae66b1-0fbe-49b3-a4ae-2876feaeda0e.png)



