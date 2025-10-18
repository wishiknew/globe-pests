# Globe Pests Project

## Overview
A structured database of agricultural pests organized by country, designed to provide information about major crop threats worldwide.

## Project Structure
- `pests-by-country.json` - Main data file containing pest information organized by country

## Data Structure
Each country entry includes:
- Country name and code
- Geographic region
- List of major agricultural pests with:
  - Common and scientific names
  - Pest type (insect, fungal disease, etc.)
  - Crops affected
  - Description and severity level

## Current Coverage
- 10 countries across 6 global regions
- 30 major agricultural pests
- Focus on high-impact crop threats

## Severity Levels
- **Critical**: Immediate action required, potential for widespread crop failure
- **High**: Significant economic impact, requires active management
- **Medium**: Moderate impact, manageable with standard practices

## Development Notes
- Data is maintained in JSON format for easy parsing and integration
- Last updated: 2025-10-18
- Primary focus: Agricultural pests affecting food crops

## Future Enhancements
- Add more countries and regions
- Include control methods and management strategies
- Add economic impact data
- Include seasonal patterns and climate considerations
- Create API or web interface for data access
