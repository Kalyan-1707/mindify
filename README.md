## Mindify - React Dashboard

This repository aims to develop a **React-based calendar dashboard** that calculates the **cost of meetings** based on participant information and user-defined rates.

### Key Features

* Estimates the **financial impact** of meetings by considering:
    * **Participant hourly rates**
    * **Meeting duration**
* Integrates with existing calendar platforms (future development).

### Getting Started

1. **Prerequisites:**
    * Node.js and npm installed ([https://nodejs.org/en](https://nodejs.org/en))
2. **Clone the repository:**

```bash
git clone https://github.com/Kalyan-1707/mindify
```

3. **Install dependencies:**

```bash
npm install
```

4. **Start development server:**

```bash
npm run dev
```

This will open the development server at http://localhost:5173/.

### Development

The project uses the following folder structure:

```
src/
  - pages/ - React components for different views (e.g., MeetingCost.jsx)
  - components/ - Reusable components (e.g., MeetingForm.jsx)
  - api/ - API endpoints for data fetching or calculations (e.g., costCalculation.js)
  - App.jsx - Main application component
  - index.html - Entry point for the application
```


### Contribution Guidelines

* Fork the repository and create a pull request for your changes.
* Ensure your code adheres to the existing code style and formatting.
* Add clear comments and documentation for your contributions.
* Consider testing your changes before submitting a pull request.

We appreciate any contributions that improve the functionality and usability of this project.
