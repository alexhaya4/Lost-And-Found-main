# Lost-And-Found

A web-based Lost and Found platform built using PHP, CSS, JavaScript, and HTML.

## Overview

**Lost-And-Found** is a full-stack web application designed to facilitate the reporting and searching of lost and found items. Users can submit reports for items they've lost or found, browse recent submissions, and connect with others to recover lost belongings.

## Features

- **User-Friendly Submission Forms**: Report lost or found items with details and optional images.
- **Search Functionality**: Quickly find items using keywords, categories, dates, and locations.
- **Responsive Design**: Works seamlessly across desktops, tablets, and mobile devices.
- **Administrative Panel**: For reviewing, approving, or removing reports (if enabled).
- **Email Notifications**: Connect users who report found items with those who have lost them (if mail features are configured).

## Technologies Used

- **Backend**: PHP
- **Frontend**: HTML, CSS, JavaScript
- **Styling**: CSS for custom design and layout
- **Database**: MySQL (or compatible) for storing reports and user data

## Getting Started

### Prerequisites

- PHP 7.x or higher
- MySQL database
- Web server (e.g., Apache, Nginx)
- Composer (optional, if dependencies are managed)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/alexhaya4/Lost-And-Found-main.git
   cd Lost-And-Found-main
   ```

2. **Set up the database:**
   - Import the provided SQL file (if available) into your MySQL server.
   - Update the database connection details in the configuration file (e.g., `config.php`).

3. **Configure environment:**
   - Ensure your PHP environment has access to the required extensions (e.g., PDO, mysqli).
   - Configure any mail settings if email notifications are enabled.

4. **Launch the application:**
   - Place the project folder in your web server's root directory.
   - Access the app in your web browser (e.g., `http://localhost/Lost-And-Found-main/`).

## Usage

- **Report Lost Item:** Fill out the "Report Lost" form with item details, date, and location.
- **Report Found Item:** Use the "Report Found" form to add found items.
- **Browse/Claim:** Search or browse recent reports, and contact the lister if you find a match.

## Folder Structure

- `index.php` — Main landing page
- `lost.php` — Lost item report form
- `found.php` — Found item report form
- `search.php` — Search and browse items
- `admin/` — Administrative tools (if present)
- `assets/` — CSS, JS, images, and other static assets
- `config.php` — Configuration and database connection

## Contributing

Contributions are welcome! Feel free to submit issues, fork the repository, and open pull requests.

## License

This project is open-source. See `LICENSE` for details.

## Contact

For support or inquiries, open an issue or contact [alexhaya4](https://github.com/alexhaya4).
