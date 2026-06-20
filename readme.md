Library Management System for Machakos Training College

Database-Machakos Training College
Database tables:1.Books
                2.Authors
                3.Students
                4.Borrowing
                5.Returns

1. Books:-
          a)Book_id(pk)
          b)Book Title
          c)Author_id(fk)
          c)Publication Year
          d)Number of copies available

2. Authors:-
          a)Author_id(pk)
          b)Author name
          c)Email
          d)Phone number

3. Students:-
          a)Student_id(pk)
          b)Full Name
          c)Email
          d)Course
          e)Phone number

4. Borrowing:-
          a)Student_id(fk)
          b)Book_id(fk)
          c)Borrow_date
          d)Expected return date

5. Returns:-
          a)Student_id(fk)
          b)Book_id(fk)
          c)Return_date
