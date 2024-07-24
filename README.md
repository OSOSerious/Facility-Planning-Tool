# Rehabilitation Facility Finder

## Overview

The Rehabilitation Facility Finder is a Python-based tool designed to assist in locating and evaluating properties suitable for rehabilitation facilities in South Florida. It uses AI agents and various data sources to analyze properties, zoning regulations, community factors, and facility planning requirements.

## Features

- Property search based on specified criteria (location, bedrooms, price)
- Zoning analysis for potential rehab facility use
- Community assessment for compatibility with rehab facilities
- Facility planning and renovation cost estimation
- Command-line interface for easy use

## Prerequisites

- Python 3.7+
- Git (for version control)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/rehab-facility-finder.git
   cd rehab-facility-finder
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install required packages:
   ```
   pip install -r requirements.txt
   ```

4. Set up environment variables:
   Create a `.env` file in the project root and add your API keys:
   ```
   OPENAI_API_KEY=your_openai_key_here
   RAPIDAPI_KEY=your_rapidapi_key_here
   ```

## Usage

Run the script with the following command:

```
python rehab_facility_finder.py --city "Miami" --min_bedrooms 10 --max_price 2000000
```

You can adjust the parameters as needed:
- `--city`: Specify the city to search in (default: Miami)
- `--min_bedrooms`: Set the minimum number of bedrooms (default: 10)
- `--max_price`: Set the maximum property price (default: 2000000)

## Output

The script will display results for each property found, including:
- Address
- Number of bedrooms
- Price
- Zoning allowance
- Community score
- Estimated renovation cost
- Optimal capacity
- Key features

## Limitations

- The current version uses mock data for zoning and community assessments
- Property search is limited to the Realtor.com API's capabilities
- The tool is focused on South Florida and may need adjustments for other regions

## Future Improvements

- Implement real data sources for zoning and community information
- Add more detailed financial analysis
- Develop a web-based user interface
- Expand geographical coverage

## Contributing

Contributions to improve the Rehabilitation Facility Finder are welcome. Please feel free to submit pull requests or open issues to discuss potential enhancements.

## License

[MIT License](https://opensource.org/licenses/MIT)

## Disclaimer

This tool is for informational purposes only and should not be considered as professional advice for real estate or facility planning decisions. Always consult with qualified professionals before making significant property or business decisions.
