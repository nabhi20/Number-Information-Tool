# Number-Information-Tool
A Python CLI tool with one-time animated banner, colorful terminal UI, mobile number validation, API lookup, and formatted JSON results. Designed for cybersecurity demonstrations and smooth user interaction.
Here is a cleaner, professional, well-structured README.md written in proper English:


---

📱 Phone Information Lookup Tool

A terminal-based Python tool that displays a one-time animated banner, accepts a 10-digit mobile number, retrieves information from an external API, and presents the results in a colorful and readable format.


---

🚀 Overview

This script provides a visually appealing command-line interface for looking up information associated with Indian mobile numbers.
It includes:

A one-time sliding animated banner

Colorful text animations using colorama

Clean user prompts for number input

API integration for fetching phone-related data

Smooth “Generating…” progress animation

Formatted JSON output display

Error handling for invalid inputs and API failures



---

✨ Features

🎬 Animated Banner – Displays only once when the program starts

🌈 Colorful Output – Random color effects for text

📲 Simple Input – Enter a 10-digit phone number

🔍 API Fetching – Retrieves number information from


🔄 Loading Animation – Clean and smooth progress indicator

📊 Formatted Results – Pretty-printed JSON output

🔁 Repeat Use – After one lookup, enter another number without restarting

🛡️ Error Safe – Handles invalid numbers, failed API calls, and malformed responses



---

📦 Requirements

Install the required dependencies:
pkg update -y && pkg upgrade -y
pkg install python -y
pkg install python-pip -y
pip install requests colorama


---

▶️ How to Run

1. Make sure Python 3 is installed.


2. Install dependencies.


3. Run the script:



python3 script.py

You will see the animated banner once, followed by a prompt to enter phone numbers.


---

📝 How It Works

1. Enter Number

Type any 10-digit mobile number.
If the input is invalid, the script will notify you.

2. Processing

A loading animation appears while the script contacts the API.

3. Results

The fetched information is displayed in a clean and colorful JSON format.

4. Continue

You can enter another number or type EXIT to quit.


---

📁 Script Structure

script.py     # Main Python file
README.md     # Documentation


---

🔧 Key Components

slide_banner_once()

Displays the animated banner when the script starts.

generating_animation()

Shows a rotating progress bar while data is being processed.

api_call(number)

Sends a request to the API and returns the response text.

show_result(parsed, number)

Prints the formatted and colorized information.


---

🛠️ Configuration Options

You can modify these in the script:

API_BASE = 
REQUEST_TIMEOUT = 20
VERIFY_SSL = False
GEN_SECONDS = 3


---

🔒 Important Notes

SSL verification is disabled by default (VERIFY_SSL=False)

The script expects JSON responses but will safely handle text replies

Certain fields are sanitized before printing



---

👨‍💻 Author

Cybersecurity With Nabhi
Telegram Channel: https://t.me/Nabhi_Informations_Channel
