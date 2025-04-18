 # LinkedIn Job Scraper

 A tool to scrape job listings from LinkedIn using Selenium and the open-source linkedin-jobs-scraper library. You can configure search queries, apply filters, and export results to CSV for analysis.

 ## Features
 - Authenticate with LinkedIn using your `LI_AT_COOKIE`
 - Define custom search queries with keywords, locations, filters, and limits
 - Event-driven scraping: capture job data, performance metrics, and errors
 - Export scraped job listings to `linkedin_jobs.csv`

 ## Installation
 1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/linkedin-job-scraper.git
    cd linkedin-job-scraper
    ```
 2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```
 3. Install Python dependencies:
    ```bash
    pip install linkedin-jobs-scraper python-dotenv selenium pandas jupyter
    ```
 4. Create a `.env` file in the project root with your LinkedIn authentication cookie:
    ```
    LI_AT_COOKIE=your_li_at_cookie_value
    ```
 5. Ensure `chromedriver` and `chrome` are installed and available on your PATH or update paths in the notebook.

 ## Usage
 1. Launch Jupyter:
    ```bash
    jupyter notebook src/linkedin.ipynb
    ```
 2. Execute each cell in order. Scraped job listings will be saved to `linkedin_jobs.csv`.

 ## Contributing
 Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to contribute.

 ## Citation
 If you use this project in your research, please cite it as described in [CITATION.md](CITATION.md).

 ## License
 This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
