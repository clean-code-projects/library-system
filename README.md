# library-system
Create a library system

Based on an [Object Mentor's Course](https://github.com/clean-code-projects/library-system.git)

Use Cases:
- Librarians can register patrons
- Librarians can add copies of a book to the library
- Patrons can borrow a copy of a book from the library
    - Patrons cannot borrow a copy that is already borrowed
    - Patrons can borrow more than one copy if available
    - The return date should be set two weeks from borrow date
    - Young patrons cannot borrow age restricted books
    - Patrons cannot borrow books if they have outstanding fines
- Patrons can return a copy of a book to the library
    - Patrons cannot return a book that was not borrowed
    - Patrons should receive a 50 cent fine for each day the book is late
    - Patrons should receive a $5 fine if the book is damaged
    - Patrons should recieve a fine for the retail price of the book if it is lost
- Patrons can pay fines
- Librarians can add CDs and DVDs to the library
