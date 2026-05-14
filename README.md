<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.10+"/>
  <img src="https://img.shields.io/badge/Days-90-FF6B6B?style=for-the-badge" alt="90 Days"/>
  <img src="https://img.shields.io/badge/Files-90-4ECDC4?style=for-the-badge" alt="90 Files"/>
  <img src="https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-FFE66D?style=for-the-badge" alt="Level"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License"/>
</p>

<h1 align="center">🐍 The 90-Day Python Developer Roadmap</h1>

<p align="center">
  <strong>From zero to confident Python developer — one day at a time.</strong><br/>
  <sub>90 self-contained tutorials · YouTube-ready code · Beginner-friendly · College-level</sub>
</p>

<p align="center">
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-roadmap-overview">Roadmap</a> •
  <a href="#-part-1--the-essentials-days-158">Part 1</a> •
  <a href="#-part-2--advanced-features-days-5974">Part 2</a> •
  <a href="#-part-3--working-with-data-days-7590">Part 3</a> •
  <a href="#-how-to-use">How to Use</a> •
  <a href="#-contributing">Contributing</a>
</p>

---

## ✨ What Is This?

This repository contains **90 Python tutorial files** — one for each day of a structured learning roadmap that takes you from absolute beginner to a confident, job-ready Python developer. Each file is:

- 🎯 **Self-contained** — run any file independently, no setup needed
- 📺 **YouTube-ready** — designed to be walked through in a video tutorial
- 🧑‍🎓 **College-level** — assumes no prior programming experience
- 💡 **Practical** — every day ends with a real-world mini-project

```
📁 90-Day-Python-Roadmap/
├── 📂 Part1_Essentials/        ← Days 1–58 (Core Python)
├── 📂 Part2_Advanced/          ← Days 59–74 (OOP, Regex, Packages)
├── 📂 Part3_Data/              ← Days 75–90 (APIs, Databases, pandas)
└── 📄 README.md
```

---

## 🚀 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/90-Day-Python-Roadmap.git
cd 90-Day-Python-Roadmap

# 2. Make sure you have Python 3.10+
python --version

# 3. Run any day's file
python Part1_Essentials/day_01_indentation_and_comments.py

