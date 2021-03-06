# Testing

## User Stories

As a customer I want to be able to see various photos so that I know how mine can turn out.

1. When a customer clicks on the link to the website they go on the landing page.
2. Top right is a hamburger menu, when clicked on it opens up and has 4 page option.
3. The customer can click on the Gallery option which will take them to the Gallery page.
4. Here they will see a mixture of pictures of pets from previous photoshoots.
5. If visiting on a large screen, the pictures zoom out to create a more dynamic web page.

As a customer I want to be able to navigate with ease through pages.

1. As a customer you have a collapsed menu on the top right, on all pages that is not sticky so you don't need to go back to top of the page to find it.
2. Top left, customers can find a paw icon which when clicked takes them back to the homepage.


As a customer I want to see the prices so I can see if the service is affordable.

1. The customer can find the prices by clicking on the menu and then clicking services.
2. In the services page they can find the three packages with a link each that takes them to the contact page to enquire about the packages.

As a customer I want an easy way to contact the photographer.

1. The customer can contact the photographer by going to the menu and clicking contact.
2. On the contact page the customer can find a form where they can add their details and their message and submit it.
3. The customer can also be led to the contact page from the services page, where there's a contact link in the initial paragraph as well as an enquire button on each package card.

As a customer I want to see other people's experiences and reviews.

1. Customers can find people's reviews on the home page at the bottom after being introduced to Regina.

## Validation testing

### [W3C CSS Validation Service](jigsaw.w3.org)

![alt text](./readme_images/css.png)



### [W3C Markup Validation Service](https://validator.w3.org/)

Index page was checked in the validator and showed the below.

![alt text](./readme_images/w3-index.png)

While it looked very decent I wanted to increase the accessibility as that was also something that showed up when checked with lighthouse chrome dev tools.

I realised that I needed to remove the maximum scale in the meta as well as changing user-scalable from no to yes.

This resulted in an improvement in the accessiblity.

![alt text](./readme_images/w3-index-update.png)

The rest of the pages were also run through the validator and the results are linked below.

* [Gallery](./readme_images/w3-gallery.png)
* [Services](./readme_images/w3-services.png)
* [Contact](./readme_images/w3-contact.png)


### Lighthouse

As mentioned above, an accessibility issue came up which was then resolved.

![alt text](./readme_images/lh-index.png)

![alt text](./readme_images/lh-index-updated.png)

The rest of the pages were also checked via lighthouse and the results are linked below.

* [Gallery](./readme_images/lh-gallery.png)
* [Services](./readme_images/lh-services.png)
* [Contact](./readme_images/lh-contact.png)


## Manual Testing

### Home page

