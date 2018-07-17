# Project Prompts

Each team of developers will be assigned one of the following projects to
complete. Though the broad brush-strokes are laid out for you here, the details
are **up to you**, so feel free to get as creative as you like!

Note: As in previous projects, **only shoot for Reach Goals once you've
satisfied the core requirements**.

## Bucketli.st

Besides finishing WDI, you surely have one or two things you'd love to do with
your life. Let's get 'em on paper! You could integrate with a third-party
location-based API to allow users to search for a location or venue to add to
their bucket list items.

**Reach Goal(s)**:
- Add social features to your site, such as following other users.
- Allow users to make certain list items public, but default to private.

## E-Commerce

Create an e-commerce site for famed retail giant, Nozama.com! Naturally, the
site will need to allow customers to see all of Nozama's products, add those
items to a shopping cart, and purchase them using
[Stripe](https://stripe.com/docs/checkout). In addition, by logging in,
customers should be able to keep track of their purchases by looking at their
past orders.

**Reach Goal(s)**:
- Build a search feature so that people can search for specific
products by name.

## Survey

Make an app that can be used to create custom surveys (for instance, asking
"what should we eat for lunch today?" or "On a scale of 0-5, how well did you
understand what we just learned?") and collect the responses on a dashboard for
that particular survey.

**Reach Goal(s)**:
- Make the dashboard real-time, so you can see answers pour in as
they're completed.
- Each live survey should be hosted at a unique, randomly-generated URL.

## FileBucket

Build an app for your client, Xobpord, that allows users to upload files into a
virtual file system. Ordinary users can only read/download a file where as
Owners can do anything to the files they own. In addition to keeping track of
the file structure, this app should associate meta-data with each file,
including things like:

-   date created/uploaded
-   date modified
-   owner (user who uploaded the file)
-   tags

**Reach Goal(s)**:
Implement a simple permissions system for your application:

-   'collaborators' can be chosen; they have permission to read from and write
    to files.

## Content Management System

Build an application for Swedish web-conglomerate Sserpdrow! Your application's "users" will be companies/organizations that want to have their own company blog and web pages and they are going to use your application to CRUD their own "blog posts" **and** "web pages".
When a user logs in, they should see a dashboard that lets them CRUD their "blog posts" and "web pages".
Your application will also likely have “visitors” that just go to your site and want to consume (read) the content that your “users” (companies/organizations) have provided. When a "visitor" goes to your site, they should be shown a list of companies/organizations to view.

- Ex: "blog post": http://november-project.com/category/boston/
- Ex: "web page": http://november-project.com/how-to-join/

**Reach Goal(s)**:
Implement authorization.
- Administrators should be able to delete pages or posts, while normal users should be able to edit pages. Only administrators can publish a new post, normal users can only save drafts.

## Inventory Management System:

The recent merger of two mega-companies, Nozama and Part Foods has created the need for a better inventory management system. You have been hired for the job!

The main responsibility of the inventory management system is to be able to track your inventory levels: how much you have received, orders that have been filled, and when you need to order more. The attributes of the items in inventory should make sense for your business, and include things like price and quantity on hand. Each item type should have a unique identifier created by the manufacturers that can use to identify the item (barcode, serial number, etc). This unique identifier is the link between the manufacturer's database and your inventory management system's database. Authentication will be a key feature so the system is secure.

**Reach Goal(s)**:
- Develop a barcode generator or QR code generator that creates a unique image that contains the unique identifier for each item in your inventory
- Automatic refill notifications: when an item gets to a low quantity, send a request to the manufacturer of the item to ship you another order of that item
- Enhanced authentication: Restrict user signups to emails of a certain domain, that of the company that is running the inventory management system. Make sure to verify email addresses. Use multi factor authentication during the sign up or sign in process.
