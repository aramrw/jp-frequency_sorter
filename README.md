Word Frequency Analyzer
This is a simple Node.js script that analyzes the frequency of words using scraped data and Yomichan dictionaries.

Features
Loads a list of scraped words from a file.
Loads Yomichan dictionaries for word frequency lookup.
Processes scraped words and finds their frequencies.
Writes the results to an output file.
Usage
Make sure you have Node.js installed on your system.

Clone this repository.

Install the required dependencies:

bash
Copy code
npm install
Prepare your scraped word list:

Place your list of words in a file named kanji_words.txt inside a folder named scraped_words.

Run the script:

bash
Copy code
node index.js
Once the processing is complete, the results will be saved in an output file named output.txt in the output folder.

Notes
This script is designed to be a simple tool for analyzing word frequencies and is not intended for commercial use.

You can customize the Yomichan dictionaries used for analysis by modifying the yomichanDictionaries array in the script.

License
This project is licensed under the MIT License - see the LICENSE file for details.
