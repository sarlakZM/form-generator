# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

## Overview

You are tasked with creating a dynamic form generator application in React, based on a pre-defined schema. The form should support conditional rendering, validation, and other interactive features.

## Built With

[![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)](https://vite.dev/)
[![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white)](https://react-hook-form.com/)
[![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)](https://mui.com/)


## Features

**Development Requirement**

- Zustand for state management.
- React Hook Form + Yup for form handling and validation.
- TypeScript for fully typed code.
- MUI (plus Emotion, if desired) for styling.
- Todo (Incomplete): React Testing Library (RTL) for unit testing.
- Todo (Incomplete): (Optionally) MirageJS for mocking an API if you’d like to demonstrate backend interactions.

**Core Requirements**

1.Form Creation UI
  - Create a new form.
  - Add elements (e.g., text, checkbox).

2.Form Rendering UI
  - Takes the form schema.
  - Renders the actual fillable form.
  - Applies conditional logic (e.g., show/hide fields based on other fields’ values).

3.Validation
  - If isRequired is set to true, the field must be validated as required using React Hook Form + Yup.
  - Show appropriate error messages for validation failures.
  
4.Data Persistence
  - Use local storage or a mocked API (MirageJS) to save and retrieve created forms.
  - Forms should be loadable for editing and re-rendering.


## Run Locally

Go to the project directory

```bash
  cd form-generator-assignment
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

Test the server

```bash
  npm run test
```

Build the server

```bash
  npm run build
```


