# Capitals Quiz Website README

## Overview

This project is a web-based quiz application that tests users' knowledge of world capitals. The application uses Express.js as the web server framework, Body-Parser for parsing form data, and PostgreSQL for storing and retrieving quiz questions.

## Prerequisites

Ensure you have the following installed:
- Node.js
- npm (Node package manager)
- PostgreSQL

## Usage

- The home page displays a country, and you need to type its capital.
- Submit your answer through the form.
- The application checks your answer, updates your score, and presents the next question.

## Project Structure

- `index.js`: Main server file.
- `public/`: Directory for static files (e.g., CSS, JS).
- `views/`: Directory for EJS templates used for rendering HTML.

## Dependencies

- express
- body-parser
- pg
- ejs
