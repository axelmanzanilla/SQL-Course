# SQL-Course
## Exercise 2
### 2.1 Crear una tabla llamada Libros en la base de datos prueba1, que contenga las siguientes columnas:
* id (número entero)
* title (texto)
* author (texto)
* publisher (texto)
* publication_date (tipo fecha)
* pages (número entero)
* price (número decimal)
* genre (texto)
### 2.2 Insertar la siguiente información en la tabla:
```sql
INSERT INTO books (id, title, author, publisher, publication_date, pages, price, genre) VALUES
(1, 'To Kill a Mockingbird', 'Harper Lee', 'J.B. Lippincott & Co.', '1960-07-11', 281, 10.99, 'Fiction'),
(2, '1984', 'George Orwell', 'Secker & Warburg', '1949-06-08', 328, 12.99, 'Science Fiction'),
(3, 'Pride and Prejudice', 'Jane Austen', 'T. Egerton', '1813-01-28', 279, 9.99, 'Fiction'),
(4, 'The Catcher in the Rye', 'J.D. Salinger', 'Little, Brown and Company', '1951-07-16', 277, 11.99, 'Fiction'),
(5, 'The Great Gatsby', 'F. Scott Fitzgerald', 'Charles Scribners Sons', '1925-04-10', 180, 10.49, 'Fiction'),
(6, 'Moby-Dick', 'Herman Melville', 'Harper & Brothers', '1851-10-18', 635, 14.99, 'Fiction'),
(7, 'The Odyssey', 'Homer', 'Penguin Classics', '1999-01-01', 541, 12.49, 'Fiction'),
(8, 'Brave New World', 'Aldous Huxley', 'Chatto & Windus', '1932-08-30', 268, 12.99, 'Science Fiction'),
(9, 'The Origin of Species', 'Charles Darwin', 'John Murray', '1859-11-24', 502, 16.99, 'Non-Fiction'),
(10, 'A Brief History of Time', 'Stephen Hawking', 'Bantam Books', '1988-04-01', 256, 13.99, 'Non-Fiction'),
(11, 'The Universe in a Nutshell', 'Stephen Hawking', 'Bantam Books', '2001-11-06', 216, 15.99, 'Non-Fiction'),
(12, 'I, Robot', 'Isaac Asimov', 'Gnome Press', '1950-12-02', 253, 11.99, 'Science Fiction');
```
### 2.3 Realizar las siguientes peticiones a la base de datos:
* A Uriel le  gusta la decada de los 50, ayuda a Uriel a encontrar libros que se encuentren en esa decada.
* A Pablo le gusta la lectura ligera, ayudale a encontrar libros con menos de 250 páginas.
* María quiere comprar libros del autor Stephen Hawking, muestra los libros que sean de ese autor.
* Juan es una persona soñadora que le gusta la ciencia ficción, muestra todos los libros que no sean de "No ficción".
* Karla quiere comprar un libro pero no tiene mucho dinero, su presupuesto es de 10 dolares, pero si el libro es de su autor favorito (Stephen Hawking) no le importa gastar un poco más, por lo que su presupuesto es de 15 dolares, muestra los libros que cumplan con esa condición.
