# Simplify Meeting Notes

## Public GitHub Repository Link
[Simplify Meeting Notes](https://github.com/sajalregmi/simplify-meeting-notes)

## Brief Description
This project converts a Markdown meeting note into a well-formatted Google Doc using the Google Docs API

## Setup Instructions
1. **Clone or Download** this repository from the link above.
2. Open the `.ipynb` notebook in **Google Colab**.
3. Ensure that the required dependencies are installed (see below).
4. Authenticate with your Google account when prompted.

## Required Dependencies
- `google-api-python-client`
- `google-auth-httplib2`
- `google-auth-oauthlib`
- `re` (usually included by default)

If not installed, install them using:!pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib


## How to Run in Colab
1. Open the notebook in **Google Colab**.
2. Run the first cell to install and import dependencies (if needed).
3. Run the second cell to **authenticate** with your Google account.
4. Run the final cell to create a new Google Doc in your Drive and populate it with the transformed Markdown.

**Note:** This script relies on **Colab authentication** (`auth.authenticate_user()`), which only works inside Google Colab. Running this code outside of Colab may require a different authentication flow.

---
Thank you for using this Markdown-to-Google-Docs converter!
