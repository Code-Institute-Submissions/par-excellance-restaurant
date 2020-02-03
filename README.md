# Par Excellance - Allergen-free Fine Dining Restaurant

Code Institute - Milestone Project 1

This project is a one-page website for an allergen-free fine dining restaurant in London. The purpose of this website is to put emphasis on the uniqueness of the restaurant's concept on the market - while making sure the website is as informative and as functional as possible to the potential customers visiting the page.

![Website Showcase](https://github.com/valentina-b/milestone-project-1/blob/master/assets/readme_assets/images_readme/%20img-showcase.png?raw=true)



## UX
 
With the rise of autoimmune health issues which are closely connected to diet and lifestyle, the main problem this project is trying to solve is to provide a safe dining environment for people dealing with autoimmune disorders, allergies and food intolerances.

Thanks to the recent discoveries by functional medicine practinioners and researchers, today we know as a fact that, for example, gluten can cause problems to certain individuals for up to 6 months after the ingestion. This is why the possibility of eating a dish from a kitchen where allergens are handled is a high risk for a great number of people. As a consequence, people with autoimmune disorders stay away from eating out which makes their social, private and business life more difficult while simultaneously, restaurant owners are loosing valuable customers who are ready to spend more to dine out.

A restaurant of such type requires a website covering user stories from two sides - the owner's perspective (business goals) and user's perspective (customer goals).

The original project proposal to my mentor can be viewed [here.](https://github.com/valentina-b/milestone-project-1/blob/master/assets/readme_assets/MSTP_1_proposal-Valentina_Bedi.pdf)

### Business Goals

As a restaurant owner...
* I want customers to know I’m unique on the market so that they can easily differentiate me from competitors
* I want customers to make online reservations so that my service staff saves time and efforts answering phone calls
* I want customers to get updates about my restaurant so that they stay informed about the latest news and events

### Customer Goals

As a customer...
* I want to read the menu so that I can see if the food fits my diet and lifestyle
* I want to know the prices so that I can see if the restaurant's offer fits my budget
* I want to see ratings and reviews of the restaurant so that I can see what other customers think about the restaurant
* I want to make online reservations so that I can save time by not calling the restaurant or going there in person
* I want to contact the restaurant easily so that I can ask if I have additional questions or give my feedback
* I want to know when the restaurant is open and where is it so that I can make plans for a visit in advance



## Features and Page Sections

Based on the user stories, I've created brief overviews of the website information and features that should be provided in order to successfully reach both users' and website owner's goals.

Some of the information and features overlap, while some are strictly customer or business related:

![Goals Overview](https://github.com/valentina-b/milestone-project-1/blob/master/assets/readme_assets/images_readme/img-goals-overview.png?raw=true)

When everything put together, we get a brief overview of MVP features for the first round of implementation:

![Information and Features Overview](https://github.com/valentina-b/milestone-project-1/blob/master/assets/readme_assets/images_readme/img-information-features-overview.png?raw=true)


### Sections

1. Top navigation bar - fixed on the top so that the users are able to navigate themselves anywhere they are on the page.
2. Header - introduction to the website. Image indicates the product is eating related, logotype indicates it's an elegant place, CTA to book a table indicates it's about eating out and not ordering food, for example.
3. About section - explains the concept and the offer of the restaurant.
4. Menu section - gives the user more information about the quality and ingredients used in the restaurant with an option to download the menu as a PDF to learn more about the offer and prices before the visit.
5. Review section - positive feedbacks from previous customers to encourage the visit and set expectations.
6. Restaurant details section - provides relevant contact details and information about opening hours.
7. Footer - gives users the option to stay up to date with the restaurants news and events by subscribing to the newsletter and linking to social media profiles.

### Features

1. Booking a table online - a form that allows customers to make online reservations while they are already online and on the page, i.e. this feature doesn't let time to come between the 'consideration' and 'decision' phase of the customer.
2. PDF menu - menu in a PDF form in a new tab that allows users to get familiar with the dishes and prices.
3. Newsletter subscription and social media profiles' links - allow users to stay up to date with the latest news and events connected to the restaurant.
4. Shortcuts behind contact details - allow users to quickly email, call or see the restaurant on a map in order to avoid additional steps in contacting the restaurant (calling, visiting in person, etc.)

### Features Left to Implement

1. Booking through a calendar UI - instead of an online booking form in the current shape, the modal would look like a calendar which would give you date and time availability.
Example taken from a fine dining restaurant [Lorenz Adlon.](https://www.lorenzadlon-esszimmer.de/)

![Calendar Feature](https://github.com/valentina-b/milestone-project-1/blob/master/assets/readme_assets/images_readme/img-additional-calendar.png?raw=true)

2. Google maps frame - it would allow users to have information about the restaurant location at a glance.
Example taken from a fine dining restaurant [Jacobs Restaurant.](https://jacobs-restaurant.de/)

![Google Maps Feature](https://github.com/valentina-b/milestone-project-1/blob/master/assets/readme_assets/images_readme/img-additional-gmaps.png?raw=true)

3. Gallery of dishes or restaurant photos - a gallery of photos would be a great way to add more visual content to the site which would support the restaurant's concept and give an idea of the restaurant's environment.

Example taken from a fine dining restaurant [Jacobs Restaurant.](https://jacobs-restaurant.de/)

![Gallery Feature](https://github.com/valentina-b/milestone-project-1/blob/master/assets/readme_assets/images_readme/img-additional-gallery.png?raw=true)



## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X