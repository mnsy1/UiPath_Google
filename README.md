# UiPath Google Search Automation Library

This UiPath library is designed to automate the process of opening Google, searching for a specific text, and clicking on the first link in the search results. This library can be used as a foundation for automating web browsing tasks or as part of more complex workflows.

## Features
- Opens Google in a browser (default: Chrome)
- Searches for a specific text (input parameter)
- Clicks on the first search result link
- Works seamlessly with UiPath Studio as a reusable library

## Prerequisites
- UiPath Studio (latest version)
- A compatible web browser (Chrome/Firefox)
- UiPath Web Automation packages installed
- Stable internet connection

## Installation

1. Download or clone this repository:
   ```bash
   git clone https://github.com/yourusername/uipath-google-search-automation.git
2. Open UiPath Studio and load the library into your project.

## Usage

1. Import the Library: After cloning or downloading, import the library into your UiPath project.
2. Set the Search Text: In your UiPath workflow, pass the text you want to search on Google as an argument to the library.
3. Run the Automation: Execute the workflow, and it will:
- Open Google in the browser.
- Search for the text you provided.
- Click on the first link in the search results.

## Example Workflow

1. Drag and drop the GoogleSearchAutomation activity into your workflow.
2. Provide the search text as an argument/input to the activity (e.g., "UiPath automation tutorial").
3. Run the workflow, and the automation will complete the task.

## Customization

- Browser Type: The library is set to use Chrome by default. You can modify the browser type in the workflow by editing the Open Browser activity settings.
- Search Result Click: Currently, the first search result is clicked. If you need to click on other results or customize the behavior, modify the selectors in the Click activity.

## Contributions

Feel free to submit issues or pull requests to enhance the library.
