# In-memory Database

Your task is to design an in memory database using the given data.

You should design an API that is similar to ActiveRecord and allows:

- Reading of CSV files into a meaningful structure
- Print out all `books` and `magazines` (into the console) with all their details
- Find a book or magazine by its `isbn`
- Find all books and magazines by their `author`'s email
- Print out all books and magazines with all their details sorted by `title`

# Data

Data is stored in the `db/data` folder which contains:

- `authors.csv`: Contains authors with their `email`, `firstName`, and
  `lastName`
- `books.csv`: Contains books with their `title`, `description`, one or more
  `authors` and an `isbn`
- `magazines.csv`: Contains magazines with their `title`, one or more `authors`,
  a `publishedAt`, and its `isbn`
