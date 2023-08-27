# MongoDB Query Log Index Advisor

![GitHub](https://img.shields.io/github/license/zegulas/mongodb_query_log_index_advisor)
![GitHub stars](https://img.shields.io/github/stars/zegulas/mongodb_query_log_index_advisor?style=social)

The MongoDB Query Log Index Advisor is a tool designed to help MongoDB users optimize their collections' indexes based on query logs. By analyzing query patterns and usage from logs, this tool provides recommendations for creating or modifying indexes to improve query performance.

## Features

- Analyze MongoDB query logs to identify frequently executed queries.
- Provide suggestions for new indexes or (todo: adjustments to existing indexes).
- Improve query performance by optimizing index usage.
- Easy-to-use command-line interface.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/zegulas/mongodb_query_log_index_advisor.git
   cd mongodb_query_log_index_advisor
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Usage

1. Export your MongoDB query logs in a suitable format.
2. Run the advisor tool and provide the path to your query log file:
   ```bash
   python advisor.py --log_path /path/to/your/query/logs.log
4. Review the generated index recommendations and apply them to your MongoDB collections.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/bugfix:
   ```bash
   git checkout -b feature-new-feature
4. Make your changes and ocmmit them:
   ```bash
   git commit -m "Add new feature"
6. Push to your branch:
   ```bash
   git push origin feature-new-feature
8. Create a pull request on GitHub.

## License

This project is licensed under the MIT License.

## Contact

For questions or support, please contact zegulas@gmail.com