# 4. For Part 3 (data topics), install optional dependencies
pip install pandas matplotlib openpyxl requests
```

> [!TIP]
> Each file is **completely standalone**. You can jump to any day that interests you — no need to run them in order!

---

## 🗺️ Roadmap Overview

<table>
<tr>
<td width="33%" valign="top">

### 🟢 Part 1 — Essentials
**Days 1–58** · 58 files

The heaviest and most important part. By Day 58, you'll know the core language well enough to write programs that actually do things.

`Variables` `Lists` `Strings` `Dicts`
`Loops` `Functions` `Modules` `Files`
`Exceptions`

</td>
<td width="33%" valign="top">

### 🔵 Part 2 — Advanced
**Days 59–74** · 16 files

Writing Python that other people — including you six months from now — can read and build on.

`Classes & OOP` `Inheritance`
`Regex` `Special Methods`
`Packages` `Standard Library`
`pip & venv`

</td>
<td width="33%" valign="top">

### 🟣 Part 3 — Data
**Days 75–90** · 16 files

What a lot of Python jobs actually involve: moving data around, cleaning it, storing it, and doing things with it.

`CSV & JSON` `APIs` `Web Scraping`
`SQLite` `NoSQL` `pandas`
`Capstone Project`

</td>
</tr>
</table>

---

## 📗 Part 1 — The Essentials (Days 1–58)

<details>
<summary><strong>1.1 The Absolute Basics (Days 1–5)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 1 | Indentation, block structuring, and comments | `day_01_indentation_and_comments.py` |
| 2 | Variables, assignments, and optional type hints | `day_02_variables_and_type_hints.py` |
| 3 | Expressions, basic strings, and the `None` value | `day_03_expressions_strings_none.py` |
| 4 | Numbers, built-in numeric functions, complex numbers | `day_04_numbers_and_functions.py` |
| 5 | User input, built-in operators, basic Python style | `day_05_input_operators_style.py` |

</details>

<details>
<summary><strong>1.2 Lists, Tuples, and Sets (Days 6–13)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 6 | Lists as arrays and list indices | `day_06_lists_and_indices.py` |
| 7 | Modifying lists | `day_07_modifying_lists.py` |
| 8 | Sorting lists — custom sorting and `sorted()` | `day_08_sorting_lists.py` |
| 9 | Common list operations: `in`, `+`, `*`, `min`, `max` | `day_09_list_operations.py` |
| 10 | Nested lists and deep copies | `day_10_nested_lists_deep_copy.py` |
| 11 | Tuple basics, packing/unpacking, list↔tuple conversion | `day_11_tuples.py` |
| 12 | Sets, set operations, and frozen sets | `day_12_sets.py` |
| 13 | 🧪 Lab: Examining a list | `day_13_lab_examining_list.py` |

</details>

<details>
<summary><strong>1.3 Strings (Days 14–20)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 14 | Strings as sequences and basic string operations | `day_14_strings_as_sequences.py` |
| 15 | Special characters and escape sequences | `day_15_escape_sequences.py` |
| 16 | `split`, `join`, converting strings, stripping whitespace | `day_16_split_join_strip.py` |
| 17 | String searching, modifying strings, useful methods | `day_17_string_searching.py` |
| 18 | Converting objects to strings; the `format()` method | `day_18_format_method.py` |
| 19 | f-strings and old-style `%` formatting | `day_19_fstrings_formatting.py` |
| 20 | Bytes, text preprocessing, and practice lab | `day_20_bytes_text_lab.py` |

</details>

<details>
<summary><strong>1.4 Dictionaries (Days 21–24)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 21 | What is a dictionary? Core dictionary operations | `day_21_dictionaries.py` |
| 22 | Word counting; what can be used as a key | `day_22_word_counting.py` |
| 23 | Sparse matrices and dictionaries as caches | `day_23_sparse_matrices_caches.py` |
| 24 | 🧪 Efficiency of dictionaries; word counting lab | `day_24_dict_efficiency_lab.py` |

</details>

<details>
<summary><strong>1.5 Control Flow (Days 25–31)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 25 | `if`-`elif`-`else` and structural pattern matching | `day_25_conditionals_match.py` |
| 26 | `while` loop and `for` loop with `range` | `day_26_loops.py` |
| 27 | Controlling `range` with start/step; tuple unpacking | `day_27_range_unpacking.py` |
| 28 | `enumerate` and `zip` | `day_28_enumerate_zip.py` |
| 29 | List, set, and dictionary comprehensions | `day_29_comprehensions.py` |
| 30 | Booleans and comparison operators | `day_30_booleans_comparisons.py` |
| 31 | 🧪 Writing a text file analyzer — practice lab | `day_31_text_analyzer_lab.py` |

</details>

<details>
<summary><strong>1.6 Functions (Days 32–38)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 32 | Basic function definitions | `day_32_functions_basics.py` |
| 33 | Positional, keyword, and variable-number arguments | `day_33_arguments.py` |
| 34 | Mutable objects as arguments and default values | `day_34_mutable_arguments.py` |
| 35 | Local, nonlocal, and global variables | `day_35_scope_variables.py` |
| 36 | Assigning functions to variables; lambda expressions | `day_36_lambdas.py` |
| 37 | Generator functions and decorators | `day_37_generators_decorators.py` |
| 38 | 🧪 Useful functions practice lab | `day_38_functions_lab.py` |

</details>

<details>
<summary><strong>1.7 Modules and Scoping Rules (Days 39–43)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 39 | What is a module? The `import` statement | `day_39_modules_import.py` |
| 40 | Module search path; where to place your modules | `day_40_module_path.py` |
| 41 | Private names; library and third-party modules | `day_41_private_names_libraries.py` |
| 42 | Scoping rules, namespaces, the built-in namespace | `day_42_namespaces_scoping.py` |
| 43 | 🧪 Creating your own module — practice lab | `day_43_module_lab.py` |

</details>

<details>
<summary><strong>1.8 Python Programs (Days 44–48)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 44 | Program structure: command line, arguments, main guard | `day_44_program_structure.py` |
| 45 | I/O redirection; `argparse` and `fileinput` | `day_45_argparse.py` |
| 46 | Running scripts on UNIX, macOS, and Windows | `day_46_running_scripts.py` |
| 47 | Programs vs modules; distributing Python apps | `day_47_distribution.py` |
| 48 | 🧪 Creating a complete program — practice lab | `day_48_complete_program_lab.py` |

</details>

<details>
<summary><strong>1.9 Filesystem and File I/O (Days 49–55)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 49 | `os.path` vs `pathlib`; absolute and relative paths | `day_49_paths.py` |
| 50 | Manipulating pathnames; getting info about files | `day_50_file_info.py` |
| 51 | More filesystem operations; processing directory trees | `day_51_filesystem_operations.py` |
| 52 | Opening, closing, and file modes | `day_52_opening_files.py` |
| 53 | Reading/writing text and binary data; pathlib I/O | `day_53_reading_writing_data.py` |
| 54 | Terminal I/O; the `struct` module for binary data | `day_54_terminal_io_struct.py` |
| 55 | Pickling and shelving objects; wc project | `day_55_pickle_shelve.py` |

</details>

<details>
<summary><strong>1.10 Exceptions (Days 56–58)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 56 | Philosophy of error handling; types of exceptions | `day_56_exceptions_intro.py` |
| 57 | Raising, catching, custom exceptions, assert | `day_57_raising_exceptions.py` |
| 58 | Exception hierarchy; context managers with `with` | `day_58_context_managers.py` |

</details>

---

## 📘 Part 2 — Advanced Features (Days 59–74)

<details>
<summary><strong>2.1 Classes and OOP (Days 59–64)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 59 | Defining classes; instance variables; methods | `day_59_classes_basics.py` |
| 60 | Class variables; `@staticmethod` and `@classmethod` | `day_60_class_static_methods.py` |
| 61 | Inheritance with class and instance variables | `day_61_inheritance.py` |
| 62 | Private variables/methods; `@property` | `day_62_private_property.py` |
| 63 | Scoping for instances; destructors; multiple inheritance | `day_63_multiple_inheritance.py` |
| 64 | 🧪 OOP practice lab — Library Management System | `day_64_oop_lab.py` |

</details>

<details>
<summary><strong>2.2 Regular Expressions (Days 65–67)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 65 | What is a regex? Special characters and raw strings | `day_65_regex_basics.py` |
| 66 | Extracting matched text; `re.sub()` substitution | `day_66_regex_sub.py` |
| 67 | 🧪 Phone number normalizer — practice lab | `day_67_regex_lab.py` |

</details>

<details>
<summary><strong>2.3 Data Types as Objects (Days 68–70)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 68 | Types as objects; duck typing | `day_68_types_duck_typing.py` |
| 69 | Special methods (`__getitem__`, etc.); list-like objects | `day_69_special_methods.py` |
| 70 | Subclassing built-ins; `UserList`; when to use dunder methods | `day_70_subclassing_builtins.py` |

</details>

<details>
<summary><strong>2.4 Packages and Libraries (Days 71–74)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 71 | Packages, subpackages, `__init__.py`, `__all__` | `day_71_packages.py` |
| 72 | 🧪 Creating a package — practice lab | `day_72_package_lab.py` |
| 73 | The standard library: collections, itertools, datetime | `day_73_standard_library.py` |
| 74 | PyPI, `pip`, `venv`, and the `--user` flag | `day_74_pypi_pip_venv.py` |

</details>

---

## 📙 Part 3 — Working with Data (Days 75–90)

<details>
<summary><strong>3.1 Basic File Wrangling (Days 75–76)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 75 | Organizing data files; handling messy inputs | `day_75_data_file_wrangling.py` |
| 76 | Compressing and grooming files (gzip, zipfile) | `day_76_compressing_files.py` |

</details>

<details>
<summary><strong>3.2 Processing Data Files (Days 77–80)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 77 | Text encoding: ASCII and Unicode | `day_77_text_encoding.py` |
| 78 | Delimited flat files; the `csv` module | `day_78_csv_files.py` |
| 79 | Excel files; data cleaning, sorting, pitfalls | `day_79_excel_cleaning.py` |
| 80 | 🧪 Writing data files; weather data lab | `day_80_writing_data_lab.py` |

</details>

<details>
<summary><strong>3.3 Data Over the Network (Days 81–84)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 81 | Fetching files: FTP, SFTP, HTTP/HTTPS | `day_81_fetching_files.py` |
| 82 | Fetching data via an API | `day_82_api_data.py` |
| 83 | Structured data: JSON and XML | `day_83_json_xml.py` |
| 84 | 🧪 Scraping web data; practice lab | `day_84_web_scraping.py` |

</details>

<details>
<summary><strong>3.4 Saving Data (Days 85–87)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 85 | Python database API; SQLite with `sqlite3` | `day_85_sqlite.py` |
| 86 | SQLAlchemy ORM; Alembic migrations | `day_86_sqlalchemy.py` |
| 87 | NoSQL overview; Redis; MongoDB | `day_87_nosql.py` |

</details>

<details>
<summary><strong>3.5 Exploring Data (Days 88–90)</strong></summary>

| Day | Topic | File |
|:---:|-------|------|
| 88 | Python vs spreadsheets; pandas DataFrames | `day_88_pandas_intro.py` |
| 89 | Data cleaning with pandas; loading & saving | `day_89_pandas_cleaning.py` |
| 90 | 🧪 Aggregation, merging, plotting; **Capstone Project** 🎓 | `day_90_capstone.py` |

</details>

---

## 📖 How to Use

### 📺 For YouTube Viewers
1. Watch the video for the current day
2. Open the corresponding `.py` file
3. Read through the code and comments
4. Run the file: `python day_XX_topic.py`
5. Modify and experiment!

### 🧑‍💻 For Self-Learners
```
Monday    → Watch/read 2 days
Tuesday   → Practice + modify the code
Wednesday → Watch/read 2 days
Thursday  → Practice + mini-project
Friday    → Watch/read 2 days
Weekend   → Build something using what you learned
```

### 📋 Prerequisites
| Requirement | Details |
|-------------|---------|
| **Python** | 3.10 or higher ([download](https://python.org/downloads)) |
| **Editor** | VS Code, PyCharm, or any text editor |
| **OS** | Windows, macOS, or Linux |
| **Experience** | None! We start from scratch |

### 📦 Optional Dependencies (Part 3)
```bash
pip install pandas matplotlib openpyxl requests beautifulsoup4
```
> Parts 1 and 2 use **only the Python standard library** — no installs needed!

---

## 🏗️ Project Structure

```
📁 90-Day-Python-Roadmap/
│
├── 📂 Part1_Essentials/                    # Days 1–58
│   ├── day_01_indentation_and_comments.py
│   ├── day_02_variables_and_type_hints.py
│   ├── ...
│   └── day_58_context_managers.py
│
├── 📂 Part2_Advanced/                      # Days 59–74
│   ├── day_59_classes_basics.py
│   ├── ...
│   └── day_74_pypi_pip_venv.py
│
├── 📂 Part3_Data/                          # Days 75–90
│   ├── day_75_data_file_wrangling.py
│   ├── ...
│   └── day_90_capstone.py
│
└── 📄 README.md
```

---

## 🌟 What You'll Build

Throughout the 90 days, you'll create real mini-projects:

| Day | Project | Skills Used |
|:---:|---------|-------------|
| 13 | List Examiner | Lists, loops, functions |
| 24 | Word Frequency Counter | Dicts, file I/O |
| 31 | Text File Analyzer | File I/O, string methods |
| 38 | Function Toolkit | Functions, decorators |
| 48 | Complete CLI Program | argparse, modules |
| 55 | Word Count (`wc`) Clone | File I/O, pickling |
| 64 | Library Management System | OOP, inheritance |
| 67 | Phone Number Normalizer | Regex |
| 72 | TextUtils Package | Packages, imports |
| 80 | Weather Data Analyzer | CSV, data processing |
| 84 | Web Data Scraper | HTML parsing, regex |
| 85 | Student Database | SQLite, SQL |
| 90 | **Sales Analytics Dashboard** 🏆 | pandas, plotting, APIs |

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. 🍴 **Fork** the repository
2. 🔧 **Create** a feature branch (`git checkout -b improve-day-15`)
3. ✅ **Commit** your changes (`git commit -m 'Add clearer examples to Day 15'`)
4. 📤 **Push** to your branch (`git push origin improve-day-15`)
5. 🔁 **Open** a Pull Request

### Ideas for Contributions
- Fix typos or improve explanations
- Add more practice exercises
- Translate comments to other languages
- Add test files for each day

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

You are free to use this code for:
- ✅ Personal learning
- ✅ YouTube tutorials
- ✅ Teaching classes
- ✅ Any other purpose

---

## ⭐ Support

If this roadmap helped you, please consider:

- ⭐ **Starring** this repository
- 📺 **Subscribing** to the YouTube channel
- 🔗 **Sharing** with friends who want to learn Python
- 💬 **Opening an issue** if you find a bug or have a suggestion

---

<p align="center">
  <strong>Made with 🐍 and ❤️ for the Python community</strong><br/>
  <sub>Happy coding! See you at Day 90! 🎓🚀</sub>
</p>
