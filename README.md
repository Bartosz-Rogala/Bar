# Aplikcja do obsługi klientów w barze.
Aplikacja została stworzona na potrzeby rekrutacji

Aplikacja została stworzona przy wykorzystaniu Spring Boot

Aplikacja wystawia REST API:
-POST /api/create - przyjmuje zamówienia
![](/screenshots/post.png)

-GET  /api/view_orders/id - z parametrem id - pobiera dane do paragonu/faktury
![](/screenshots/get.png)



Aplikacja pozwala również na pobranie informacji o wszystkich zamówieniach:

-GET /api/view_orders

oraz na pobranie informacji o zamówieniach tylko jednej osoby 

-GET  /api/view_orders/client - z parametrem barClient