# Requirements for our Blog API

## Maxine's blog

Resources are the nouns of our APIs -- stuff we can use a *CRUD* operation on.

**CRUD:**
- C - Create
- R - Read
- U - Update
- D - Delete

**List of resources:**
- Articles
- Writers
- Categories (for the articles)
- Comments (in each article)

**List of data types:**
- article
    - id
    - slug
    - title
    - content
    - writer
    - category
    - comments
- writer
    - id
    - name
    - bio
- comment
    - id
    - content
    - author
- error
    - code
    - description

**Notes:**

URI Parameter = 

    https://host.com/posts/5

Query Parameter = 

    https://host.com/posts?q=cat

    https://host.com/posts/5?q1=cat&q2=dog

Headers = 

    https://host.com/posts
    (headers ...)