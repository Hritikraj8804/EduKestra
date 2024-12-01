## EduKestra

### Overview

The **EduKestra** project is designed to provide a platform where students can is a fully automated platform for managing study content and student subscriptions. This project integrates **GitHub** and **Kestra** to automate the process of notifying students about newly added assignments, tests, and study materials, request new topics to be added to educational content. Request page allows students to submit requests with the following information:
- **Name**: The student's name.
- **Email**: A valid email address.
- **Requested Topic**: A description of the topic they'd like to see included.

This page also contains a user-friendly form for submitting requests, which ensures a seamless experience for students across all devices with a responsive design.

### Key Features

1. **Responsive Design**:
   - The page is fully responsive, meaning it adjusts seamlessly to various screen sizes, including desktops, tablets, and mobile phones.
   - The layout automatically switches between a desktop version with horizontal navigation and a mobile version with a vertical    navigation menu.
    ![Edukestra](/styles/img/mobile_ham.png)
    ![Edukestra](/styles/img/mobil_subs.png)
    ![Edukestra](/styles/img/mobil_menu.png)
    ![Edukestra](/styles/img/edukestra.png)


2. **User-Friendly Navigation**:
   - A fixed top navigation bar that includes links to other sections of the platform (Home, Courses, Test, Roadmap, Contact).
   - A **Hamburger Menu** is used for mobile and tablet views to save space and keep the navigation clean.
    ![Edukestra](/styles/img/mobil_menu.png)
    ![Edukestra](/styles/img/mobil_content.png)

3. **Form for Requesting Topics**:
   - The page includes a simple and clear form for submitting requests, making it easy for  students to share their thoughts on new topics they'd like to be included in the curriculum.
   - The form includes input fields for the student’s name, email, and a text area for describing the requested topic.
   - A "Submit Request" button sends the form data when clicked.
   ![Edukestra](/styles/img/req.png)
   ![Edukestra](/styles/img/subscribed.png)

4. **Footer with Contact Information**:
   - The footer includes contact details, allowing users to get in touch for support or inquiries.
   - The contact link is active and opens a default email client when clicked.

5. **Animations and Hover Effects**:
   - Subtle animations and hover effects are applied to buttons, links, and form elements to improve interactivity and user experience.
   - Hovering over form inputs and buttons triggers a slight color change, enhancing feedback.

### Technologies Used

- **HTML**: Used to structure the page and form elements.
- **CSS**: Custom styles and responsive design to ensure the page looks great on all screen sizes.
- **JavaScript**: For handling the dark mode toggle and other small dynamic interactions (if required).
- **Flexbox & Grid Layout**: For creating a responsive, modern design using CSS layout techniques.
- **Media Queries**: Ensures that the page adapts to different devices, with particular focus on mobile-first design.
- **Git**: Used to Manages changes to source code over time.
- **GitHub**: Provides a platform for developers to collaborate on projects.
- **Kestra**: Automates data pipelines and workflows.
- **Docker**: Packages applications and their dependencies into portable containers.

### How It Works

1. **Request Form**:
   - Students fill out the form by entering their name, email, and the topic they would like to request.
   - Once submitted, the data will be sent to the backend for processing (can be linked to an API for further action).
   
2. **Navigation**:
   - On larger screens (desktops), the navigation menu is displayed horizontally, providing easy access to various sections of the platform.
   - On mobile and tablet screens, the menu switches to a hamburger-style menu to save space and improve usability.

3. **Footer**:
   - The footer at the bottom contains basic contact information and links to contact us via email.
   - It stays fixed at the bottom of the screen on all devices, ensuring it’s always accessible.

### Future Enhancements

- Integrate form submission with an API or database for storing student requests.
- Implement email notifications to confirm the receipt of requests.
- Improve the user interface with more advanced animations and transitions.

---

This project offers a great foundation for building educational platforms, enabling easy interaction between students and content creators. The responsive design ensures that students can use the platform on any device, whether at home or on-the-go.
