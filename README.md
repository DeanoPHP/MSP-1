# Gold's Gym

![Responsive](assets/images/responsive.png)
[Click here to view the live website](https://deanophp.github.io/MSP-1/)

## Overview
Welcome to the repository for Gold's Gym, a modern and dynamic gym located at the heart of the city, dedicated to empowering individuals through fitness. Our website serves as a virtual extension of our physical space, providing visitors with detailed information about our facilities, services, and fitness programs. The website features responsive design, ensuring a seamless experience across all devices, from desktops to mobile phones.

This is a fictitious gym website created as part of a Web Development course with Code Institute. It has been designed to simulate a real-world application, this website serves as a showcase of my skills in HTML, and CSS.

## User Experience (UX)

### As a visitor
- As a visitor I want to be able to easily navigate the website so I can find information about the gym services, classes, opening times, and membership fees.
- As a visitor I want to see a well-organized presentation of all fitness classes before I join.
- As a visitor I want the website to be visually appealing and professionally styled so that I have a positive impression of the gym.
- As a visitor I want to be able to find the contact information easily so I can contact the gym to arrange a visit.
- As a visitor I want to easily find contact information so I can contact the gym with any questions.
- As a visitor I want to see a map of the gym's location.
- As a visitor I want to see a gallery showing the gym's facilities so I can see whether it meets my needs.
- As a visitor I would like to information about the gym staff.<br><br>
- As a visitor I want to to be able to use all my devices to view the gyms website so responsive design is a must.

### As a gym owner 
- As a gym owner, I want to feature high-quality images and detailed descriptions of our specialized equipment and facilities so that potential members can see we are well-equipped for serious bodybuilders.

- As a gym owner, I want to highlight our personalized training programs on the website, including details about our expert trainers and their bodybuilding expertise, to attract members looking for guidance and advanced workout strategies.

- As a gym owner, I want to to give the user a clear way to join

### As a returning user 
- As a returning user, I want to quickly book personal training sessions through the website, so I can ensure consistent progress and availability with my preferred trainers.
- As a returning user, I want to easily view and manage my membership details, such as renewal dates and payment methods, to keep my account in good standing without any administrative hassles.
- As a returning user, I want to easily find and sign up for upcoming events and competitions hosted by the gym, ensuring I never miss out on key community activities.
- As a returning user, I want to easily provide feedback about the gym's facilities, trainers, or services through the website, to ensure that my voice is heard and that the quality of the gym continues to improve.

## Skeleton
Wireframes were designed using [Balsamiq](https://balsamiq.cloud/#)
<br><br>

| Desktop                                   | Tablet                                  | Mobile                                  |
| ----------------------------------------- | --------------------------------------- | --------------------------------------- |
| ![Desktop](assets/wireframes/desktop.png) | ![Tablet](assets/wireframes/tablet.png) | ![Mobile](assets/wireframes/mobile.png) |

## Technologies Used
- HTML
- CSS
- Bootstrap
- Animate.css
- FontAwesome
- Google Fonts

## Design

### Color Palette
  - Gold: #C7A64A - Used for h1 tags and logo;
  - Dark shade of yellow-green #5C501F - Used for sub-headings;
  - Light grey: #fafafa - Used for links;
  - very light grey: #eeeeee - used for body;

## Font Usage

Our project utilizes a combination of FontAwesome, Roboto, and Anonymous Pro to ensure clear readability, aesthetic appeal, and functional design across all elements of our website.

### Fonts Details

- **Google Fonts**: Used primarily for icons across the website. FontAwesome provides scalable vector icons that can instantly be customized — size, color, drop shadow, and anything that can be done with the power of CSS.

- **Roboto**: This is the primary typeface used for text elements on the website. Designed for readability, Roboto offers a modern, neutral look with a wide range of weights and styles.

- **Anonymous Pro**: Employed mainly in code snippets and data displays, Anonymous Pro is a monospace font that offers excellent clarity and readability in technical sections of the website.

### Font Integration

To integrate and use these fonts in your development environment, follow these steps:

- **fonts.google.com**:
  ```css
    /* Importing Roboto font with all weights and styles */
    @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');

    /* Importing Anonymous Pro font with specific weights and styles */
    @import url('https://fonts.googleapis.com/css2?family=Anonymous+Pro:ital,wght@0,400;0,700;1,400;1,700&display=swap');

- [Link for Roboto](https://fonts.google.com/?query=roboto)
- [Link for Anonymous Pro](https://fonts.google.com/?query=anonymous+pro)


Anonymous Pro and Roboto make a highly functional pairing in digital design, combining clarity with versatility. Anonymous Pro, a monospaced font, offers exceptional readability for code snippets and data, ensuring that each character is distinctly spaced and easy to differentiate. This makes it ideal for technical contexts where precision in text presentation is crucial. Roboto, on the other hand, is a sans-serif font known for its clean lines and friendly appearance, making it suitable for more general text such as paragraphs, headings, and user interfaces. Together, these fonts provide a balanced aesthetic: Roboto enhances the visual appeal and ease of reading for narrative text, while Anonymous Pro ensures technical sections are approachable and clear. This combination is particularly effective in environments like technical blogs, programming interfaces, or any application where text clarity and user comfort are paramount.

### Implementation

Here is an example of how to apply colours and fonts:

```css
:root {
    --link-font-color: #fafafa;
    --gold-color: #C7A64A;
    --sub-heading-color: #5C501F;
    --font-family-body: "Roboto", sans-serif;
    --h1-font-family: "Anonymous Pro", sans-serif;
}

.navbar-brand {
    font-family: var(--h1-font-family);
    color: var(--gold-color);
}
```

## Future features
- Navbar style when scrolling
- Gallery with better functionality
- Register and login system
- Bookings system
- Access My Membership Information
- Track My Workout Progress
- Purchase Supplements Online
- Online support

## Assistance from AI
During the development of this project, AI-powered tools were utilized to assist with certain aspects, including the design and implementation of a transparent navbar using Bootstrap. This assistance helped to optimize the solution and implement best practices in web development.

### Specific AI Contributions
- **Bootstrap Navbar Transparency**: AI provided guidance on how to adjust the `background-color` property using RGBA values to achieve the desired level of transparency in the navbar.

## Credits and Acknowledgments

### Images
The images used in this project are sourced from various providers and are used under their respective licenses. Here are the details:

- **Logo**:
  - **Source**: [Pixabay](https://pixabay.com/illustrations/ai-generated-woman-workout-gym-8703055/)
  - **Artist**: [Artist's Name](Ai Generated Woman Workout royalty-free stock illustration.)
  - **License**: [License Details](https://pixabay.com/service/license-summary/)




