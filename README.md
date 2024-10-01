# To-Do List Interview Task

## Objective

The goal of this task is to assess your proficiency with React, TypeScript, and problem-solving skills by building a small application. You will create a To-Do List with progressively more complex features, testing different aspects of your React and TypeScript knowledge.

## Task Breakdown

### Level A: Basic To-Do List with Sorting

1. **Objective**: Create a basic to-do list that allows users to add tasks and display them.
2. **Requirements**:
   - Users should be able to add new tasks.
   - Tasks should be displayed in the order they are added.
   - Users can delete tasks from the list.
   - Implement a dropdown to toggle between sorting tasks alphabetically and by the time they were added.
   - Define appropriate TypeScript types/interfaces for tasks and ensure type safety.

### Level B: Task Priority and Search

1. **Objective**: Enhance the to-do list with task priority and search functionality.
2. **Requirements**:
   - Users should be able to assign a priority (high, medium, low) to tasks.
   - Add the ability to filter tasks by priority.
   - Implement a search box to filter tasks based on text input.
   - Users should be able to mark tasks as complete or incomplete.
   - Ensure type safety when adding features like task status and priority.

### Level C: Optimized Search and Persistence

1. **Objective**: Add performance optimizations and a drag-and-drop sorting feature.
2. **Requirements**:
   - Delay filtering until the user stops typing using a debounced function.
   - Persist tasks in `localStorage` to maintain the list across page reloads.
   - Use TypeScript to create utility types or functions if needed (e.g., for debouncing).

## Instructions

1. Fork or clone this repository.
2. The project is set up with a skeleton in `App.tsx`. You can start building your solution directly in this file.
3. Follow the progression from Level A to Level C, implementing the required features.
4. Use TypeScript features such as interfaces, union types, and optional properties to ensure type safety throughout the application.
5. Utilize React hooks like `useState` and `useEffect` while maintaining TypeScript correctness.

## Setup

1. Install the dependencies:

   ```bash
   npm install
   ```
