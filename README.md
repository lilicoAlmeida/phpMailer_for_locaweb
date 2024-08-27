# PHP Mailer for Locaweb

This repository contains a PHP script designed to send emails with attachments using the PHPMailer library, specifically configured for use with Locaweb's SMTP servers.

## Features

- Send emails with attachments.
- Fully customizable SMTP settings, including host, port, encryption type (SSL/TLS), and credentials.
- User-friendly HTML form for input, including fields for email, subject, message, and file attachments.
- Error logging and handling for better troubleshooting.

## Installation

1. **Clone the repository:**
  
   git clone https://github.com/lilicoAlmeida/phpMailer_for_locaweb.git
   
   cd phpMailer_for_locaweb
   
## Download and include PHPMailer: Make sure you have PHPMailer installed. You can download it from PHPMailer GitHub repository or install it using Composer:

composer require phpmailer/phpmailer

Update your SMTP settings: Open the index.php file and update the SMTP settings (host, port, username, password, etc.) according to your Locaweb account.

## Usage

Navigate to the project directory and run it on your local server (e.g., XAMPP, WAMP, etc.).

Access the form in your browser: Open http://localhost/phpMailer_for_locaweb/index.php and fill out the form.

Send an email: Enter the required information (email, subject, message, and attachment) and click "Send". The script will process the input and attempt to send the email via Locaweb's SMTP server.

## Troubleshooting

If you encounter issues with sending emails, ensure that:
Your SMTP credentials are correct.
The Locaweb SMTP server is accessible from your network.
PHP is configured to allow file uploads if you plan to attach files.
Check the PHP error log for detailed error messages.
Contributing
Feel free to fork this repository and submit pull requests. If you encounter any issues or have suggestions for improvements, please open an issue on GitHub.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
