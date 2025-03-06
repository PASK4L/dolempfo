# DOLE Makati Pasay Field Office Web Project

This project is a web application designed for the DOLE Makati Pasay Field Office, allowing users to fill out a submission form for various documents, such as referrals to the National Labor Relations Commission. After submission, users can generate a ready-to-print document.

## Project Structure

```
dole-makati-pasay-web
├── public
│   ├── index.html          # Main HTML document
│   └── styles
│       └── main.css       # Styles for the web application
├── src
│   ├── components
│   │   ├── Form.tsx       # Form component for document submission
│   │   └── PrintDocument.tsx # Component to format and print documents
│   ├── pages
│   │   ├── Home.tsx       # Landing page of the application
│   │   └── Submission.tsx  # Page for document submission
│   ├── App.tsx            # Main application component with routing
│   └── index.tsx          # Entry point for the React application
├── package.json            # npm configuration file
├── tsconfig.json           # TypeScript configuration file
└── README.md               # Project documentation
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd dole-makati-pasay-web
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Run the application:**
   ```
   npm start
   ```

4. **Open your browser and navigate to:**
   ```
   http://localhost:3000
   ```

## Usage

- Navigate to the Home page to access the submission form.
- Fill out the required fields in the form and submit.
- After submission, a confirmation message will be displayed along with an option to print the document.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.