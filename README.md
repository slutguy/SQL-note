## SQL
* #### ADC
Show all database   |show databases;    
| ----------------- | ------------------- |
Show now database   |select database(); 
Creat the databases |create database[if not exists][default charset][collate]
delete database     |derop database[if exists]
use database        |use #someone#  

* #### Table motion
Search all table of database
>show tables;

show the types

`desc #tables name#`

show create the table

`show create table #name#`

create the table

* `create table first #name# (`
* `id int comment '#id#',`  
* `age int comment'#age#',` 
* `gender varchar(1) comment '#someone#',`
* `) comment '#someone#';`

Type    | Size    | SIGNED Scope | UNSIGNED Scope | Describe
 ----- | ------- | ------------ | ------------ | ----- 
 TINYINT | 1byte  | (-128,127) | (0,255) | little int
SMALLINT | 2bytes | (-32768,32767) | (0,65535) | large int
MEDIUMINT | 3bytes | (-8388608,8388607) | (0,16777215) | large int
INT&INTEGER | 4bytes | (-2147483648,2147483647) | (0,4294967295) | large int
BIGINT | 8bytes | (-2^63, 2^63-1) | (0,2^64-1) | large int 
FLOAT | 4bytes | (-3.402823466 E+38,3.402823466351 E+38) | 0&(1.175494351 E-38,3.402823466 E+38) | float
Double | 4bytes | - | - | -
Decimal | 8bytes | - | - | -


