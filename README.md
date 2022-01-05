# To-Do List CLI App

> This project aims at creating a command-line interface application using Typer to help manage a simple to-do list.

## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)

## General Information

* C.R.U.D operations on a set of to-do list items

## Technologies Used

* Version 0.1.0

## Features

List the ready features here:

| Command            | Description                                                  |
| ------------------ | ------------------------------------------------------------ |
| `init`             | Initializes the application's to-do database.                |
| `add DESCRIPTION`  | Adds a new to-do to the database with a `DESCRIPTION`.       |
| `list`             | Lists all the to-dos in the database.                        |
| `complete TODO_ID` | Completes a to-do by setting it as done using its `TODO_ID`. |
| `remove TODO_ID`   | Removes a to-do from the database using its `TODO_ID`.       |
| `clear`            | Removes all the to-dos by clearing the database.             |

## Setup

* Setup and Activate Python venv

* Install dependencies
  * `python -m pip install -r requirements.txt`

## Usage

How does one go about using it?

* Initialize the application
  * `python -m todo init`
* Get help
  * `python -m todo --help`

* Add to-do item
  * `python -m todo add Get some milk -p 1`
  * `python -m todo add Clean the house --priority 3`
* List items
  * `python -m todo list`
* Mark to-do item as completed
  * `python -m todo complete 1`

* Remove to-do item
  * `python -m todo remove 1`
* Clear all to-do items
  * `python -m todo clear`

## Project Status

Project is: _in progress_
