# AI-Resume-Builder
A dynamic and interactive web application that helps users create professional resumes, with AI-assisted content generation for key sections. This tool is especially geared towards students and professionals, enabling them to quickly draft impactful and industry-relevant resumes.

✨ Features
Real-time Resume Preview: Instantly see your resume take shape as you fill in the details.

AI-Assisted Content Generation: Leverage the power of the Gemini API to automatically generate drafts for:

Professional Summary/Objective

AI/ML Concepts & Knowledge list

Soft Skills list

Project Descriptions

Work Experience Descriptions

Dynamic Sections: Easily add, remove, and manage multiple entries for Education, Projects, Internships/Work Experience, and Certifications.

Tailored for AI/ML Resumes: Input fields are designed to capture specific details relevant to Computer Science with AI/ML specialization.

PDF Export: Download your generated resume as a clean, professionally formatted PDF document.

Responsive Design: Accessible and usable across various devices (desktop, tablet, mobile).

🚀 Technologies Used
Frontend: HTML5, CSS3 (Tailwind CSS via CDN), JavaScript

AI Integration: Google Gemini API (gemini-2.5-flash-preview-05-20)

PDF Generation: html2pdf.js library

Hosting: GitHub Pages

Version Control: Git & GitHub

💡 How the AI Integration Works
The "Generate with AI" buttons trigger a call to the Google Gemini API. The prompt sent to the AI includes relevant context from other filled fields in your resume (e.g., your name, programming languages, project titles) to help the AI generate more personalized and relevant text for that specific section. This helps overcome writer's block and provides a strong foundation for you to refine.

⚙️ Local Setup
To run this application on your local machine:

Clone the Repository (or download index.html):

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

(Replace your-username and your-repo-name with your actual GitHub details.)

Open in Browser:

Simply open the index.html file in your preferred web browser.

Recommended: Use the Live Server extension for VS Code for a more streamlined development experience (auto-reloads on save).


🔮 Future Enhancements
Themed Templates: Offer different resume design templates for various industries or styles.

Data Persistence: Implement local storage or a simple database (e.g., Firebase Firestore) to save user data, allowing them to return and edit their resume later.

Improved AI Customization: Allow users to provide more specific prompts or keywords for AI generation.

Grammar and Spell Check: Integrate a tool for proofreading the generated content.

More Output Formats: Add options to export to DOCX or JSON.

🤝 Contributing
This project is a personal initiative, but feel free to fork the repository, experiment, and make it your own!

📄 License
This project is open-source and available under the MIT License.
