# WebScraper

A simple and efficient web scraping tool written in C# to extract and process data from websites. This project demonstrates the use of .NET libraries for handling HTTP requests, parsing HTML, and storing extracted data.

---

## Features

- Send HTTP requests to web pages using `HttpClient`
- Parse and navigate HTML content using `HtmlAgilityPack`
- Extract specific data points like text, images, or links
- Store scraped data in a structured format (e.g., CSV or database)
- Configurable settings for target URLs and scraping parameters

---

## Prerequisites

- **.NET SDK**: [.NET 6.0 or later](https://dotnet.microsoft.com/download)
- **Dependencies**:
  - [HtmlAgilityPack](https://www.nuget.org/packages/HtmlAgilityPack/)
  - Optionally, [CsvHelper](https://www.nuget.org/packages/CsvHelper/) for saving data to CSV

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/webscraper.git
   cd webscraper
   ```

2. Restore dependencies:
   ```bash
   dotnet restore
   ```

3. Build the project:
   ```bash
   dotnet build
   ```

---

## License

This project is licensed under the [MIT License](LICENSE).

---
