# Facility-Planning-Tool

## Description

This project utilizes the Swarms AI framework to create an intelligent system for finding and analyzing properties suitable for sober living and drug rehabilitation facilities in South Florida. It employs multiple specialized AI agents to perform tasks such as property searching, zoning analysis, community impact assessment, and facility planning.

## Features

- Property search tailored for rehab facilities
- Zoning regulation analysis
- Community impact assessment
- Facility layout planning
- Both sequential and concurrent workflows for comprehensive property analysis

## Installation

1. Clone the repository:
git clone https://github.com/yourusername/south-florida-rehab-facility-finder.git
cd south-florida-rehab-facility-finder
Copy
2. Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
Copy
3. Install required packages:
pip install -r requirements.txt
Copy
4. Set up environment variables:
Create a `.env` file in the root directory and add your API keys:
OPENAI_API_KEY=your_openai_api_key_here
Copy
## Usage

Run the main script:
python rehab_facility_finder.py
Copy
This will execute the property search and analysis process, generating a recommendation for a suitable property to be used as a rehab facility.

## Project Structure

- `rehab_facility_finder.py`: Main script containing agent definitions and execution logic
- `requirements.txt`: List of Python package dependencies
- `rehab_facility_recommendation.txt`: Output file containing the final property recommendation

## Agents

1. **Property Searcher**: Finds properties suitable for rehab facilities based on specific criteria.
2. **Zoning Analyst**: Evaluates zoning regulations and potential challenges for each property.
3. **Community Impact Assessor**: Analyzes the community aspects and suitability of each location.
4. **Facility Planner**: Plans the optimal use of each property as a rehab facility, including necessary modifications.

## Tools

- PropertySearchTool: Searches for properties meeting specified criteria
- ZoningAnalysisTool: Analyzes zoning regulations for potential properties
- CommunityAssessmentTool: Assesses community compatibility for rehab facilities
- FacilityPlanningTool: Plans and designs rehab facility layouts and modifications

## Workflows

- **Sequential Workflow**: Processes properties through each agent in sequence
- **Concurrent Workflow**: Allows agents to work on tasks simultaneously for faster processing

## Contributing

Contributions to improve the project are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request# Facility-Planning-Tool
Faciality Planning tool
