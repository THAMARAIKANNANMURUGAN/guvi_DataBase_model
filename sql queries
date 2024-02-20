// Use DBML to define your database structure
// Docs: https://dbml.dbdiagram.io/docs

Table Zen_Class {
 id integer [primary key]
 class string
dashborad string
task string
ineterviewtask string


}
 Table class{
id integer [primary key]
joinclass Boolean
title string
startingtime varchar
contents string
aditionalclass array
 }

Table aditionalclass{
  id integer [primary key]
  topic varchar
}
Table dashboard{
  id integer [primary key]
  pendingtask integer
  completedtask integer

}
Table contents{
  id integer [primary key]
  mentor_name string
  topic strin

}



 Ref:class.id > Zen_Class.class
 Ref:dashboard.id > Zen_Class.dashborad
 Ref: aditionalclass.id > class.aditionalclass
Ref: contents.id > class.contents


