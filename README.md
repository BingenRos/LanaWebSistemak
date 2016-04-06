# LanaWebSistemak
Datu basea DBSBingen@dbserver2016.cloudapp.net dago kokatuta, erabiltzaile bat sortuta dago, beharresko pribilegio guztiekin.
datu basearen egitura:

Lizentzia taula

| Field       | Type        | Null | Key | Default | Extra |
+-------------+-------------+------+-----+---------+-------+
| modeloa     | varchar(20) | YES  |     | NULL    |       |
| zenb        | int(11)     | NO   | PRI | NULL    |       |
| abaduramax  | double      | YES  |     | NULL    |       |
| modalitatea | varchar(30) | YES  |     | NULL    |       |
| kamara      | tinyint(1)  | YES  |     | NULL    |       |
| pisua       | int(11)     | YES  |     | NULL    |       |
| erabMail    | varchar(40) | NO   | MUL | NULL    |       |
+-------------+-------------+------+-----+---------+-------+

Erabiltzaile taula

+--------------+-------------+------+-----+---------+-------+
| Field        | Type        | Null | Key | Default | Extra |
+--------------+-------------+------+-----+---------+-------+
| erab         | varchar(20) | NO   |     | NULL    |       |
| pasahitza    | varchar(20) | NO   |     | NULL    |       |
| helbidea     | varchar(40) | YES  |     | NULL    |       |
| izenAbizena  | varchar(50) | YES  |     | NULL    |       |
| email        | varchar(40) | NO   | PRI | NULL    |       |
| jaiotzeUrtea | int(11)     | NO   |     | NULL    |       |
+--------------+-------------+------+-----+---------+-------+



Erabiltzaile bat sortuta dago erabiltzeko
erab = a
pasahitza = a

Erailtzaile honek hainbat lizentzia ditu sortuta.

Non sortu daitezke arazoak:
  Formularioetan zuriuneak hutzita
  formularioan, eskatzen den mota baino zerbait ezberdin ipintzen bada.
  kamara atalean bai,b,ez edo e ipintzea gomendagarria da.

Komentario bezala, datu basearen taula uste dut deskolokatzen dela formatu batzuetan. argazki bat ipiniko dut badaezpada  
