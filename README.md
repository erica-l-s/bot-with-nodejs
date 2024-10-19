

# Job Vacancy Search Application

This project is a web application that allows users to search for job vacancies from the website Yourfirm.de by entering keywords. The results can be downloaded as an Excel file. The application is built using **Node.js** for the backend, and **JavaScript, HTML, and CSS** for the frontend.

## Features

- **Search Vacancies**: Users can enter one or more keywords (separated by commas) to search for job vacancies.
- **Real-time Feedback**: Provides feedback to the user during the search, including success messages when vacancies are found and error messages when there are no vacancies or issues with the search.
- **Download Results**: Users can download the search results as an Excel (.xlsx) file with a customizable filename.

## Technologies

### Backend

- **Node.js** with Express for handling requests and responses.
- **Axios** for scraping job vacancy data from the website Yourfirm.de.
- **Cheerio** for parsing and extracting the job data from the HTML.
- **xlsx** for converting search results into an Excel file.

### Frontend

- **HTML/CSS** for layout and design.
- **JavaScript (ES6+)** for making API requests and handling the user interface.
- **Fetch API** for communicating with the backend.

## Installation

### Prerequisites

- Node.js and npm installed.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/job-vacancy-search.git

2. Navigate to the project directory:
   ```bash
   cd job-vacancy-search
   
3. Install the required dependencies:
   ```bash
   npm install

The server will run on ``` http://localhost:3000.```

Link: https://bot-with-nodejs.onrender.com
