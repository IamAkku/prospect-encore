# PROSPECT-ENCORE
prospect encore analysis in which admin or user can login and they can change there password, reset it, search prospect priority and by using prospect id.
 Module-1: 		Monitor Module (Showroom emplyees)

1)	Login
2)	Add New Prospect
3)	View All Prospect
4)	Update Prospect
    		a)-Phone, b)-Model, c)-Colour, d)-Priority
5)	Search
  		a)By Priority b)Prospect Id
6)	Change Own Password
6)	Signout


Module-2: 		Admin Module

1)	Login
2)	Create User Account
  		a)Monitor  b)Admin
3)	View All Users(Employees)
4)	View All Prospects
5)	Change Password
    		a)Self   b)Others
6)	Search Prospect
    		a)By Priority b)Prospect Id
7)	Activiate/Deacticate Account
8)	Signout


 
## PREQISITES
 
#Use the following tables for data storage

create table employee
(  userName varchar(45) primary key,
   userPass text,
   userType text,
   fullName text,
   phone text,
   email text,
   status text
);

insert into employee values('E001', 'password' , 'admin' ,
         'kuldeep, '8512099003',
          'kuldeep@gmail.come','activated');


create table prospect
(
   prospId 			int 		primary key auto_increment,
   prospName 		varchar(45),
   prospPhone 		varchar(45),
   prospAddress 	varchar(45),
   interestedModel 	varchar(45),
   interestedColor 	varchar(45),
   dateOfVisit 		varchar(20),
   priority 			varchar(45)
);

# INSTALLLATION 
  install pycharm on local desktop, install Numpy, install matplotlib, install pandas, install xlrd,insatll openpyxl, install seaborn via command prompt.
  
## RUNNING
  copy the deployed github code , open it in pycharm and click run.
