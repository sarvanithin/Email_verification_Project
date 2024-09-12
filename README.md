# Email Verification Application

## Overview
This project allows you to verify single and bulk email addresses using Flask, SMTP, and DNS checks.

## File Structure
- **app.py**: Main application file
- **templates/**: HTML templates for frontend
- **static/**: CSS, JS, and image resources
- **requirements.txt**: Dependencies required for the project
- **README.md**: Documentation for setup and usage

## Setup
1. Install dependencies:
2. Run the application
3. Access the app in your browser at `http://127.0.0.1:5000/`.

## Usage
- **Single Email Verification**: Enter an email and check if it's deliverable.
- **Bulk Email Verification**: Upload an Excel file to verify multiple emails at once.

## Notes
- SMTP checks might be blocked by some email servers due to security settings.
- Ensure you have an active internet connection for DNS and SMTP lookups.
