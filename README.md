# Active Record Conclusion

We have just explored the world of ORMs: _Object Relation Mappers_. When
creating applications with Ruby on Rails, we use an ORM called _Active Record_,
integrated into our projects as a Ruby gem. Active Record creates a link between
Ruby and our database, which means it can take care of translating queries we
write using Ruby into commands the database understands. It makes our work
easier and faster.

Over the past several lessons, we covered the basic mechanics of Active Record,
including connecting to a database, creating tables and finding/saving data.
Since it's always important to know what's going on under the surface of the
tools we use, we also explored how Active Record abstracts the methods we
employ. Of course, we then practiced employing those Active Record methods. We
also learned that instead of making individual, manual changes to databases, we
can use Active Record migrations, which apply database changes as an organizated
structure. Migrations serve as a sort of version control system for our
database, so we covered how they work and how to write our own. Ultimately, we
saw how we can create CRUD actions—create, read, update, delete—for our
applications with Active Record, an essential skill we'll be using as we create
web applications. We also encountered Rake, a tool that helps us create and
automate tasks in Ruby.

We have Ruby knowledge, we have database knowledge and now we know how to use
the ORM layer to communicate between the two. We're ready to move on and learn
how to use these blocks to build something powerful.
