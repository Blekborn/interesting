# List of Free Learning Resources
## Intro
If you want to find a learning resource, you should definitely check out our site, [Free Learning Resources](http://resrc.io).
And for those who want to learn a computer language, you should check out these books on [reSRC.io](http://resrc.io/list/10/list-of-free-programming-books/) or on [github](/free-programming-books.md).
This list initially was a clone of [stackoverflow - List of Freely Available Programming Books](http://stackoverflow.com/questions/194812/list-of-freely-available-programming-books/392926#392926) by George Stocker. Now updated, with dead links gone and new content.

Moved to GitHub for collaborative updating and for the site mentioned above.

### NEW : Search inside free-programming-books.md (and a whole lot more of learning resources)
[resrc.io/search](http://resrc.io/search/)

### How To Contribute
It's [easy](https://github.com/vhf/free-programming-books/wiki/Contribution). Please read [CONTRIBUTING](/CONTRIBUTING.md).
- [Fork](https://help.github.com/articles/fork-a-repo)
- Read the [TODO](/TODO.md) file(Adding new books is our #1 priority, but things like Alphabetizing are important, too.)
- [Edit](https://github.com/vhf/free-programming-books/edit/master/free-programming-books.md) (we prefer multiple small commits rather than one large change)
- [Send a PR](https://help.github.com/articles/using-pull-requests)
- Be part of a project that over 31,000 people starred in 13 months. ;)

**Again, unlike other projects, we prefer multiple small commits rather than one large change in a pull request - it's fine to have one PR, but please make sure your title reflects what you're changing**, thanks.


### How to Share
+ [Share on Twitter](http://twitter.com/home?status=https://github.com/vhf/free-programming-books%0AFree%20Programming%20Books)
+ [Share on Facebook](http://www.facebook.com/sharer/sharer.php?s=100&p[url]=https://github.com/vhf/free-programming-books&p[images][0]=&p[title]=Free%20Programming%20Books&p[summary]=)
+ [Share on Google Plus](https://plus.google.com/share?url=https://github.com/vhf/free-programming-books)
+ [Share on LinkedIn](http://www.linkedin.com/shareArticle?mini=true&url=https://github.com/vhf/free-programming-books&title=Free%20Programming%20Books&summary=&source=)


### In Other Spoken Languages
+ Russian: [github](/free-programming-books-ru.md)
+ Ukrainian: [github](/free-programming-books-ua.md)


### Noticeable lists from [reSRC](http://resrc.io/)
+ Free JavaScript frameworks resources and tutorials: [github](/javascript-frameworks-resources.md) or [site](http://resrc.io/list/18/javascript-frameworks/)


### Interactive Programming Resources
+ Free interactive programming tutorials: [github](/free-programming-interactive-tutorials-en.md) or [site](http://resrc.io/list/217/programming-interactive-tutorials/)


### Podcast - Screencast
Free Podcasts and Screencasts:
+ English: [github](/free-podcasts-screencasts-en.md)


### Software Testing Books
+ [Free ebooks about software testing](https://github.com/ligurio/free-software-testing-books)

------------

### Cloudinary

 - https://cloudinary.com/users/login

 - Gemfile: gem 'cloudinary'

 - uploaders -> image_uploader.rb -> include Cloudinary::CarrierWave

 - You can download your customized cloudinary.yml configuration file through our Management Console. https://cloudinary.com/documentation/rails_integration

 - config -> cloudinary.yml  

 - config -> storage.yml =
   ` cloudinary:
      service: Cloudinary`
   
 - config -> environments -> development.rb = config.active_storage.service = :cloudinary

