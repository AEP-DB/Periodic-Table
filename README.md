Periodic-Table
==============
You need to have mysql installed on your machine to use this application.

After installing mysql you need to create following database and tables in them by running this commands in mysql.

Commands to be runned :
create database periodictable;

use periodictable;

create table periodictable (atm_name varchar(20),atm_no int(2),symbol varchar(3),atm_mass int(3),category varchar(12),valency int(2),block varchar(10));

Initially the periodic table will contain no record, you can add new elements to it through this application or for intial stages just run following commands in mysql :

insert into periodictable values ('Hydrogen',1,"H",1,"gas",1,"s");

insert into periodictable values ('Helium',2,"He",4,"noble gas",0,"p");

insert into periodictable values ("Lithium",3,"Li",7,"metal",1,"s");

insert into periodictable values ("Beryllium",4,"Be",9,"metal",2,"s");

insert into periodictable values ("Boron",5,"B",11,"metalloid",3,"p");

insert into periodictable values ("Carbon",6,"C",12,"Non-metal",4,"p");

insert into periodictable values ("Nitrogen",7,"N",14,"Non-metal",5,"p");

insert into periodictable values ("Oxygen",8,"O",16,"Non-metal",2,"p");

insert into periodictable values ("Flourine",9,"F",19,"Non-metal",1,"p");

insert into periodictable values ("Neon",10,"Ne",20,"noble gas",0,"p");

insert into periodictable values ("SOdium",11,"Na",23,"metal",1,"s");

insert into periodictable values ("Magnesium",12,"Mg",24,"metal",2,"s");

insert into periodictable values ("Aluminium",13,"Al",27,"metal",3,"p");

insert into periodictable values ("silicon",14,"Si",28,"Non-metal",4,"p");

insert into periodictable values ("phosphorous",15,"P",31,"Non-metal",3,"p");

insert into periodictable values ("sulphur",16,"S",32,"Non-metal",2,"p");

insert into periodictable values ("chlorine",17,"Cl",35,"Non-metal",1,"p");

insert into periodictable values ("argon",18,"Ar",40,"noble gas",0,"p");

insert into periodictable values ("Potassium",19,"K",39,"metal",1,"s");

insert into periodictable values ("calcium",20,"Ca",40,"metal",2,"s");

insert into periodictable values ("iron",26,"Fe",56,"metal",2,"d");

insert into periodictable values ("Copper",29,"Cu",63,"metal",2,"d");

insert into periodictable values ("zinc",30,"Zn",65,"metal",2,"d");

insert into periodictable values ("silver",47,"Ag",18,"metal",1,"d");

insert into periodictable values ("tungsten",74,"W",184,"metal",4,"d");

insert into periodictable values ("platinum",78,"Pt",195,"metal",5,"d");

insert into periodictable values ("gold",79,"Au",197,"metal",2,"d");

insert into periodictable values ("mercury",80,"Hg",201,"metal",2,"d");

insert into periodictable values ("lead",82,"Pb",207,"metal",2,"p");

insert into periodictable values ("krypton",36,"Kr",84,"noble gas",0,"p");

insert into periodictable values ("xenon",54,"Xe",131,"noble gas",0,"p");

Now you are ready to use the applications.
