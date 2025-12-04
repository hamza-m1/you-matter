# You Matter

This is a mental health awareness site offering explanations of common conditions, quick practical tips, and links to trusted resources. The user base is newcomers to mental health topics, people feeling stressed, and users seeking reputable external help.

## Design and Planning

### User stories

- As a site visitor, I want the website to be responsive and look good on all screen sizes (desktop, tablet, mobile) so that I can have a smooth and comfortable browsing experience.
- As a Site User, I want to navigate easily through the website so that I can find the information I need.
- as a visitor, I want to see a calm, welcoming hero message on the homepage so that i can feel reassured and comfortable exploring the site.
- As a newcomer to mental health topics, I want to find clear, beginner-friendly explanations of common issues/challenges so that i can understand what they are and how to spot them.
- As a user feeling stressed or anxious, I want to access a short list of practical stress-management tips so that I can try implementing the tips to help lower my stress.
- As a user wanting trusted help, I want a resource links section with clear labels and external links so that I can find professional support and further reading.
- As a site visitor, I want to read an About Us section so that I can understand the purpose, values, and mission of the website and feel connected to the team behind it.
- As a user who benefits from encouragement, I want a rotating set of positive affirmations or quotes so that I can feel uplifted and supported.
- As a user seeking someone to talk to, I want a clear, private way to contact the site team (for example a contact form or email) so that I can ask questions or request support confidentially.

### Wireframes

![mobile hero section wireframe](/assets/readme-images/mobile-hero-wireframe.png)

![mobile challenges section wireframe](/assets/readme-images/mobile-challenges-wireframe.png)

![mobile resources wireframe](/assets/readme-images/mobile-resources-wireframe.png)

![mobile contact us wireframe](/assets/readme-images/mobile-contact-us-wireframe.png)

![desktop top wireframe](/assets/readme-images/desktop-wireframe1.png)

![desktop bottom wireframe](/assets/readme-images/desktop-wireframe2.png)

### Typography

I used chewy from google fonts for headers and titles because it's playful, calming and bold.
I used Quicksand from google fonts because its easy to read and complements Chewy.

### colour Scheme

- #025951; Dark green
- #a9d8ae; Medium green
- #fffdec; Light yellow

I decided to go with a leafy green colour scheme as it reflects nature, which is calming so would help the user feel calm and relaxed as they navigate through the site.

## Features

The site uses Bootstrap components and clean HTML/CSS to provide a calm, accessible experience. Key UI features include:

- **Bootstrap Navbar:** Responsive top navigation with a clear brand link and collapsible menu for small screens.
- **Bootstrap Cards:** Card components used for the Challenges and Resources sections to present concise, scannable content.
- **Bootstrap Accordion:** Collapsible, accessible accordion used for the Practical Tips section so users can expand the tips they want to read.
- **Bootstrap Form:** A simple contact form with labels and validation-ready inputs for users to get in touch.
- **Bootstrap Carousel:** A small carousel for daily affirmations to provide gentle, rotating encouragement.
- **Footer:** A persistent footer with contact and copyright information.

## Technologies Used

This project uses the following core technologies:

- **HTML:** Semantic, accessible markup for page structure and content.
- **CSS:** Custom styles and CSS variables for theming; responsive layout and calm visual design.
- **Bootstrap:** Bootstrap 5 components and utilities (navbar, cards, accordion, form, carousel) for responsive, accessible UI.
- **Font Awesome:** Iconography via Font Awesome for clear, lightweight visual cues
- **Google Fonts:** Web fonts (for example, Chewy and Quicksand) are loaded from Google Fonts for friendly, readable typography.
- **Git & GitHub:** Source control with Git and remote repository hosting on GitHub; GitHub also used for site deployment.
- **GitHub Copilot:** Assisted authoring and problem solving using GitHub Copilot — used here for generating illustrative images and for helping with quick bug fixes and implementation suggestions.

## Testing

### Google Lighthouse Performance

![Google lighthouse performance score](/assets/readme-images/google-lighthouse-score.png)

### Responsiveness

![Responsiveness test across multiple screen sizes](/assets/readme-images/site-responsiveness.png)

