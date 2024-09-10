# UiPath Google Search Automation Library

This UiPath library is designed to automate the process of opening Google, searching for a specific text, and clicking on the first link in the search results. This library can be used as a foundation for automating web browsing tasks or as part of more complex workflows.

## Features
- Opens Google in a browser (default: Chrome)
- Searches for a specific text (input parameter)
- Clicks on the first search result link
- Works seamlessly with UiPath Studio as a reusable library

## Prerequisites
- UiPath Studio (latest version)
- A compatible web browser (Chrome)
- UiPath Web Automation packages installed
- Stable internet connection

## Installation

1. Download or clone this repository:
   [https://github.com/mnsy/Google.Search.1.0.1.nupkg](https://github.com/mnsy1/UiPath_Google/blob/main/Google.Search.1.0.1.nupkg)
2. Open UiPath Studio and load the library into your project.

## Usage

1. Import the Library: Import the library into your UiPath project after cloning or downloading.
2. Set the Search Text: In your UiPath workflow, pass the text you want to search on Google as an argument to the library.
3. Run the Automation: Execute the workflow, and it will:
- Open Google in the browser (Launch Activity).
- Search for the text you provided (Search Activity).
- Click on the first link in the search results (Click First Search Result Activity).

## Example Workflow

1. Drag and drop the Launch activity into your workflow which will run Chrome browser.
2. Provide the search text as an argument/input to the Search activity (e.g., "UiPath automation tutorial").
3. Use the Click First Search Result Activity which indicates the first element on the search result and click on it.
4. Run the workflow, and the automation will complete the task.

## Customization

- All activities takes main 3 input arguments Retry Number, Retry Interval, and Timeout (milliseconds).

## Contributions

Feel free to submit issues or pull requests to enhance the library.
