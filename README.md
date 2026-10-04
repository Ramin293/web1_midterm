# OrbitFood

OrbitFood is a restaurant website for the Web Technologies I midterm. The design is based on our [Figma wireframes](https://www.figma.com/design/33DjxGXbiNhiNw5JFCWh98/Task-5-StudyFlow-Wireframes?node-id=0-1).

[Open the current website](https://ramin293.github.io/web1_midterm/)

## Current progress

Three of the six main pages are ready:

- `index.html`: introduction, restaurant photograph and featured dishes.
- `menu.html`: starters, mains and desserts with category links.
- `dish.html`: pumpkin risotto, ingredients and related dishes.

The shared navigation, footer, colours and responsive layout are also in place. Reservation, About and Order currently contain only a header, navigation and a coming-soon message. They still need to be implemented.

## What is left

- Build the reservation page with date, time, guest count, name and an optional note. Add labels and basic HTML validation.
- Build the About page with the restaurant story, team, location and an HTML table of opening hours.
- Build the order page with dish selection, portions and pickup time.
- Add demo result pages for both forms. Make it clear that no real booking, order or payment takes place.
- Add the styles and images needed for these pages, then check all navigation links and mobile layouts.
- Update this README when the remaining pages are finished.

Continue using the Figma layout and the existing shared styles. The final version needs at least five complete pages, a table, a form, semantic HTML, Flexbox, CSS Grid, positioning, two responsive breakpoints and Bootstrap grid and utility classes.

## How to run

Download the project and open `index.html` in a browser. There is no installation or build step. Bootstrap and the current photographs are stored locally.

## Technologies

HTML, CSS and Bootstrap 5.3.8. Custom styles are in `css/style.css`.

The existing pages use Flexbox for navigation and buttons, CSS Grid for food cards, and Bootstrap containers, rows and columns. The label on the main photograph uses relative and absolute positioning. Media queries at 991px and 767px adjust the tablet and phone layouts.

Keep the remaining work within the topics covered before the midterm. No custom JavaScript or backend is planned. OrbitFood is fictional, and the prices and photographs are part of the student project.

## Publishing

GitHub Pages publishes the `main` branch from `/ (root)`. Pushing changes to `main` updates the website after deployment.

## Sources

- [Bootstrap](https://getbootstrap.com/docs/5.3/). Its licence is in `bootstrap/LICENSE`.
- [Restaurant interior](https://images.unsplash.com/photo-1517248135467-4c7edcad34c4) from Unsplash.
- [Risotto](https://unsplash.com/photos/7TaFlRyAhSQ) by Luna Hu on Unsplash.
- [Sea bass](https://unsplash.com/photos/jMwvJ5aj5eA) by Patrick Browne on Unsplash.
- [Fruit tart](https://unsplash.com/photos/UcYoEO5nSNE) by Toa Heftiba on Unsplash.
- [Mushroom toast](https://unsplash.com/photos/83Lq4rDrx_o) by Sofia Holmberg on Unsplash.

AI assistance was used for implementation and checking the project.
