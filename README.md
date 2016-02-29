# Interactive Word Clouds

3rd year project about Interactive Word Clouds.

The goal of this project is to create a web application which will allow users to create word clouds which consist of single words as well as compound words from multiple sources of text.

**Working project can be found [here](http://audreyleowhl.github.io)**

## Ways of using the web application

You can either enter text in the text area, or select a file from your computer to generate the text for the word cloud.

If you have selected a file but wish to change your file selection, you can just select another file, and that should replace the file you previously selected.

By using the radio buttons to select between 'Text' and 'File', you can choose to generate word clouds from either text or file. Selecting `Text` means that you chose to generate word clouds from the text entered in the text area, while selecting `File` means that you chose to generate word clouds from the file selected.

You can also choose to generate word clouds consisting of either single words or compound words by clicking on the buttons `Single word cloud` and `Compound word cloud` respectively. If you are not happy with the created word cloud, clicking on the button again will regenerate the word cloud.

The `Clear text` button allows you to clear all the text in the text area, and clicking on `How to use` opens up this page on a new tab or window, allowing you to see what can be done in this web application and more information about it.

The `Compound word cloud` button is currently disabled while I work on the functionality for it.

## Web browsers

This web application currently works with all web browsers.

## File formats

This web application currently only works with these file formats:
- .txt
- .pdf

More work is currently being done to allow for more file formats.

## Software

This web application uses these external software:
- [wordfreq](https://github.com/timdream/wordfreq) by timdream
- [wordcloud2.js](https://github.com/timdream/wordcloud2.js) by timdream
- [pdf.js](https://mozilla.github.io/pdf.js/) by mozilla
