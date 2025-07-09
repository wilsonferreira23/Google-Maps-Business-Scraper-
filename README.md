# Google Maps Business Scraper Streamlit Web App
  live : https://gmap-scraper-web-app-shakib-absar.streamlit.app/

## Overview

Google Maps Business Scraper is a Streamlit application designed to scrape business details from Google Maps based on a search term. It extracts `business names`, `addresses`, `websites`, `phone numbers`, and `average reviews`. <br>
The scraped data is then saved in an Excel file for easy access and download.

## Features

- **User Input**: Enter a search term and specify the number of results to scrape.  
- **Progress Indicator**: A progress bar and elapsed time indicator to show the scraping process.
- **Data Export**: Export the scraped data to an Excel file and download it directly from the app.
- **Styled Interface**: Custom background color and personalized branding.

## Installation

1. **Clone the Repository**
    ```sh
    git clone https://github.com/sabsar42/Google-Map-Scrapper-Streamlit.git
    cd Google-Map-Scrapper-Streamlit
    ```

2. **Create a Virtual Environment**
    ```sh
    python -m venv venv
    ```

3. **Activate the Virtual Environment**

    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```

4. **Install Required Packages**
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Streamlit App**
    ```sh
    streamlit run main_setVal.py
    ```

2. **Open the App in a Browser**
    After running the command, Streamlit will display a URL in the terminal (usually `http://localhost:8501`). Open this URL in your browser.

3. **Enter Search Term and Number of Results**
    - Enter the desired search term.
    - Specify the number of results to scrape.

4. **Scrape and Download Data**
    - Click on the **Get Data** button to start scraping.
    - After completion, download the Excel file containing the scraped data.

## Code Structure

- **`main_setVal.py`**: Contains the main Streamlit application code along with the Scraper logic.

## Example
    
1. **Enter Search Term**: "Coffee Shops in New York, United States"
2. **Specify Number of Results**: 100
3. **Click `Get Data`**: The app scrapes data and displays progress.
4. **Download Excel File**: Click the download button to get the results in .XLSX format ( Excel File ).

## Contributions

Contributions are welcome! Feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Author

Developed by Shakib Asbar.
