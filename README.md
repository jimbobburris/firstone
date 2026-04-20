# To-Do List Application

A simple, elegant to-do list application built with HTML, CSS, and JavaScript featuring local storage functionality.

## Features

- ✅ **Add Tasks** - Quickly add new tasks to your list
- ✅ **Mark Complete** - Check off tasks as you complete them
- ✅ **Delete Tasks** - Remove individual tasks
- ✅ **Filter Tasks** - View all, active, or completed tasks
- ✅ **Local Storage** - Your tasks are automatically saved and persist across browser sessions
- ✅ **Task Statistics** - See total and completed task counts
- ✅ **Responsive Design** - Works great on desktop and mobile devices

## How to Use

1. Open `index.html` in your web browser
2. Type a task in the input field and click "Add" (or press Enter)
3. Check the checkbox to mark a task as completed
4. Click "Delete" to remove a task
5. Use the filter buttons to view different task categories
6. Click "Clear Completed" to remove all completed tasks

## Local Storage

This application uses browser's local storage to persist your tasks. Your to-do list will be saved automatically and restored when you return to the page.

## Installation

No installation required! Simply download the files and open `index.html` in any modern web browser.

## File Structure

- `index.html` - Main HTML structure
- `style.css` - Styling and responsive design
- `script.js` - Application logic and local storage handling

## Browser Support

Works in all modern browsers that support:
- ES6 JavaScript
- Local Storage API
- CSS Grid and Flexbox

## Features in Detail

### Local Storage
Tasks are automatically saved to the browser's local storage under the key `todoList`. This ensures your tasks persist even after closing the browser.

### Filtering
- **All** - Shows all tasks
- **Active** - Shows only incomplete tasks
- **Completed** - Shows only completed tasks

### Statistics
The app tracks:
- Total number of tasks
- Number of completed tasks
- Option to clear all completed tasks at once

## Future Enhancements

- Edit existing tasks
- Task priorities
- Due dates
- Categories/Tags
- Dark mode
- Export/Import tasks
