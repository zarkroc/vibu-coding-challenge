# Frontend Assignment

Please implement page in software stack of your choice with the following requirements

- Assume that you have data already returned from JSON service. Structure of that JSON is up to you.
  - The data could be in this form but you're free to do as you wish:

```[
    {
      id: 1,
      movie: "name of movie",
      description: "Lorem ipsum",
      image: 'url-to-image'
      thumbs-down: 1,
      thumbs-up: 10
      user: {
        name: "Tord userson",
        image: "http://usersprofileimage.net"
      },
      comment:{
        user: "Rutger Gönåker"
        text: "comment text"
      }
    }
    {
      id: 1,
      movie: "name of second movie",
      description: "Lorem ipsum",
      image: 'url-to-image'
      thumbs-down: 5,
      thumbs-up: 1
      user: {
        name: "Tord userson",
        image: "http://usersprofileimage.net"
      },
      comment:{
        user: "Rutger Gönåker"
        text: "comment text"
      }

    }
  ]
```

- Data should be presented in a single page.
  - Think a list of movies with comments and the possibility to add  and see comments.
  - It should be posible to see up and down votes (But voting is not needed)
- Functionality of adding comments should be implemented - comment box doesn't have to look fancy, but user should be able to add a comment which then will be displayed on page. **Note:** This comment doesn't have to be stored on server - it can vanish after full page reload.
  - If comment is present in data (if you choose to implement it like that should be visible)
- Thumbs-up/thumbs-down one doesn't influence another in any way. This is also static content; it's just displaying data. I.e no user input!
- Text should expand after clicking at any part of it. Collapsing text doesn't have to be implemented.
- Thumbs up / thumbs down / stars are all part of Font Awesome.
  - Or use use numbers if time is lacking!
- You can grab random user images from e.g. <https://randomuser.me/>
- Header/background image - pick whatever you want from Flickr or similar same goes for movie images.
- It doesn't have to render on a server.
- HTML/Component (if used) structure is totally up to you.
- Page doesn't have to be responsive. Layout doesn't have to be pixel perfect or pretty :smiley:
- It's only client side "application" (we used quotes, because it's only one page - hard to call it "application" ;)

Try to have correct error codes. Write a short documentation on HOW to use your code and how to run it.

**If you feel nice** please limit your solution to: JavaScript, TypeScript, (Vue and React) :smiley:

Have fun!
