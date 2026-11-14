# Contact-book
A Python contact book built with classes: add, search, delete, and list contacts, with duplicate names rejected.
# Contact Book

A small Python program that stores contacts, built to practice object-oriented programming.

## What it does

- Stores contacts, each with an ID, a name, and a phone number
- Adds a contact, and rejects it if a contact with the same name already exists (capitalization is ignored)
- Searches for a contact by name
- Deletes a contact by name
- Shows all contacts, or a message if the list is empty

## How it's built

- `Contact` represents one person: ID, name, and phone number.
- `ContactBook` holds a list of contacts and has the methods `add`, `search`, `delete`, and `show_all`.

## How to run

1. Install Python 3.
2. Run the file: `python contact_book.py`

## What I practiced

- Writing classes, attributes, and methods
- One class that holds a collection of another class's objects
- Looping and comparing strings, with case-insensitive matching
- Handling the "not found" and "empty list" cases

## Planned improvements

- Save contacts to a JSON file and load them back
- Pytest tests
- A simple menu in the terminal
