Personal Website - Qwanell Walker Lewis

About the Website

This is my personal website. It introduces me as a second-year student at the T.A. Marryshow College who is aspiring to become a freelancer in the cyber security field. It includes an About section, a Portfolio with a video and a skills table, and a Contact section.

**Live site:** https://qwanellwalker15.github.io/personal-website-02/

Summary of the Redesign

I redesigned my original website to improve its structure, appearance, usability and responsiveness. The main improvements were:

- Rebuilt the page with semantic HTML5 elements (`header`, `nav`, `main`, `section`, `article`, `figure`, `footer`)
- Added the viewport meta tag so the site scales correctly on phones
- Moved the stylesheet into a `css/` folder
- Added an online image from Unsplash alongside my local profile photo
- Wrote more descriptive alt text for images
- Made the video, images and table flexible so they fit any screen
- Added a mobile-friendly navigation menu
- Replaced the outdated table border attribute with CSS styling
- Made the email address a clickable `mailto:` link
- Added a footer
- Added HTML and CSS comments throughout

Technologies Used

- HTML5
- CSS3 (Flexbox, media queries, relative units)
- Git and GitHub (branches, commits, Pull Requests)
- GitHub Pages (hosting)

Directory Structure

 How to View the Website

- **Online:** Visit https://qwanellwalker15.github.io/personal-website-02/
- **Locally:** Download or clone the repository and open `index.html` in a web browser.

 Responsive Design Approach

I used a mobile-first approach. The base CSS is written for phone screens, and media queries add layout changes for larger screens:

- **Mobile (under 768px):** Navigation links are stacked in a column so they are easy to tap, and sections fill the screen width.
- **Tablet (768px and wider):** Navigation becomes a horizontal row, and spacing and the profile photo size increase.
- **Desktop (1024px and wider):** Text size and spacing increase, and the content is centred with a maximum width so lines stay readable.

Other techniques used: Flexbox for the navigation, `max-width: 100%` and `height: auto` for images, an `aspect-ratio` wrapper so the video scales properly, and `rem` units for sizing.

 Image Credits

- **Profile photo** (`images/profile.jpg`): my own photo.
- **Padlock on keyboard image:** "Brown padlock on black computer keyboard" by [FlyD](https://unsplash.com/@flyd2069) on [Unsplash](https://unsplash.com/photos/brown-padlock-on-black-computer-keyboard-FGH69mi53Mw), used under the [Unsplash License](https://unsplash.com/license).
- **Video:** embedded from YouTube.

Reflection
For this assignment, I redesigned my personal website to make it better structured, easier to use and responsive. My original site only used `nav` and `section` elements, had no media queries, and kept its stylesheet in the root folder. I rebuilt the page with semantic HTML5 elements like `header`, `main` and `footer`, moved my CSS into a `css` folder, and added media queries so the site works on mobile, tablet and desktop. I also added an online image from Unsplash with proper attribution, better alt text, and comments in my HTML and CSS.

One challenge was finding an online image I was allowed to use. I first tried a Google image and a paid Unsplash+ photo, and I learned that I must check the licence and the photographer before using any image. Another challenge was doing everything through GitHub's website instead of the terminal, so I had to learn how to create a branch, move a file and commit from the browser.

I learned that branches let me work safely without changing my live site on main, and that small commits with clear messages show my progress. I also learned that a Pull Request lets me review my changes before merging them. Next time, I would test my site on different screen sizes more often while I work.
