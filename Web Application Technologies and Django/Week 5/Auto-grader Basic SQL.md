`CREATE TABLE Ages ( 
  id INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL UNIQUE,
  name VARCHAR(128), 
  age INTEGER
);`
<br>
<br>
<br>
`DELETE FROM Ages;
INSERT INTO Ages (name, age) VALUES ('Olaoluwapolorimi', 16);
INSERT INTO Ages (name, age) VALUES ('Tegen', 33);
INSERT INTO Ages (name, age) VALUES ('Jayda', 14);
INSERT INTO Ages (name, age) VALUES ('Cathal', 15);
INSERT INTO Ages (name, age) VALUES ('Kiera', 21);`

<br>
<br>
<br>
`SELECT hex(name || age) AS X FROM Ages ORDER BY X`;

<br>
<br>
<br>
41696C6964683330
