# Requirements for our Blog API

## Maxine's blog

Resources are the nouns of our APIs -- stuff that we can use a *CRUD* operation on.

**CRUD:**
- C - Create
- R - Read
- U - Update
- D - Delete

**List of resources:**
- Blog *
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
    - writerId
    - categoryId
    - comments
- writer
    - id
    - name
    - bio
    - articles
- category
    - id
    - name
    - articles
- comment
    - id
    - content
    - author
    - articleId
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