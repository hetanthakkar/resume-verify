# RecruiterVerify

RecruiterVerify is a comprehensive tool designed to help recruiters authenticate resumes by verifying candidate details through multiple sources like LinkedIn, GitHub, app stores, and deployed websites. This tool automates the process of verifying work experience, project authenticity, and skill proficiency, giving recruiters deeper insights into a candidate's true capabilities.

## Features

### Experience Verification
- **LinkedIn Integration**: Cross-references the candidate's experience section with LinkedIn profiles to ensure accuracy.
- **Direct Summary**: Provides a concise summary of years of experience, saving recruiters from manually reviewing lengthy resumes.

### Project Verification
- **App/Play Store Links**: Extracts data from app stores to verify that candidate claims match the actual app's features, reviews, and update history.
- **Deployed Websites**: Uses web scraping to match content with the resume description, ensuring the project’s authenticity.
- **GitHub Projects**: Analyzes GitHub commit history and README files to verify the candidate’s authorship and involvement in the project.

### Overall Skill Assessment
- **GitHub Activity Analysis**: Scans the candidate’s GitHub repositories for the most coded languages and the number of lines of code written, providing a realistic evaluation of their technical skills.

## Tech Stack

### Frontend
- **React Native**: The mobile application is built using React Native, enabling recruiters to verify resumes on both Android and iOS platforms.

### Backend
- **Python**: The backend is developed using Python, leveraging its capabilities for data processing, web scraping, and API integrations.
- **Flask**: Used for building RESTful APIs to handle backend processes.
- **Selenium & BeautifulSoup**: Used for web scraping and data extraction from websites and app stores.
- **SQLAlchemy**: Database integration for storing and querying candidate data.

## Installation and Setup

### Prerequisites
- **Node.js** and **npm** (for React Native)
- **Python 3.x** and **pip**
