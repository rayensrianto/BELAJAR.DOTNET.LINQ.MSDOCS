# BELAJAR.DOTNET.LINQ.MSDOCS
Rangkuman gue belajar LINQ dari dokumentasi nya Microsoft.

# LANGUAGE INTEGRATED QUERY (LINQ) (C#)
LINQ adalah teknologi yang mengintegrasikan antara query dengan bahasa C#.
Dulu, query terhadap data itu di tulis dengan sebuah string yang sederhana tanpa pemeriksaan saat di compile  dan tidak support dengan Intellisense.
Selain itu, kita juga harus mempelajari query language yang berbeda dari data source yang berbeda seperti SQL Server, Oracle, XML Documents dll.
Dengan LINQ, sebuah query adalah first-class language construct, seperti class, methods, event. Kita menulis query terhadap strongly typed collection of object menggunakan keyword dan operators yang familiar di bahasa C#.
Teknologi LINQ memberikan pengalaman query yang konsisten terhadap object (LINQ to Objects), realtional databases (LINQ to SQL), dan XML (Linq to XML)

Bagi developer yang menulis query, hal yang paling terlihat dari integrasi LINQ ini adalah query expression.
Query expression ditulis menggunakan sintaks query (query syntax). Dengan query syntax, kita dapat melakukan filtering, ordering, grouping pada data source dengan code yang minim. Kita juga bisa menggunakan pola query expre