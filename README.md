# Roommate-Recruitment
Roommate Recruitment (RR) Website

Overview of Applica on
Roommate recruitment (RR) is the website that allows the target group in need to choose preferred roommates. The main purpose of RR is to provide a pla orm where users post and also find a rac ve posts under four dis nct categories (area, flat name, rent prices, room capacity) and post comments or apply to join under the posts they are interested in. The site allows users to have more autonomy in finding roommates in the case of ren ng student accommoda on, as most student accommoda on is randomly arranged.
We set up the site to make it easier for students at the University of Liverpool. When using Facebook, you can see that there are groups of University of Liverpool students looking for flatmates, where users post informa on about their flat and their flatmates in general. However, Facebook does not categorize the posts and show if there are any new roommates currently in the group. RR's original inten on was to present the informa on to users in a more efficient way so that they could filter the stream themselves and see the number of people under the post is full or not. We want the site to be available to all students at the University of Liverpool. Perhaps it could be made available to all UK universi es in the future, the intended audience for the website includes but is not limited to the U.O.L.

2.0 Achievements of Objec ves
The Roommate Recruitment (RR) is a great system, and it consists of six different subsystems and other addi onal features. The project team created a mul -user database applica on complete with a fully func onal server and web-based client applica ons. The webpages are wri en in HTML, JavaScript.
The RR system has met all requirements and main mission objec ves men oned in the requirements specifica on. All queries used and reports produced by the system fulfill the specified requirements. The database structure has been slightly modified based on design specifica ons. But func onality closely reflects it.
However, due to the  me constraint on the project, we failed to complete the recommenda on algorithm which used to sor ng posts and used vacancy as an alterna ve. As well as autofill data and version control.

2.1 Account Management
The Account Management system includes account registra on and login. Users are required to use their university email and strong password when registering an account. The valida on code will be sent to the email user has filled in. Registra on can only be completed a er entering the verifica on code. When registering an account, we also provide a variety of personalized avatars to choose from.

2.2 Post and Comment Management
The Post and Comment Management system is the core component of the whole system. It manages all the opera ons (create, edit, delete and apply for entering a room group) with post and related comments. Users are restricted to edit their posts and comments only. In the database design here, foreign keys are used to ensure comments are related to posts and users. If the related post is deleted, all the comments under this post will also be deleted.


2.3 Search and Si ft Engine
Search and si  engines are designed to help user to si  out their interes ng posts efficiently and precisely. Users can use searching boxes by selec ng their preference condi ons such as area, flat, and price interval. The engine will simply traversal and sift  out those posts under these condi ons from the database [5].
 
2.4 Personal Informa on Management
Users can set and edit their personal informa on like avatar, religion, gender, na onality, sexual orienta on, etc. Founda onal informa on cannot be null but op onal informa on can. It is worth no ng that the username is unique and cannot be edited. This component is related to the user profile.

2.5 System Security
To protect user informa on, a regular expression is used to check if the user's password is a strong password which must contain at least one of "_", "-", "+", "@", one numerical number, and the length must be between 8 and 20 characters.

2.6 Database Design and Management
The Roommate Recruitment system uses MySQL as its database. The database contains six tables (Figure 4). The physical data model is shown as well that the blue line indicates the rela on between user and other tables and the red line is to the
 
