# Word Frequency Analyzer

This is a simple Node.js script that analyzes the frequency of any Japanese word using [Yomichan](https://chrome.google.com/webstore/detail/yomichan/ogmnaimimemjmbakcfefmnahgdfhfami) compatible [_**frequency**_](https://drive.google.com/drive/folders/1g1drkFzokc8KNpsPHoRmDJ4OtMTWFuXi) dictionary(s).

## Features

- Loads a list of scraped words from a file.
- Loads _any_ [Yomichan](https://chrome.google.com/webstore/detail/yomichan/ogmnaimimemjmbakcfefmnahgdfhfami) compatible [_**frequency**_](https://drive.google.com/drive/folders/1g1drkFzokc8KNpsPHoRmDJ4OtMTWFuXi) dictionary(s). 
- Processes words and finds their frequencies.
- Writes the results to an output file.

## Usage

1. **Make sure** you have **Node.js** installed on your system.

2. Clone this repository.

3. Install the **required dependencies**:

   ```bash
   npm install lodash
   ```
   
   ```bash
   npm install chalk
   ```
