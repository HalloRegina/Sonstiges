Was brauchen wir wir brauchen
-----------------------------------------------------------------------------------------------------------------------------
Netbeans PHP 
-----------------------------------------------------------------------------------------------------------------------------
XAMPP
-----------------------------------------------------------------------------------------------------------------------------
Chrome
-----------------------------------------------------------------------------------------------------------------------------
Notepad++
-----------------------------------------------------------------------------------------------------------------------------
MySQL Workbench -->
-> Generate Insert Statments for Tables 
-> Generate Drop Schema 
-> Include Model attached scripts
-----------------------------------------------------------------------------------------------------------------------------
Suche ohne Ergebniss 
--> 
if ($stmt->rowCount() == 0) {
}
-----------------------------------------------------------------------------------------------------------------------------
Keine Eingabe
->
if ($_POST['company'] == '') {
  echo 'Leeeeeeeeeeeeeer';
}

-----------------------------------------------------------------------------------------------------------------------------
select Date:
SELECT *
FROM date
WHERE SUBSTRING(Date, 4, 2) = MONTH(CURDATE())
AND
SUBSTRING(Date, 7, 4) = YEAR(CURDATE());

