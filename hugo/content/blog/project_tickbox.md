+++
title = 'What every software project needs'
date = 2025-10-22T14:38:10+01:00
draft = true
+++


This is not an exaustive list but as a bare minimum you need the following:

### People

1. __Hire good developers__

This is a really important one so why is it relatively rare? 
Well, partly because hiring managers generally don't know what a good developer looks like and partly because good developers are expensive.
Our advice is to hire __fewer but better__ developers.
You'll also reduce communication overhead.

2. __Eat your own dog food__

If the people building the product are not the people maintaining it, guess what? 
They'll build a product where maintenance is not the most important property and instead prioritise getting a product out of the door.
That's just human nature. 
This was rampant in the outsourcing craze of the early 2000s. 
These days, staff are generally __embedded__ in the development team if work is outsourced to a third party. 


3. __Quality work tickets__

Tickets need:
- to be approved by the person doing the work
- to be as accurate as possible
- to have acceptance criteria that define what 'done' means.

There's often horse trading between the implementers and the business when agreeing on what exactly a ticket includes. 
In this most human of tech processes, emotional safety is key.

4. __Emotional safety__

Steve Jobs famously [said](https://www.goodreads.com/quotes/8586131-it-doesn-t-make-sense-to-hire-smart-people-and-then):  "It doesn't make sense to hire smart people and then tell them what to do. We hire smart people so they can tell us what to do."
It takes more than one-off away days to facilitate this. 
Instead there must be regular stakeholder involvement, preferably daily. 
A lot of __Agile practices__ advocate this so if you're not employing at least some of these principals, you should.

### Process

1. __Automated regression tests__

You'll be hard pressed to find an open source project without __continuous integration__ but I still see some in industry.


2. __Logging__

Good logging is the key to effective maintence.
It's also the first thing to be neglected if the devs are not the maintainers (see "Eat your own dog food").
