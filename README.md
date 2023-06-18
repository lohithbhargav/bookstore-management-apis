# BOOKSTORE MANGAEMENT APIS

## Requirements
1. Database - MySQL
2. GORM
3. Json Marshall, UnMarshall
4. Gorilla MUX

## Folder
CMD -> main.go

PKG ->
    Config -> APP.GO
    controllers -> BOOK-Controller
    models -> BOOK.GO
    routes -> BOOKSTORE-ROUTES
    utils -> Utils.go

## Routes
1. GetBooks <- /book/ <- GET
2. CreateBook <- /book/ <- POST
3. GetBookByID <- /book/{bookid} <- GET
4. UpdateBook <- /book/{bookid} <- PUT
5. DeleteBook <- /book/{bookid} <- DELETE# bookstore-management-apis
