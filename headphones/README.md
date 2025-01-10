# Headphones Webpage

Welcome to the **Headphones Webpage**, a fictional online store showcasing a wide variety of headphones. This project demonstrates how to build a simple, modern e-commerce webpage with a focus on clean design and user experience.

---

## **Description**

This is a fictional online store designed to showcase and sell headphones. It includes a homepage with featured products, what we do section, about us section, and a contact us section. The project is intended to serve as an example of an e-commerce website with a focus on product display, usability, and responsive design.

---

## **Features**

1. **Responsive Design**:
   - The webpage seamlessly adapts to mobile screens when the screen width is **480px or less**.
   - All elements are reorganized for an optimal user experience on smaller devices.

2. **Hover/Active States**:
   - **Links**: On hover or active, the color changes to `#FF6565`.
   - **Buttons**: On hover or active, the button opacity changes to `0.9`.

3. **Content Centering**:
   - All content is centered within a **maximum width of 1000px** on the page.

---

## **Technical Details**

### 1. **Fonts**
   - Fonts used in the Figma design:
     - **Source Sans Pro**: [Download Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
     - **Spin Cycle OT**: [Download Spin Cycle OT](https://fontsgeek.com/fonts/Spin-Cycle-OT-Regular)
   - Ensure these fonts are installed on your system for proper rendering.

### 2. **CSS Implementation**
   - The hover/active states for links and buttons are implemented with the following styles:
     ```css
     /* Links hover/active state */
     a:hover, a:active {
         color: #FF6565;
     }

     /* Buttons hover/active state */
     button:hover, button:active {
         opacity: 0.9;
     }
     ```

   - The maximum width of content is defined using the following rule:
     ```css
     /* Center content and set max width */
     .container {
         max-width: 1000px;
         margin: 0 auto;
     }
     ```

---

## **Design Notes**

- Some Figma measurements may include float values. **Values were rounded** for simplicity and consistency.
- The mobile version of the webpage switches at a screen width of **480px or less** using a CSS media query:
  ```css
  @media (max-width: 480px) {
      /* Mobile-specific styles go here */
  }