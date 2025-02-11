# CCMS - Contract and Compliance Management System

CCMS is a Python-based Contract and Compliance Management System designed to help organizations manage their contracts and ensure compliance effectively. With an intuitive interface and robust backend, CCMS is built to streamline workflows and improve efficiency in managing contractual obligations.

---

## Features
- **Contract Parsing:** Extract and process data from contract documents.
- **Compliance Tracking:** Monitor and ensure adherence to contractual terms.
- **Command-Line Interface (CLI):** Easy-to-use interface for managing operations.
- **Database Integration:** Store and manage contracts in a structured format.
- **Supabase Integration:** Leverage Supabase for scalable and reliable backend.
- **Document Support:** Handle contracts in PDF and Word formats.
- **Logging and Reports:** Generate logs and compliance reports for audits.

---

## Requirements

- Python 3.8 or higher
- Dependencies listed in `requirements.txt`

Install the dependencies using pip:
```bash
pip install -r requirements.txt
```

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/VinVorteX/ccms.git
   cd ccms
   ```

2. Set up the environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Add a `.env` file for environment variables (e.g., `SECRET_KEY`, database credentials).

4. Run the application:
   ```bash
   python -m ccms.main
   ```

---

## Usage

### CLI Commands

The following commands are available via the CLI:

1. **Parse a Contract:**
   ```bash
   ccms parse --file path/to/contract.pdf
   ```

2. **Generate Compliance Report:**
   ```bash
   ccms report --contract-id 1234
   ```

3. **Add a Contract to the Database:**
   ```bash
   ccms add --file path/to/contract.docx
   ```

4. **List All Contracts:**
   ```bash
   ccms list
   ```

For more options, use:
```bash
ccms --help
```

---

## Project Structure
```
CCMS/
├── ccms/               # Core package
│   ├── __init__.py
│   ├── main.py         # CLI entry point
│   ├── config.py       # Configuration
│   ├── commands/       # Submodule for CLI commands
│   ├── database/       # Submodule for database management
│   ├── parsers/        # Submodule for document parsing
│   └── utils/          # Submodule for utility functions
├── README.md           # Project documentation
├── LICENSE             # License information
├── setup.py            # Package setup file
├── requirements.txt    # Project dependencies
├── .gitignore          # Ignored files
└── dist/               # Created after building the package
```

---

## Contributing

We welcome contributions from the community! Follow these steps to contribute:

1. Fork the repository and clone it locally.
2. Create a new branch for your feature or bug fix.
3. Make your changes and write tests if applicable.
4. Submit a pull request with a detailed description of your changes.

---

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

## Contact

For questions or support, contact:
- **Email:** rvinayak108@gmail.com
- **GitHub:** [VinVorteX](https://github.com/VinVorteX)

---

## Future Plans
- Integration with advanced compliance tools.
- Support for additional document formats.
- Web-based interface for broader accessibility.

---

Thank you for using CCMS! We hope it helps you manage your contracts and compliance effectively.

