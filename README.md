# LMS
1. When using this program, the filepath must be changed in two places. Line 52 of FileParser.java and line 11 of FileUpdater.java
2. When a user is adding a book, some fields such as studentName, returnDate, and checkInStatus are automatically generated as they are only changed when checking in or out, not adding a book.
# Fastest way to check for all requirements
1. Run program
2. Click Catalog
3. Scroll through the catalog to see every field properly displayed. (You won't see any checked out books that aren't passed due unless you check out because of the time it took to make the program)
4. Select Reverse for "Order:" and hit Apply
5. Select Author from "Sort by:" then hit Apply, then the same for Page Count
6. Change Author and Subject to J.R.R Tolkien and Fantasy respectively then hit Apply
7. Reset Author and Subject back to no filter, then change at least one check box from Damage and one from Check-in Status then hit Apply
8. Click Back then Add
9. Fill out the fields (Set Damage to Major Damage) then click add. (A popup will show if you either use alphabetic characters for ISBN or Page count or leave any field blank)
10. Go back to Catalog and see it added to the list
11. Click Back then Check Out. Enter your name. Try to check out Lord of the Rings. Then choose the book you added. Then click Check Out and choose Yes.
12. Go back to Catalog to see changes you made to your book (Filtering out the authors will make this easier).
13. Click Back then Delete
14. Delete any book other than yours.
15. Open the JSON file and you will see the book you deleted is not there and your book is also there.
