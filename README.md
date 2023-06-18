# BOOKSTORE MANGAEMENT APIS

## Requirements
1. Database - MySQL
2. GORM
3. Json Marshall, UnMarshall
4. Gorilla MUX

## Folder
CMD -> main.go

PKG ->
    1. Config -> APP.GO
    2. controllers -> BOOK-Controller
    3. models -> BOOK.GO
    4. routes -> BOOKSTORE-ROUTES
    5. utils -> Utils.go

## Routes
1. GetBooks <- /book/ <- GET
2. CreateBook <- /book/ <- POST
3. GetBookByID <- /book/{bookid} <- GET
4. UpdateBook <- /book/{bookid} <- PUT
5. DeleteBook <- /book/{bookid} <- DELETE# bookstore-management-apis
