# Real Estate Data Scraping Script

Welcome to the Real Estate Data Scraping Script! This project elegantly automates the extraction of valuable real estate data from a specified website. Harnessing the power of web scraping, the script meticulously gathers key property information and seamlessly exports it into an Excel file. This streamlined process not only saves time but also ensures accuracy and consistency in data collection.

The exported Excel file is designed to serve as an integral component of your broader analytical projects, allowing for easy integration and further data manipulation. Whether you're performing market analysis, trend forecasting, or any other data-driven exploration, this script provides a robust foundation for your real estate insights.

### Tools Used
- **BeautifulSoup**: A Python library used for parsing HTML and extracting data from web pages.
- **Pandas**: A powerful data manipulation and analysis library for Python, used to handle and export data to CSV files.
- **Regular Expressions (re)**: Used for cleaning and extracting specific data patterns from the scraped information.
- **OS**: A module to interact with the operating system, used for file handling.

### Code Description
The provided script performs the following tasks:

1. **Extract Property Data**:
   - The function `extract_property_data(file_path)` uses BeautifulSoup to parse HTML files and extract property information such as price, property details, and address. The data is stored in a list of dictionaries.

2. **Aggregate Property Data**:
   - The function `extract_all_properties(directory, num_files)` processes multiple HTML files in the specified directory, combining the extracted property data into a single list.

3. **Clean and Process Data**:
   - The script uses regular expressions to clean and extract specific information (e.g., price, bedrooms, bathrooms, size, property type, postal code) from the raw property details.

4. **Export to CSV**:
   - The cleaned data is stored in a Pandas DataFrame and exported to a CSV file, making it ready for integration with other parts of your analytical projects.

By leveraging these tools and techniques, the script ensures efficient and accurate data collection from real estate websites, providing a solid foundation for your analytical endeavors.

---

