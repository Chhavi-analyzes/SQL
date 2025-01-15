show tables; # to show the tables in your database
desc sales    # info about the table 
select * from sales # * means that you want everything from the table and from "name of the table required"
select "headers name" from 'table name': if you want to see selected rows only 
ctrl+ enter : to run the command 
HOW TO ADD A NAME?
select SaleDate, Amount, Boxes, Amount/boxes '**amount per box**' from sales;

HOW TO IMPOSE ANY CONDITION ?
select * from sales
where amount > 10000;
order by amount /desc   (to arrange data in increasing or decreasing order acc. to 
