# EduKeastra

EduKeastra is a fully automated platform for managing study content and student subscriptions. This project integrates **GitHub** and **Kestra** to automate the process of notifying students about newly added assignments, tests, and study materials.

## Features
- **Subscription Management**: Students can subscribe to the platform by providing their Telegram ID and email.
- **Content Updates**: Add assignments, test papers, or study materials to the repository, and they are automatically processed.
- **Automated Notifications**: Subscribers receive an email notification whenever new content is added to the platform.
- **GitHub Integration**: All data, including subscribers and content, is stored and managed in the GitHub repository.
- **Kestra Workflow Automation**: Automates the task of processing content updates and notifying subscribers.

---

## Repository Structure

```plaintext

├──kestra.yml                    # Kestra workflow
├── subscribers.txt              # Stores the Telegram IDs of subscribed students
├── previous_hash.txt            # Stores the previous_hash
├── index.html                   # Frontend HTML for the subscription page
├── styles/
│   └── styles.css               # Stylesheet for the subscription page
├── README.md                    # Project documentation
