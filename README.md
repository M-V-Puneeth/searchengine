
# Search Engine

A simple Python-based search engine that indexes a corpus of text documents and allows querying using basic information retrieval techniques.

## Features

- Tokenization and stopword removal
- Inverted index construction
- Query processing and document retrieval
- Modular code structure for easy extension

## Project Structure

```
searchengine/
├── buildindex.py     # Script to build the inverted index from the corpus
├── querytexts.py     # Script to process user queries and retrieve relevant documents
├── stopwords.txt     # List of stopwords to exclude during indexing
├── corpus/           # Directory containing text documents to be indexed
└── README.md         # Project documentation
```

## Getting Started

### Prerequisites

- Python 3.6

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/M-V-Puneeth/searchengine.git
   cd searchengine
   ```

2. Ensure your corpus of text files is placed inside the `corpus/` directory.

### Usage

1. Build the inverted index:

   ```bash
   python buildindex.py
   ```

2. Run the query processor:

   ```bash
   python querytexts.py
   ```

   Follow the on-screen prompts to enter your search queries.

## Customization

- **Stopwords**: Modify `stopwords.txt` to add or remove words that should be excluded during indexing.
- **Corpus**: Add your `.txt` files to the `corpus/` directory to include them in the search index.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.
