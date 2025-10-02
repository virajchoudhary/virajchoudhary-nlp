Personal Python package developed for my university Natural Language Processing lab assignments.
It includes simple, reusable functions for:

Text preprocessing
Corpus analysis
Feature engineering

I originally built this toolkit to support my coursework, but I may extend it for other use cases over time. Who knows, it could even evolve into a major project. Big things start small.

More functions and modules will be added.

## Installation

1.  **Install the package from PyPI:**
    ```bash
    pip install virajchoudhary-nlp
    ```

2.  **Import and use the features in your Python code:**
    ```python
    from virajchoudhary_nlp import preprocessing as pp

    raw_text = "This is a 123 test sentence for my NLP toolkit!"

    # lowercase
    lower_text = pp.to_lowercase(raw_text)
    print(f"Lowercase Text: {lower_text}")

    # Tokenize
    tokens = pp.tokenize_words(lower_text)
    print(f"Tokens: {tokens}")
    ```

---

For more details, you can find the project on [PyPI](https://pypi.org/project/virajchoudhary-nlp/).
