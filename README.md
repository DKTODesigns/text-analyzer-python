# Text Analyzer (Python)

A simple Python project that demonstrates basic text analysis using object-oriented programming.

---

## Features

- Converts text to lowercase
- Removes punctuation
- Counts frequency of all words
- Counts frequency of a specific word

---

## Example

```python
text = "Lorem ipsum dolor! diam amet, consetetur Lorem magna."
analyzer = TextAnalyzer(text)

print(analyzer.fmtText)
print(analyzer.freqAll())
print(analyzer.freqOf("lorem"))