The challenges section on desktops:

![Responsiveness test for the challenges section on desktop](/assets/readme-images/responsivness-challenges-desktop.png)

The challenges section on tablets:

![Responsiveness test for the challenges section on tablets](/assets/readme-images/responsivness-challenges-tablet.png)

The challenges section on mobiles:

![Responsiveness test for the challenges section on mobiles](/assets/readme-images/responsivness-challenges-mobile.png)

### Code Validation

Homepage HTML validation:

![HTML validation for index.html](/assets/readme-images/index.html-validation.png)

Contact form success page HTML validation:

![HTML validation for the contact form success page](/assets/readme-images/success.html-validation.png)

Styles CSS validation:

![HTML validation for the Styles CSS file](/assets/readme-images/css-validation.png)

### Colour Contrast

Colour contrast between dark green background and white text:

![Colour contrast between dark green background and white text](/assets/readme-images/colour-contrast1.png)

Colour contrast between medium green background and black text

![Colour contrast between medium green background and black text](/assets/readme-images/colour-contrast2.png)

Colour contrast between light yellow background and black text

![Colour contrast between light yellow background and black text](/assets/readme-images/colour-contrast3.png)

## Manual Testing user stories

- As a site visitor, I want the website to be responsive and look good on all screen sizes (desktop, tablet, mobile) so that I can have a smooth and comfortable browsing experience.

![User story 1 test](/assets/readme-images/user-story-test1.png)

- As a Site User, I want to navigate easily through the website so that I can find the information I need.

![User story 2 test large screen](/assets/readme-images/user-story-test2-1.png)

![User story 2 test small screen](/assets/readme-images/user-story-test2-2.png)

- as a visitor, I want to see a calm, welcoming hero message on the homepage so that i can feel reassured and comfortable exploring the site.

![User story 3 test](/assets/readme-images/user-story-test3.png)

- As a newcomer to mental health topics, I want to find clear, beginner-friendly explanations of common issues/challenges so that i can understand what they are and how to spot them.

![User story 4 test](/assets/readme-images/user-story-test4.png)

- As a user feeling stressed or anxious, I want to access a short list of practical stress-management tips so that I can try implementing the tips to help lower my stress.

![User story 5 test](/assets/readme-images/user-story-test5.png)

- As a user wanting trusted help, I want a resource links section with clear labels and external links so that I can find professional support and further reading.

![User story 6 test](/assets/readme-images/user-story-test6.png)

- As a site visitor, I want to read an About Us section so that I can understand the purpose, values, and mission of the website and feel connected to the team behind it.

![User story 7 test](/assets/readme-images/user-story-test7.png)

- As a user who benefits from encouragement, I want a rotating set of positive affirmations or quotes so that I can feel uplifted and supported.

![User story 8 test](/assets/readme-images/user-story-test8.png)

- As a user seeking someone to talk to, I want a clear, private way to contact the site team (for example a contact form or email) so that I can ask questions or request support confidentially.

![User story 9 test](/assets/readme-images/user-story-test9.png)

## Bugs

**Card heights**

- The card heights were not uniform across screen sizes. I fixed this by using media queries to change the height based on screen width.

**Cards not centered on mobile screens**

- fixed by adding auto margin to the left anf right of the cards

**Accordion items did not close when others were opened**

- When adding extra accordion items on top of the 3 copied from bootstrap examples, they did not link with the other items and so didn't auto close.
- I fixed this by adding the code below to every accordion item.

```
data-bs-parent="#tipsAccordion">
```

## Deployment

**Creating a repository on GitHub**

1. Go to GitHub.com and sign in to your account.
2. In the upper-right corner of any page, open the + menu and select New repository.
3. Enter a repository name and choose Public or Private.
4. (Optional) Check Add a README file to create a longer project description.
5. Click the green Create repository button.

**Deploying on GitHub Pages**

1. Open the repository on GitHub and go to Settings → Pages.
2. Under Source, choose Deploy from a branch.
3. Set Branch to main and Folder to / (root).
4. Click Save.
5. Wait a few minutes — the live site URL will appear at the top of the Pages settings.

## Credits

- GitHub Copilot for image generation
