# REST

## What Google Learned From Its Quest to Build the Perfect Team

* They make a programs, a way for students to practice working in teams and a reflection of the increasing demand for employees who can adroitly navigate group dynamics. A worker today might start the morning by collaborating with a team of engineers, then send emails to colleagues marketing a new brand, then jump on a conference call planning an entirely different product line, while also juggling team meetings with accounting and the party-planning committee.

* Every day, the teammates gathered to discuss homework assignments, compare spreadsheets and strategize for exams. Everyone was smart and curious, and they had a lot in common. These shared experiences, would make it easy for them to work well together.

* Today, on corporate campuses and within university laboratories, psychologists, sociologists and statisticians are devoting themselves to studying everything from team composition to email patterns in order to figure out how to make employees into faster, better and more productive versions of themselves.

# How I explained REST to my brother

## Who is Roy Fielding?
Roy Thomas Fielding (born 1965) is an American computer scientist, one of the principal authors of the HTTP specification and the originator of the Representational State Transfer (REST) architectural style. He is an authority on computer network architecture and co-founded the Apache HTTP Server project.


## Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?
Machines don't have a universal nouns,and every programming language, database, or other kind of system has a different way of talking about nouns. That's why the URL is so important. It let's all of these systems tell each other about each other's nouns.

## What is the HTTP protocol that Fielding and his friends created?
HTTP—this protocol Fielding and his friends created—is all about applying verbs to nouns. For instance, when you go to a web page, the browser does an HTTP GET on the URL you typed in and back comes a web page.

## What does a GET do? Web pages usually have images, right?
Those are separate resources. The web page just specifies the URLs to the images and the browser goes and does more GETs using the HTTP protocol on them until all the resources are obtained and the web page is displayed. But the important thing here is that very different kinds of nouns can be treated the same. Whether the noun is an image, text, video, an mp3, a slideshow, whatever. I can GET all of those things the same way given a UR.

## What does a POST do?

It's used If one system needs to add something to another system.

## What does PUT do?

It's used If a system wants to replace something in another system

## What does PATCH do?

It's used if a system want to do a partial update

## What does PATCH do?
In computing, the PATCH method is a request method supported by the Hypertext Transfer Protocol (HTTP) protocol for making partial changes to an existing resource. The PATCH method provides an entity containing a list of changes to be applied to the resource requested using the HTTP Uniform Resource Identifier (URI)

API Keys

## Did you get your API key for the Geocoding API?

Yes i did

## Did you get your API key for the Weather Bit API?

Yes i did

## Did you get your API key for the The Movie DB API Docs?

Yes i did