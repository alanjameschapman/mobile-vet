# Mobile Vet

The Mobile Vet is a Veterinary Service to treat poorly animals. There will be a main clinics (based in Thirsk), but owners can request a call-out if they are unable to get to the practice.

![Responsive Mockup](docs/screenshots/am-i-responsive.png)

## Features

### Features common to all pages

- **Navigation Bar**

  - The navigation bar is on all pages (for quick/easy navigation) and responds to smaller screens by reducing to a burger icon, which expands downwards to reveal all pages. Links to Mobile Vet, Services, Appointments and The Team pages. As a result, the user has no need to use their browser 'back' button.

![Nav Bar Burger Dropdown](docs/screenshots/navbar-burger-dropdown.png)

![Nav Bar](docs/screenshots/navbar.png)

- **The hero images**

  - Common to all but The Team page (which already contains three profile images) each page has an image with text overlay to summarise to the user what the page is about. Each page has a different image to keep the user interested.
  - Text sits on a semi-opaque background to keep text readable over the image. The box will be centre-justified relative to the image, vertically and horizontally.

![Hero Image](docs/screenshots/hero-image.png)

![Hero Image](docs/screenshots/hero-image.png)

- **The Footer**

  - The footer section includes links to the associated Facebook, X and linkedin pages for The Mobile Vet. There they would gather more information relevant. The links open to a new tab to avoid the user from 'losing their bearings' on the site.
  - There is also a hyperlink to return the user to the top of the page, particularly useful for mobile users.
  - "This page is for educational purposes only." is self-explanatory.

![Footer](docs/screenshots/footer.png)

### Pages

- **Services**

- This page will give an overview of the kinds of treatment that the practice can deliver.

- **Appointments**

- This page allows the user to book an appointment with a vet convenient to them.

- **The Team**

- Owners want to know their pets are in safe hands. This page introduces member of The Team with profiles and 'friendly faces'.

## Testing

- I deployed before content creation for feedback from Mentor and friends.
- I also posted to #peer-code-review on Slack for peer review.
- I continuously tested my website on different screen sizes using DevTools on Chrome and different devices.
- Once the website was deployed I checked using W3C validator at every push/deployment - see Validator Testing section.

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub)

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - <https://alanjameschapman.github.io/mobile-vet/index.htm

## Credits

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism.

You can break the credits section up into Content and Media, depending on what you have included in your project.

### Content

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site

Congratulations on completing your Readme, you have made another big stride in the direction of being a developer!

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work!

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write a Git Commit Message

  - Make sure to keep the messages in the imperative mood

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.

  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept.

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process!
