
## INSTALLATION

1. CLONE THE REPO

```bash
  git clone https://github.com/Git-Utkarsh/SchoolManagementSystem.git
```
2.INSTALL REQUIRED MODULES
```bash
    pip install -r requirements.txt
```
3. CREATE DB
```bash
    mysql > create database if not exists schooldb;
    mysql > use schooldb;
    mysql > create table class(Reg int(20) primary key NOT NULL,   
    Name Varchar(30) NOT NULL, Class Varchar(12) NOT NULL,
    > Sec Varchar(5) NOT NULL,Phone Varchar(20) NOT NULL,Father   
    Varchar(30) NOT NULL,
    > Mother Varchar(30) NOT NULL ,Address Varchar(40) NOT NULL);

    mysql > create table teacher(ID int(20) primary key NOT NULL, 
    Name Varchar(30) NOT NULL, Subject Varchar(12) NOT NULL,
    > Phone Varchar(20) NOT NULL, Salary Varchar(20));
```

