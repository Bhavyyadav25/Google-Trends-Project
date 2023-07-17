# Google Trends CLI
Google Trends CLI is a command-line interface application written in Go that fetches and displays the daily trending searches from the Google Trends website. The CLI retrieves XML data and provides a clear overview of the current popular search terms, along with their corresponding links, headlines, and article URLs.

## Features
Fetches XML data from the Google Trends website using the official Google Trends API.
Parses the XML response to extract relevant information such as search terms, links, headlines, and article URLs.
Presents the retrieved data in a structured and easy-to-read format in the command-line interface.

## Prerequisites
Before running the Google Trends CLI, ensure that you have the following installed on your system:

- Go programming language (version X.X.X)
- Internet connectivity to fetch data from the Google Trends website

##Usage
Clone the repository to your local machine:
git clone https://github.com/your-username/google-trends-cli.git

Navigate to the project directory:
cd google-trends-cli

Build the project:
go build

Run the application:
./google-trends-cli

The CLI will display the current Google search trends, including the search term, link to the trend, headline, and link to the corresponding article.

##Acknowledgments
Google Trends API: https://trends.google.com/
