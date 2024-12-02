# API Search Bot

## Description

The **API Search Bot** is a Python application that allows users to search for products from the **Fake Store API** based on several filters. It offers a graphical user interface (GUI) created using the **PySimpleGUI** library, providing a simple and interactive way to search for products based on ID, keyword, category, or price. Users can also view the results in a table format and export the results to a local SQLite database.

The bot can filter products using the following criteria:
- **Product ID**
- **Keyword**
- **Category**
- **Maximum Price**

Additionally, users can list all available products, and the bot will display the results in a structured table format.

### Project Information

- **Created by**: Jordan, Peter, Matt, Ethan
- **Date**: 12.1.24
- **Course**: COMP390

## Features

- **Search**: Search products based on:
  - Product ID
  - Keyword (search by title)
  - Category (electronics, jewelry, men's clothing, women's clothing)
  - Maximum Price
- **Display Results**: Show search results in a table format with columns: ID, Title, Price, and Category.
- **Export to Database**: Export search results to a local SQLite database (`products.db`).
- **Responsive Footer**: The window displays a footer with credits to the team.

## Requirements

- Python 3.x
- PySimpleGUI
- requests
- sqlite3 (comes with Python standard library)

## Installation

To get started, ensure you have Python 3.x installed on your system. Then, install the necessary dependencies by running the following command:

```bash
pip install PySimpleGUI requests
