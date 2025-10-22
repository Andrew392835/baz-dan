INSERT INTO Producenci (nazwa, kraj)
VALUES 
  ('Apple', 'USA'),
  ('Samsung', 'Korea Południowa'),
  ('Xiaomi', 'Chiny');



INSERT INTO Produkty (nazwa, cena, producent_id)
VALUES 
  ('iPhone 14', 4999, 1),
  ('Galaxy S23', 4599, 2),
  ('Redmi Note 12', 1299, 3);


INSERT INTO Klienci (imie, nazwisko, email)
VALUES ('Anna', 'Kowalska', NULL);



INSERT INTO Ksiazki (tytul, autor_id)
VALUES ('Nieistniejąca książka', 99);



CREATE TABLE Logi (
  id_loga INT AUTO_INCREMENT PRIMARY KEY,
  komunikat TEXT,
  data_zdarzenia DATETIME
);



INSERT INTO Logi (komunikat, data_zdarzenia)
VALUES ('Pierwszy wpis do logów', NOW());
C
