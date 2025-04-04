# Web Development Project  

## Overview  
This is a **React-based web application** that features a responsive and visually appealing UI. The project incorporates various **CSS effects** to enhance the design and utilizes **React components** for better structure and maintainability.  

## Features  

### 🌟 CSS Effects Used  
- **Custom Fonts**: Imported from Google Fonts (`Dancing Script`, `Comfortaa`, `Sedan`, `Wellfleet`).  
- **Background Effects**:  
  - Fullscreen background image (`background-attachment: fixed;`)  
  - Gradient overlays (`linear-gradient()`)  
- **Hover Effects**:  
  - Changing **border color** on hover (e.g., yellow for `.about-right`, `.about-left`, `#ContactUs`).  
  - **Text hover effects**: Color change to yellow for headings and links.
  - **Smooth Scroll**: Navigates Smoothly to desired component

- **Border Styling**:  
  - Custom **border-radius** for elements like `.about-left`.  
  - White borders with hover color transitions.  
- **Responsive Layout**:  
  - **Floating elements** (e.g., `.about-right` and `.about-left`).  
  - **Flexbox/grid** for structured positioning.  
- **Image Effects**:  
  - Background images set to `cover`.  
  - Cursor change on hover for better user interaction.  

### ⚛️ React Features Used  
- **Component-based architecture**:  
  - Organized into multiple components (`Navbar`, `Header`, `AboutUs`, `Menu`, `ContactUs`, `SignUp_Login`, `Footer`).  
- **Reusable Components**:  
  - Each section is a separate React component, making the code modular.  
- **Props & State Management**: (if applicable, you can mention how state is handled)  
- **CSS Modularization**:  
  - Each component has its own CSS file (e.g., `aboutus.css`).  
- **JSX for HTML-like structure in JavaScript**.  

## 🚀 How to Run the App  

### Prerequisites  
Ensure you have **Node.js** and **npm (or yarn)** installed on your machine.  

### Steps to Start the App  
1. Clone the repository:  
   ```bash
   git clone <repository_url>
   cd <project_directory>
   ```
2. Install dependencies:  
   ```bash
   npm install
   ```
3. Start the development server:  
   ```bash
   npm start
   ```
4. Open your browser and go to:  
   ```
   http://localhost:3000
   ```

## 📂 Project Structure  
```
/public
  ├── images/ (Contains images used in the project)
  ├── index.html
/src
  ├── components/
      ├── Navbar/
      ├── Header/
      ├── AboutUs/
      ├── Menu/
      ├── ContactUs/
      ├── SignUp-Login/
      ├── Footer/
  ├── App.js
  ├── App.css
  ├── index.js
.gitignore
package.json
README.md
```

## 🛠️ Technologies Used  
- **Frontend**: React.js, JSX, CSS  
- **Styling**: Google Fonts, CSS Animations, Flexbox/Grid  

---

Enjoy coding! 🚀✨
