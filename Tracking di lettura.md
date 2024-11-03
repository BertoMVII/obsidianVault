---
cssclasses:
  - cards
  - booksTracking
---

```dataview
Table ("![](" + coverUrl +")") as Copertina, Pagine as Pagine, Autori as Autore
From "Books"
where contains(status, "Terminato")
```
