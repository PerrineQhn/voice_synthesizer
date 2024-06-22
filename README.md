# Sentences Synthetizer

This repository contains a Jupyter Notebook for synthesizing and processing sentences. The notebook utilizes several Python libraries to achieve its functionalities, including `parselmouth`, `textgrids`, `re`, and `matplotlib`.

## Prerequisites

Before running the notebook, ensure you have the following libraries installed:

- `parselmouth`
- `textgrids`
- `re`
- `matplotlib`

You can install them using pip:

```sh
pip install parselmouth praat-textgrids matplotlib
```

## Usage

1. **Clone the repository:**

```sh
git clone https://github.com/PerrineQhn/sentences_synthetizer.git
cd sentences_synthetizer
```

2. **Open the Jupyter Notebook:**

Ensure you have Jupyter installed. If not, you can install it using pip:

```sh
pip install notebook
```

Then, start Jupyter Notebook:

```sh
jupyter notebook
```

Open `sentences_synthetizer.ipynb` in the Jupyter interface.

3. **Run the Notebook:**

Follow the instructions within the notebook to process sentences. You will have options to:

- Enter your own sentence.
- Choose a sentence from a predefined list.
- Process all sentences from a file named `sentence.txt`.

### Input Prompt

The notebook includes a prompt that allows you to choose one of the following options:

```python
choice = input(
    "Please select an option (1/2/3): "
    "1. Enter your own sentence. "
    "2. Choose a sentence from the list. "
    "3. Process all sentences from the file sentence.txt."
)
```
