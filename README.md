# Advanced Parser with Rule-Writing Capability

So i was planning to to add anime to from a tracking website like MyAnimeList to my torrent rules list then i came across an idea to scrape anime titles from the website. This is a simple python script that uses BeautifulSoup for css selction and cloudscraper to bypass cloudflare protection. The script is able to scrape anime titles from the website and save them to a text file. Then a user provided rules.json file is then modified, the functions can be changed per liking, and then you have this project that can do all this for you.

## Key Features

- **Dynamic Rule Writing**: Users can define custom rules that the parser will apply during data processing, offering flexibility to cater to various data analysis needs.
- **Complex Data Handling**: Engineered to manage and parse complex data structures, including nested and multi-layered data.
- **High Performance**: Optimized for performance, ensuring quick processing of large datasets without compromising accuracy.
- **User-Friendly Interface**: Designed with usability in mind, making it accessible for both technical and non-technical users.

## Getting Started

### Prerequisites

Ensure you have Python 3.6 or later installed on your system. This project may also require additional Python libraries, which can be installed using the first line of this Jupyter Notebook.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/anime-list-parser.git
   cd anime-list-parser
   ```
2. Install required Python libraries:
   
   Thiis can be acomplished by running the first cell of the Jupyter Notebook

### Usage

To start using the parser, navigate to the project directory and run the jupyter notebook. The notebook contains detailed instructions on how to load data, define rules, and apply them to the data.

## Writing Custom Rules

This parser allows users to write custom rules in a simple and intuitive way. Rules can be defined directly within the script or loaded from an external file. Here's a basic example of how to define a rule:

```python
def custom_rule(data):
    # Your rule logic here
    return modified_data
```

For more detailed instructions on writing and applying rules, refer to the instructions in the [parser.ipynb](parser.ipynb) notebook.

## Examples

It is recommended that you explore the Notebook and the included rules.json (obsfucated) to understand the usage

## Contributing

Contributions are welcome! If you have ideas for new features, improvements, or bug fixes, please feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any questions or feedback regarding this project, please contact me at Discord: marto90123
