# 🎓 YAML Data Processing Experiment

[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![PyYAML Version](https://img.shields.io/badge/PyYAML-6.0.1-green.svg)](https://pypi.org/project/PyYAML/)
[![License](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)

> A powerful Python application for processing and analyzing student data stored in YAML format. This project demonstrates efficient data handling, filtering capabilities, and clean code practices.

## 🌟 Features

-   📊 YAML file parsing using PyYAML
-   👥 Student data management and organization
-   🔍 GPA-based filtering system
-   🛡️ Robust error handling
-   📱 Clean and intuitive interface
-   🔄 Easy data modification and updates

## 🚀 Quick Start

### Prerequisites

-   Python 3.x
-   pip (Python package manager)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/yaml-demo.git
cd yaml-demo
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
python app.py
```

## 📁 Project Structure

```
.
├── README.md
├── requirements.txt
├── students.yaml
└── app.py
```

## 📝 Components

### 1. students.yaml

Contains the student data in YAML format. Each student entry includes:

-   name
-   age
-   major
-   gpa

Example:

```yaml
students:
    - name: Alice
      age: 21
      major: Computer Science
      gpa: 3.8
```

### 2. app.py

The main Python script that processes the YAML data. It includes several functions:

-   `load_data(file_path)`: Loads and parses the YAML file
-   `display_students(students)`: Displays information about all students
-   `filter_students_by_gpa(students, min_gpa)`: Filters students based on minimum GPA
-   `main()`: Orchestrates the program flow

### 3. requirements.txt

Lists the project dependencies:

-   pyyaml==6.0.1

## 💻 Usage

1. Run the application:

```bash
python app.py
```

2. The program will:
    - Display all students and their information
    - Prompt you to enter a minimum GPA value
    - Show students who meet or exceed the specified GPA threshold

## 📸 Example Output

<div align="center">
  <img src="/images/Screenshot 2025-04-01 154111.png" alt="Example Output" width="600">
</div>

## 🔧 Technical Details

-   The application uses `yaml.safe_load()` for secure YAML parsing
-   Student data is stored in a list of dictionaries
-   GPA filtering is implemented using list comprehension
-   The program handles floating-point GPA values
-   Built with modular design principles for easy maintenance

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📚 Additional Resources

-   [PyYAML Documentation](https://pyyaml.org/wiki/PyYAMLDocumentation)
-   [YAML Specification](https://yaml.org/spec/1.2/spec.html)
-   [Python Documentation](https://docs.python.org/3/)

## ⚠️ Notes

-   Make sure both `app.py` and `students.yaml` are in the same directory
-   The program expects valid YAML syntax in the input file
-   GPA values should be numeric (floating-point numbers)
-   Keep your YAML file properly formatted for optimal performance

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

-   Aryan Soni

## 🙏 Acknowledgments

-   Thanks to the PyYAML team for their excellent library
-   Inspired by the need for efficient student data management
-   Built with ❤️ for the Python community
