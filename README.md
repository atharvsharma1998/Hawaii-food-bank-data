# Hawaii-food-bank-data

> **Note:** This data was manually entered and may be susceptible to human mislabeling, errors. Additionally, it might be outdated. If you find any inaccuracies, feel free to report them.


## Food Bank CSV Documentation

This document provides an overview of the data contained in the `food_banks.csv` file. The file contains detailed information about food banks in Hawaii, including their locations, services, and operational details.

---

## Overview
The CSV file is designed to organize information about food banks, making it easy to analyze their operations and accessibility. Below are detailed explanations for each column in the file:

### **Columns and Descriptions**

1. **`island_name`**
   - **Description**: Indicates the Hawaiian island where the food bank is located.
   - **Examples**: Maui, Oahu, Kauai.

2. **`food_bank_name`**
   - **Description**: The name of the food bank providing services.
   - **Examples**: ARC of Maui, Calvary Chapel Central Maui.

3. **`sub_area`**
   - **Description**: The sub-region or locality within the island where the food bank is situated.
   - **Examples**: Central Maui, North Shore, South Kona.

4. **`service_type`**
   - **Description**: Type of service offered by the food bank.
   - **Examples**: Groceries, Prepared Meals.

5. **`operation_duration`**
   - **Description**: Schedule of operations, including specific days and times when services are available.
   - **Examples**: 
     - "Every Monday 12-2pm except on the week of the holiday."
     - "Monday-Friday 9am - 10:30am."

6. **`instructions`**
   - **Description**: Special instructions for accessing the service, such as calling ahead or observing specific protocols.
   - **Examples**:
     - "Please call to request food and arrange pick-up."
     - "Drive thru; remain in your vehicle."

7. **`location_text`**
   - **Description**: The address or descriptive location of the food bank.
   - **Examples**:
     - "140 N. Market St, Wailuku."
     - "20 West Wakea Avenue, Kahului."

8. **`contact`**
   - **Description**: Contact information for the food bank, usually a phone number.
   - **Examples**: 
     - "808-242-5781 x216"
     - "808-244-4656"

9. **`days`**
   - **Description**: Specifies the days of operation.
   - **Examples**:
     - "monday,saturday"
     - "monday,tuesday,friday"

10. **`TEFAP`**
    - **Description**: Indicates whether the food bank participates in The Emergency Food Assistance Program.
    - **Possible Values**:
      - "yes"
      - "no"
      - "unknown"

11. **`TANF`**
    - **Description**: Indicates whether the Temporary Assistance for Needy Families program is available at the food bank.
    - **Possible Values**:
      - "yes"
      - "no"
      - "unknown"

12. **`location_geopoint`**
    - **Description**: Geographical coordinates (latitude, longitude) for the food bank, useful for mapping.
    - **Examples**: 
      - "20.8899619,-156.5026247"
      - "20.9062678,-156.485657"

13. **`description`**
    - **Description**: Provides additional details about the food bank.
    - **Note**: Most entries in this column are currently empty.

14. **`active`**
    - **Description**: Indicates whether the food bank is operational.
    - **Possible Values**: 
      - "yes"
      - "no"

15. **`marker_legend`**
    - **Description**: Categorizes the food bank services.
    - **Examples**: 
      - "grocery"
      - "meals"

---

## Usage
This file can be used to:
- Identify active food banks on various Hawaiian islands.
- Analyze service availability and type (e.g., groceries vs. prepared meals).
- Map food banks based on geographical coordinates.
- Assess participation in assistance programs like TEFAP and TANF.

For any questions or concerns regarding the dataset, feel free to reach out.

---

**Happy Data Exploring!**

