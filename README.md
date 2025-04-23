# Sankey Diagram Generator

A web-based tool for creating Mermaid Sankey diagrams from tabular data.

## Features

- Create Sankey diagrams from tabular data
- Import and export CSV data
- Export diagrams as Mermaid (.mmd) files
- Adjust diagram appearance with simple controls
- "Fit to Width" functionality for optimal viewing
- Support for Markdown links in table cells

## Usage

1. Open the [Sankey Diagram Generator](index.html) in your browser
2. Enter your data in the table (format: Country, City/Town, Person, Project, Organization)
3. The Sankey diagram will update automatically as you edit
4. Use the controls to adjust the diagram appearance
5. Click "Fit to Width" to scale the diagram to fit the available space
6. Export your diagram as a Mermaid file or your data as CSV

## Sample Data

The tool includes sample data that can be loaded by clicking the "Load Sample" button.

## File Formats

- **CSV Import/Export**: Standard CSV format with headers
- **Mermaid Export**: Standard Mermaid format with YAML frontmatter for configuration

## Dependencies

- [jQuery](https://jquery.com/) and [jQuery UI](https://jqueryui.com/) for UI interactions
- [PapaParse](https://www.papaparse.com/) for CSV parsing
- [Mermaid](https://mermaid.js.org/) for Sankey diagram rendering

## License

This project is open source and available for anyone to use and modify.
