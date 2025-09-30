# Mini-accordion-sample

This project is a simple Accordion UI component built using only HTML and CSS. It demonstrates how to create an expandable/collapsible section design (commonly used in FAQs, menus, and dashboards) without any JavaScript.

✨ Features

✅ Pure HTML & CSS implementation (no JavaScript).
✅ Modern, clean design using Google Fonts (Inter).
✅ SVG icons included for better visuals.
✅ Responsive container width.
✅ Example content for Web Development topics.

📂 Project Structure
accordion-sample/
├── index.html   # Main HTML file with accordion structure
├── styles.css   # (Optional) You can extract inline CSS here
└── README.md    # Project documentation

🚀 Usage

1.Clone or download this repository.
2.Open index.html in your browser.
3.You’ll see a 3-section accordion:

   =>Introduction to Web Development

   =>What is an Accordion Component?

   =>Benefits of Using Accordions

🖼️ Demo
Here’s how the accordion looks:

<img width="862" height="801" alt="image" src="https://github.com/user-attachments/assets/b5289456-d4e3-4d7b-a7a7-52713e5c9e5a" />



⚙️ How It Works

=>The accordion is styled using CSS Grid and toggle classes (.open) for the expanded state.
=>By default, the first accordion item is open (class="item open").
=>The hidden content is wrapped inside .hidden-box, which is displayed only when the parent .item has the .open class.
=> css
.hidden-box {
  display: none;
}
.open .hidden-box {
  display: block;
}

🎨 Customization

*Update colors, font sizes, and spacing in the <style> section.
*Replace the SVG icons with your own icons if needed.
*Extract inline styles into a separate styles.css file for cleaner structure.

📖 Example Use Cases

*FAQ sections
*Course/module outlines
*Documentation menus
*Dashboards with collapsible info
