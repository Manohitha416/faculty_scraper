# faculty_scraper
Faculty Directory Scraper
This Python script scrapes the Full-Time Faculty information from the Montclair University School of Computing Staff Directory webpage.
It extracts each faculty member's name, title, phone number, email address, and office location, and organizes the data into a structured table using pandas.

🚀 Features
Fetches live HTML content from the website

Extracts:

Faculty Name

Title

Phone Number

Email Address

Office Location

Displays the information neatly in a pandas DataFrame

🛠 Requirements
Python 3.x

Required libraries:

requests

re (regular expressions - standard library)

pandas

You can install the required libraries using:

bash
Copy
Edit
pip install pandas requests
📜 Usage
Clone this repository or download the script.

Run the script:

bash
Copy
Edit
python faculty_scraper.py
The extracted faculty directory will be displayed in a tabular format.

🧩 Code Overview
requests is used to fetch the webpage HTML content.

re (regular expressions) is used to locate and extract specific HTML sections and fields.

pandas is used to organize the extracted data into a readable and analyzable table.

⚠️ Note
This script specifically extracts the Full-Time Faculty section only.

If the webpage structure changes in the future, the regular expressions may need updating.

There is a minor correction made:
The column 'tile' was corrected to 'title' while building the DataFrame.

📬 Output Example

name	title	phone	email	location
John Doe	Professor	123-456-7890	john@domain.edu	Room 101
Jane Smith	Lecturer	987-654-3210	jane@domain.edu	Room 202