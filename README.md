# URL Shortener Tech Test

Typing out entire URLs is inconvenient. Companies like bit.ly (hint hint) have provided us with services to make this problem go away, We want you to build your very own URL shortener and disrupt this 10x growth market.

## Specification

We often have links that looks like this:

`https://www.dojoapp.co/event/fake-laugh-e1-6ql-london`

What we really want is a link that looks like this:

`http://bit.ly/2vk82Lq`


### Version 1

Create a web application with form that takes a long URL and generates a short URL, storing the short URL and long URL together in a persistant data store.
The application should redirect users to the long URL when the short URL is visited
Users should not be able to submit an invalid URL
The application should check if the URL has already been stored and not create duplicate entries
### Version 2

Style the application - use a site like bit.ly as an inspiration, or come up with your own design.
### Verson 3

Track the number of times a shortened URL has been visited
Track the time and date that a shortened URL has been visited
Create a statistics page, that shows the short URL, the long URL, each visit and the total number of visits
You may use whatever technologies you see fit. Try to be deployed as early as possible.
