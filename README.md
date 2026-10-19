# Gaming Through the Years — Milestone 2

Gaming Through the Years is a seven-page informational website about gaming culture. Its pages are Home, Gaming, Hardware, Game Reviews, Game Sources, Older Games, and Contact. The project builds on the earlier proposal, wireframes, and content inventory. Each page has a semantic header, navigation, main content, and footer. The navigation includes a visible current-page indicator and links to every page.

The visual design uses a dark blue brand color (#243b53), a light blue-gray background (#f5f7fa), white sections, and an amber accent (#b45309). Arial, Helvetica, and sans-serif fallback fonts provide readable text across devices. Headings use larger sizes than body copy, with generous line spacing for comfortable reading. All presentation is managed by one shared external stylesheet at css/styles.css.

The layout is mobile-first: navigation links stack vertically and content cards appear in a single column on small screens. At 42rem, a CSS media query switches the navigation to a horizontal arrangement and content cards to two columns. At 65rem, the card layout expands to three columns. Flexbox powers the navigation, while CSS Grid arranges the content cards.

The site includes optimized original images of a gaming setup and Elden Ring gameplay, with descriptive alternative text and image dimensions. The Contact page retains an accessible demonstration form; it does not yet send messages. Before submitting, I will check the HTML pages using the W3C Nu HTML Checker and test the site at mobile, tablet, and desktop widths. Version history is maintained in Git.
