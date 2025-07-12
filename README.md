# Stackit-App 🚀
# StackIt – Professional Q&A Platform 

## Overview

StackIt is a modern, professional Q&A platform inspired by Stack Overflow, designed for developers to ask questions, share answers, and collaborate. This project was built for the Odoo Hackathon and focuses on a clean, responsive frontend user experience.

https://stackit-ashen.vercel.app/

## Features 🚀

- **Ask and Answer Questions:** Users can post questions, provide answers, and interact with the community.
- **Tagging System:** Organize questions by relevant tags for easy discovery.
- **Voting:** Upvote questions and answers to highlight valuable contributions.
- **Filtering & Search:** Find questions by keywords, tags, unanswered status, votes, or recency.
- **User Profiles:** View top users, their stats, and recent activity.
- **Job Board:** Explore developer job postings.
- **Responsive UI:** Fully responsive design for desktops and mobile devices.
- **Theme Toggle:** Switch between dark and light modes.
- **Notifications:** Instant feedback for actions like posting questions or answers.
- **Keyboard Shortcuts:** Enhanced productivity with quick navigation.

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Backend:** _Planned_ (see note below)
- **No frameworks or libraries required for the frontend.**

## Installation & Running

1. **Clone the repository:**
2. 
2. **Open `index.html` in your browser.**
- No build step required.
- All functionality is client-side.

## Project Structure

| File/Folder     | Description                                |
|-----------------|--------------------------------------------|
| `index.html`    | Main HTML file with embedded CSS & JS      |
| `README.md`     | Project documentation                      |
| `assets/`       | (Optional) Images, icons, or extra styles  |

## How It Works

- All data (questions, answers, users, jobs) is stored as JavaScript objects for demo purposes.
- The UI is dynamically updated using DOM manipulation.
- Actions like posting questions/answers or voting update the in-memory dataset and UI instantly.

## Limitations & Future Work

- **Backend Integration:**  
_We were not able to fully integrate the backend as part of this hackathon submission._  
All data is currently stored in-memory on the frontend, so changes are lost on refresh and there is no persistent storage or authentication.  
In future versions, we plan to:
- Connect to a real backend (Node.js/Express, Django, or Odoo backend)
- Implement user authentication and authorization
- Use a database for persistent storage
- Enable real-time updates and notifications

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open source and available under the MIT License.

## Acknowledgements

- Built for the Odoo Hackathon 2025
- Inspired by Stack Overflow and other Q&A platforms

**Thank you for checking out StackIt!**  
For questions or suggestions, feel free to open an issue or contact the team.

- Gladdin Shruthi J
- Rijesh Krishna
- Surya KP
- Siddharth V
