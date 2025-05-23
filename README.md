# pr-E-commerce
👨‍💻 Developed By:
Sagar

📖 Table of Contents:
Project Overview

Features

Technologies Used

File Structure

HTML Code Walkthrough

Header

Navigation

Hero Section

Best Seller Section

Footer

Future Enhancements

Conclusion

📁 Project Overview:
This is a responsive e-commerce website for showcasing and selling footwear products. The site features a clean layout, a promotional hero banner, best-seller product listings, and a footer with social media links. It's designed using HTML, CSS, and Bootstrap icons for easy scalability and responsiveness.

✨ Features:
Responsive design using Bootstrap grid

Attractive hero section with promotional banner

Product section with pricing and discount display

Search input for future product filtering

Social media icons in the footer

Semantic HTML5 structure

🔧 Technologies Used:
HTML5 – for structuring the content

CSS3 – for styling and layout

Bootstrap Icons – for icons in search bar and social media

Media Queries (in media.css) – for responsive behavior

📂 File Structure:
pgsql
Copy
Edit
project-folder/
│
├── index.html
├── css/
│   ├── style.css
│   └── media.css
├── images/
│   ├── item-1.jpg to item-16.jpg
│   └── brand-1.jpg to brand-4.jpg
🧱 HTML Code Walkthrough:
✅ Header:
Contains the website logo/title and a search bar.

Uses Bootstrap's grid and utility classes for layout.

html
Copy
Edit
<header>
  <h1>Footwear</h1>
  <input type="Search" placeholder="Search">
</header>
✅ Navigation Bar:
Simple navigation menu using an unordered list.

Includes links for HOME, MEN, WOMEN, ABOUT, and CONTACT.

html
Copy
Edit
<nav>
  <ul>
    <li><a href="">HOME</a></li>
    ...
  </ul>
</nav>
✅ Hero Section:
Promotional area with a "50% OFF" sale message.

CTA button linking to the Best Seller section.

html
Copy
Edit
<section class="hero">
  <h2>HUGE SALE <span>50% OFF</span></h2>
  <a href="#seller">SHOP NOW</a>
</section>
✅ Best-Seller Section:
Displays 16 footwear products in a grid layout.

Each product shows an image, title, price, and discount using <del> tag.

Responsive across different screen sizes.

html
Copy
Edit
<section class="best-seller">
  <h3>Best Sellers</h3>
  <div class="shoes-items">
    <img src="./images/item-1.jpg">
    <h4>Boots Shoes Maca</h4>
    <span>Rs. 899</span> <del>Rs. 1499</del>
  </div>
</section>
✅ Footer:
Contains social media icons (Instagram, Twitter, Facebook) with external links.

Icons are imported from Bootstrap Icons CDN.

html
Copy
Edit
<footer>
  <h2>Follow us on</h2>
  <a href="https://www.instagram.com/"><i class="bi bi-instagram"></i></a>
</footer>
🛠️ Future Enhancements:
Add a shopping cart feature using JavaScript.

Integrate backend (Node.js + MongoDB) to handle product data dynamically.

Implement product filters and sorting options.

Add user login/register functionality.

Include partner section (currently commented out).

✅ Conclusion:
This static e-commerce website serves as a foundational project to showcase front-end development skills. It effectively demonstrates layout structure, responsiveness, and basic e-commerce UI elements.