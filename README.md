# WHO Disease Outbreak News (DONs) Data Extractor

## Overview
The **Outbreak Data Extractor** is a tool designed to help users **extract and structure disease outbreak reports** from the **WHO Disease Outbreak News (DONs)**. Since WHO does not allow automated web scraping, this tool enables manual data entry while using AI to **format the data for analysis**. 

With this tool, users can:
- Copy and paste outbreak reports from the **WHO DONs** page.
- Use **AI to extract key outbreak details** and structure the data into a table.
- **Append multiple reports** to the same dataset.
- **Visualize outbreaks on a map**.
- **Download structured data as a CSV file** for further analysis.
- **Access it via GitHub Pages** for a seamless experience.

## Features
✅ **Manual copy-paste workflow** (no web scraping required)  
✅ **AI-powered data extraction** for structured tables  
✅ **Appends multiple reports** instead of overwriting data  
✅ **Interactive map** showing outbreak locations  
✅ **CSV export** for further analysis in tools like Excel or Power BI  
✅ **Clear Context** feature to process a new report while keeping existing data  
✅ **Manual refresh** option to fully reset the dataset  
✅ **Faster than manual data entry into Excel or paper-based tracking**  

## How It Works
### 1. Copy a WHO DONs report
- Go to the **[WHO Disease Outbreak News](https://www.who.int/emergencies/disease-outbreak-news)** page.
- Open a report and **select all text** using:
  - **Windows:** `Ctrl + A`, then `Ctrl + C` to copy
  - **Mac:** `Command + A`, then `Command + C` to copy

### 2. Paste the report into the tool
- Click inside the text box.
- Paste using:
  - **Windows:** `Ctrl + V`
  - **Mac:** `Command + V`

### 3. Process the data
- Click the **"Extract Data"** button.
- The tool will **extract structured data** and display it in a table.
- The extracted **location data is plotted on a map**.

### 4. Add more reports (Optional)
- If you paste another report and extract data, it will be **appended to the existing dataset**.
- The same applies to the **map**—new outbreak locations will be added.

### 5. Clear or Reset Data
#### To clear only the text input (while keeping existing data):
- Click **"Clear Context"** and paste a new report.

#### To fully reset the tool (clear table and map):
- **Manually refresh the browser** using:
  - **Windows:** Press `F5` or `Shift + F5`
  - **Mac:** Press `Command + R` or `Command + Shift + R`

### 6. Download Extracted Data
- Click the **"Download CSV"** button to save the structured data for further analysis.

## Why This Approach?
- **Compliant with WHO’s policies** (no automated web scraping).
- **Makes outbreak reports easy to analyze** by converting them into structured data.
- **Saves time** compared to manually copying and formatting data.
- **Provides real-time insights** by mapping outbreak locations.
- **Faster than reading reports, writing down details manually, or entering them into Excel.**

## Deployment on GitHub Pages
- The tool is hosted using **GitHub Pages** for easy access.
- The main file has been renamed to `index.html` to serve as the entry point.
- No installation needed—just open the website and start processing reports.

## Installation & Setup (For Local Use)
This is a **web-based tool**—no installation required. However, if you want to run it locally:

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, etc.).
- An **OpenAI API key** (required for AI-powered data extraction).

### Running Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/jmesplana/who_dons_data_extractor.git
   cd who_dons_data_extractor
   ```
2. Open the `index.html` file in a browser.
3. Enter your **OpenAI API key** in the provided field.
4. Start extracting and processing outbreak reports!

## License
This project is licensed under [MIT License](LICENSE).

## Contributing
If you’d like to contribute or suggest improvements, feel free to open an issue or submit a pull request.

## Contact
For questions or feedback, reach out via GitHub issues or contact the project maintainer.

