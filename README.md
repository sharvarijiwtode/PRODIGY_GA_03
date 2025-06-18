# Markov Chain Text Generator

This project implements a **simple character-level Markov Chain** text generator using Python. It builds a statistical model from a given training text and generates new text by predicting the next character based on the previous ones.

---

## Features

- Character-level Markov Chain implementation
- Customizable order (how many previous characters are considered)
- Randomized, but statistically informed text generation
- Clean, beginner-friendly code structure

---

## How It Works

1. **Training Phase**:
   - The model learns sequences of characters (of length = `order`) from the input text.
   - It maps each character sequence to possible next characters.

2. **Generation Phase**:
   - Starting from a prefix, it generates text by choosing the next character randomly from the possibilities.

---

## Files

- `markov_text_generator.ipynb` — Main notebook containing the code and usage examples

---

## Future Enhancements
- Word-level Markov Chains
- Probability-weighted character choice
- Text input from large datasets
- Add a web interface using Flask or Streamlit

## Contributing
Feel free to fork this project, star it, and submit pull requests. Bug reports and feature suggestions are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Sharvari Jiwtode
sharvarijiwtode2005@gmail.com
