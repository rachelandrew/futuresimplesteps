### How to add a book

Create a new file in the `_books` folder with your book title as the filename and ending in the extension `.md` (use hyphens instead of spaces).

Copy the following code and paste it into your file:

```
---
author-name: "Your Full Name"
author-name-short: "Your First Name"
author-website: "https://mywebsite.com"
author-twitter: "twitterhandle"
book-title: "My Book Title"
book-slug: "your-book-title"
book-url: "https://mywebsite.com/where-you-can-buy-my-book"
---

The book blub goes here, and the format is Markdown.

```

Edit the contents.

Check to ensure there is a book image in the `images` directory with the filename `book-slug_medium.jpg`. Otherwise, we can help update the image for you, or you can add a new image following that filename structure.

Commit the changes.

#### If you have multiple authors

You can add additional author names and Twitter handles:

```
author-name: "First Author and Second Author"
author-name-short: "First"
author-name-short2: "Second"
author-twitter: "firsttwitter"
author-twitter2: "secondtwitter"
```

#### If you are offering the book for free

You can add one additional line:

```
free: true
```

This will change the button text to say "Read [Bookname]" instead of "Buy [Bookname]".