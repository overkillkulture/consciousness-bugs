# consciousness-bugs
Public bug tracker for Consciousness Revolution

MagzMayne Psychic Investigator reporting for duty

## Button Bugs Collection

This repository demonstrates common button-related bugs found in web development. Open `button-bugs.html` in your browser to see them in action.

### Documented Bugs

1. **Double Submit** - Clicking submit multiple times sends multiple requests (no debouncing)
2. **Memory Leak** - Event listeners added repeatedly without cleanup
3. **Race Condition** - Async operations completing in unexpected order
4. **Missing Disabled State** - Button remains clickable during async operations
5. **Accessibility Issues** - Div elements styled as buttons lack keyboard navigation
6. **Clickjacking Vulnerability** - Invisible overlays preventing button interaction
7. **Unintended Form Submission** - Buttons without `type="button"` trigger form submits
8. **State Desynchronization** - Button display state doesn't match actual application state

### How to View

Simply open `button-bugs.html` in any modern web browser to interact with the bugs and their fixes.
