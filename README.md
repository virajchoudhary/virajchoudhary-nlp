Viraj Choudhary's NLP Toolkit

Personal Python package developed for my university Natural Language Processing lab assignments.
It includes simple, reusable functions for:

Text preprocessing
Corpus analysis
Feature engineering

I originally built this toolkit to support my coursework, but I may extend it for other use cases over time. Who knows—it could even evolve into a major project. Big things start small.

More functions and modules will be added.

## Installation

1.  **Install the package from PyPI:**
    ```bash
    pip install virajchoudhary-nlp
    ```

2.  **Import and use the features in your Python code:**
    ```python
    from virajchoudhary_nlp import preprocessing as pp
    from virajchoudhary_nlp import features

    # Clean some text
    raw_text = "This is a 123 test sentence for my NLP toolkit!"
    cleaned_text = pp.clean_text(raw_text) # (Assuming your function is named clean_text)
    print(f"Cleaned Text: {cleaned_text}")

    # Use another feature
    word_count = features.count_words(cleaned_text) # (Assuming your function is named count_words)
    print(f"Word Count: {word_count}")
    ```

---

For more details, you can find the project on [PyPI](https://pypi.org/project/virajchoudhary-nlp/).
