//Creating table 
//Please change the jdbc connection according to your DB and add your DB jar file in lib according.

//Run create table query in your db

CREATE TABLE tradeStore (tradeId varchar(10),version int,counterPartyId varchar(10), bookId varchar(10),maturityDate DATE, createdDate DATE, expiredStatus varchar(10));
		