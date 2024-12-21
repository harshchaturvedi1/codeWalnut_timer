# Timer App

A **React + Vite** application that allows you to create and manage multiple timers simultaneously, featuring **snack bar notifications**, **validation**, **localStorage persistence**, and more. This project demonstrates **UI refinement**, **state management**, **error handling**, and **unit/component testing** using **Vitest**.

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Project Setup](#project-setup)
4. [Running the Project](#running-the-project)
5. [Running Tests](#running-tests)

---

## Overview

The **Timer App** lets you:

- Add and edit timers in a single modal component.
- Run multiple timers simultaneously.
- Display snack bar notifications on timer completion or invalid form submission.
- Persist timer data in **localStorage** so it remains after a refresh.
- Test validation logic, UI components, and store functionalities with **Vitest**.

---

## Features

1. **Simultaneous Timers**: Allows multiple timers to run at once.
2. **Snack Bars**:
   - Timer completion triggers a snack bar that also controls when the notification sound stops.
   - Error snack bars appear when form validation fails.
3. **Consolidated Modals**: A single, reusable modal for both adding and editing timers.
4. **Reusable Components**: Common buttons and layouts extracted into **shared** components.
5. **Responsive Snack Bar Placement**:
   - **Desktop**: Top-right corner.
   - **Mobile**: Bottom of the screen.
6. **LocalStorage Persistence**: Timers remain intact across page refreshes.
7. **Comprehensive Testing**: Unit tests for validation logic and component tests for key UI elements.

---

## Project Setup

1. **Clone the Repository**
   ```bash
   git clone git@github.com:harshchaturvedi1/codeWalnut_timer.git
   ```
2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Running tests**
   ```bash
   npm run test
   ```

## Running the Project

1. **Run the development server**
   ```bash
   npm run dev
   ```

## Running Tests

```bash
npm run dev
```
