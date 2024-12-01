# Greek to Braille Translator

This web application allows users to translate Greek (or English) text into Braille using Unicode Braille characters. The translator supports uppercase and lowercase letters, diacritical marks, diphthongs, and numeric values. It is designed to help educators, researchers, and accessibility advocates create content for visually impaired users in the Greek language.

## Features
- **Full Greek Alphabet Support**: Translates both uppercase and lowercase Greek letters.
- **Special Characters and Diphthongs**: Recognizes Greek diphthongs (e.g., `αι`, `ευ`) and translates them into the appropriate Braille representations.
- **Number Translation**: Converts numbers, including decimals, with proper Braille formatting.
- **Customizable Braille Styles**: Choose between multiple font families for visually rendering Braille text, including `SimBraille` and `AppleBraille`.

## How It Works
The translator uses a JavaScript function to map Greek characters and their Braille equivalents. The mapping is based on international Braille standards. Simply type or paste Greek text into the input box, and the Braille representation will be displayed instantly.

## Usage
1. Open the web page.
2. Enter some Greek (or English) text in the input box.
3. Click the **Convert** button.
4. View the Braille translation in the output area.

## Live Demo
[Visit the Greek to Braille Translator](https://gvasilious.github.io/greek2braille/)  

## Installation
To host the application locally:
1. Clone this repository:
git clone https://github.com/gvasilious/greek2braille.git

2. Open the `index.html` file in your browser.

## Contributing
We welcome contributions to improve this tool! If you encounter bugs or have suggestions for new features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as you see fit.

## Acknowledgments
- Braille character mappings based on [Unicode Braille Patterns](https://unicode-table.com/en/blocks/braille-patterns/).
- Inspired by the need for accessible Greek-language tools for visually impaired users.

