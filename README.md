README: NEO BST Visualizer, Ultra Stack Operations Visualizer, and Data Structure Visualizations
This README provides a comprehensive guide for end-users to test the NEO BST Visualizer, Ultra Stack Operations Visualizer, and Data Structure Visualizations web applications. These tools are designed to help users interactively explore and understand Binary Search Trees (BSTs), Stacks, and their operations through visualizations and animations. The guide includes setup instructions, testing steps, and a table of contents for easy navigation.

Table of Contents

1. Overview
   Introduction to the three applications and their purposes

2. Prerequisites
   System requirements for running the applications

3. Setup Instructions
   Steps to set up the applications on your local machine

4. Testing the NEO BST Visualizer
   Detailed instructions for testing the BST Visualizer.

5. Testing the Ultra Stack Operations Visualizer
   Instructions for testing the Stack Visualizer.

6. Testing the Data Structure Visualizations
   Instructions for testing the main visualization page.

7. Troubleshooting
   Common issues and solutions.

8. Additional Notes
   Extra information for users.

1)  Overview
   This project consists of three HTML-based web applications designed to visualize data structures and their operations:

NEO BST Visualizer (BinarySearch.html): An advanced tool for visualizing Binary Search Tree operations such as insertion, deletion, searching, traversals, and more. It includes features like theme customization, zoom controls, and background selection.
Ultra Stack Operations Visualizer (Stack.html): A tool to visualize stack operations (push, pop, peek) with a focus on the Last-In-First-Out (LIFO) principle. It includes a memory representation, operation history, and time complexity details.
Data Structure Visualizations (Visulization.html): A landing page that provides an overview of BSTs and Stacks, with links to their respective visualizers. It includes brief descriptions, animations, and interactive mini-demos.
These applications are built using HTML, CSS, JavaScript, and external libraries like Bootstrap and Font Awesome. They are designed to be user-friendly and work on both desktop and mobile devices.

2. Prerequisites
   To test these applications, ensure you have the following:

Web Browser: A modern browser like Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari (latest versions recommended).
Internet Connection: Required to load external libraries (e.g., Bootstrap, Font Awesome) and background images.
Local Server (Optional): For a better testing experience, you can use a local server (e.g., using VS Code's Live Server extension, Node.js http-server, or Python's http.server).
Files: Ensure you have the following files in your project directory:
BinarySearch.html (NEO BST Visualizer)
Stack.html (Ultra Stack Operations Visualizer)
Visulization.html (Data Structure Visualizations)
BST.css (for BST Visualizer styling)
Stack.css (for Stack Visualizer styling)
BST.js (for BST Visualizer logic)
Stack.js (for Stack Visualizer logic) 
3) Setup Instructions

1. Clone or Download the Project:
   If using a repository, clone it to your local machine.
   Alternatively, download the HTML, CSS, and JS files mentioned above.
2. Organize the Files:
   Place all files in a single directory for simplicity.
   Ensure the file names match exactly as referenced in the HTML files (e.g., BST.css, Stack.js).
3. Run the Application:
   Option 1: Direct Browser Access:
   Open each HTML file (BinarySearch.html, Stack.html, Visulization.html) directly in your browser by double-clicking the file or dragging it into the browser window.
   Note: Some features (e.g., loading local files) may be restricted due to browser security policies.
   Option 2: Local Server (Recommended):
   Use a local server to avoid CORS issues:
   VS Code Live Server: Install the Live Server extension in VS Code, right-click the HTML file, and select "Open with Live Server."
   Node.js: Install Node.js, then run npx http-server in the project directory and access the files via http://localhost:8080.
   Python: Run python -m http.server 8000 in the project directory and access the files via http://localhost:8000.
4. Verify Dependencies:
   Ensure your browser can access the internet to load external libraries (e.g., Bootstrap, Font Awesome).
   Check the browser console (F12 > Console) for any errors related to missing files or network issues.

4) Testing the NEO BST Visualizer
   The NEO BST Visualizer (BinarySearch.html) allows users to interact with a Binary Search Tree through various operations.

Steps to Test

1. Open the Application:
   Open BinarySearch.html in your browser.
   You should see a welcome screen with the title "NEO BST VISUALIZER" and a "Begin Exploration" button.
2. Start the Visualizer:
   Click the "Begin Exploration" button.
   The main visualizer interface should appear, showing a control panel with buttons and an empty SVG area for the tree.
3. Test Basic Operations:
   Insert a Node:
   Enter a number (e.g., 10) in the "Node Value" input field.
   Click the "Insert" button.
   Verify that a node with the value 10 appears in the SVG area.
   Insert More Nodes:
   Add more values (e.g., 5, 15, 3, 7) and confirm the tree structure updates correctly (left children < parent < right children).
   Search for a Node:
   Enter a value (e.g., 7) in the "Node Value" field and click "Search."
   Check if the node is highlighted or a message appears indicating the search result.
   Delete a Node:
   Enter a value (e.g., 5) and click "Delete."
   Verify that the node is removed and the tree is restructured appropriately.
4. Test Traversals:
   Click the "Preorder," "Inorder," "Postorder," and "Level Order" buttons.
   Observe the order in which nodes are highlighted or listed in the output text at the bottom of the SVG.
5. Test Advanced Features:
   Find Min/Max:
   Click "Min" and "Max" buttons to highlight the minimum and maximum values in the tree.
   Find LCA:
   Enter two values (e.g., 3 and 7) in the "First Node" and "Second Node" fields.
   Click "Find LCA" and verify the lowest common ancestor is displayed.
   Find Diameter:
   Use the same two values and click "Diameter" to see the distance between them.
6. Test Visual Settings:
   Click the gear icon (Settings) in the floating controls.
   Change the theme (e.g., to "dark" or "red") and confirm the color scheme updates.
   Change the background to a "starlit night sky" (as per your edited image) and verify the background updates.
   Use the zoom controls to zoom in and out, ensuring the tree scales appropriately.
7. Test Mobile Responsiveness:
   Open the page on a mobile device or use the browser's developer tools to simulate a mobile view.
   Test touch gestures (pinch to zoom, drag to pan) and ensure buttons are tappable.
8. Return to Home:
   Click the home icon in the floating controls.
   Verify that you are redirected to Visulization.html.

5) Testing the Ultra Stack Operations Visualizer
   The Ultra Stack Operations Visualizer (Stack.html) focuses on stack operations with a LIFO structure.

Steps to Test

1. Open the Application:
   Open Stack.html in your browser.
   You should see a navbar, a title "Stack Operations Visualizer," and sections for visualization, operations, and metrics.
2. Test Stack Operations:
   Push an Element:
   Enter a value (e.g., 42) in the "Enter element" input field.
   Click the "Push" button.
   Verify that the element appears at the top of the stack visualization and the "TOP" pointer updates.
   Push More Elements:
   Add more values (e.g., 15, 99) and confirm the stack grows upward.
   Pop an Element:
   Click the "Pop" button.
   Check if the top element (e.g., 99) is removed and the "TOP" pointer moves down.
   Peek at the Top:
   Click the "Peek" button.
   Verify that a message or highlight shows the top element (e.g., 15) without removing it.
   Clear the Stack:
   Click the "Clear" button.
   Confirm that all elements are removed and the stack is empty.
3. Test Stack Metrics:
   Push a few elements and check the "Current Size" and "Capacity" metrics.
   Verify that the "Stack Usage" bar updates as elements are added or removed.
   Check the "Last Operation" section to see the most recent action (e.g., "Pushed 42").
4. Test Memory Representation:
   Add elements to the stack and observe the SVG-based memory layout.
   Confirm that the memory diagram updates with each push and pop operation.
5. Test Operation History:
   Perform multiple operations (push, pop, peek) and check the "Operation History" section.
   Verify that each operation is logged with details (e.g., "Pushed 42", "Popped 15").
6. Test Theme Toggle:
   Click the theme toggle button in the navbar.
   Confirm that the interface switches between light and dark modes.
7. Test Navigation:
   Click the "Main Page" link in the navbar.
   Verify that you are redirected to Visulization.html.
8. Test Mobile Responsiveness:
   Open the page on a mobile device or simulate a mobile view.
   Test button taps and ensure the layout adjusts (e.g., navbar collapses, buttons are tappable).

6)  Testing the Data Structure Visualizations
   The Data Structure Visualizations page (Visulization.html) serves as the main landing page, linking to the BST and Stack visualizers.

Steps to Test

1. Open the Application:
   Open Visulization.html in your browser.
   You should see a header "Data Structure Visualizations" and two cards for BST and Stack.
2. Explore the BST Section:
   Read the description and key operations for the Binary Search Tree.
   Observe the animated GIF showing BST operations.
   Click the "Interactive BST Visualization →" button.
   Verify that you are redirected to BinarySearch.html.
3. Explore the Stack Section:
   Read the description and key operations for the Stack.
   Observe the animated GIF showing stack operations.
   Test the interactive stack demo:
   Click the "Push" button to add elements to the stack.
   Click the "Pop" button to remove elements.
   Confirm that the stack updates with animations (elements fade in/out).
   Click the "Interactive Stack Visualization →" button.
   Verify that you are redirected to Stack.html.
4. Test Visual Effects:
   Hover over the algorithm cards and confirm they lift slightly (translateY effect).
   Hover over the images and verify they scale up slightly.
5. Test Mobile Responsiveness:
   Open the page on a mobile device or simulate a mobile view.
   Ensure the layout adjusts (cards stack vertically, text is readable, buttons are tappable).
7. ## 🔧 Troubleshooting Guide

| Issue                      | Possible Cause         | Solution |
|----------------------------|------------------------|----------|
| **Page doesn't load**      | Missing CSS/JS files   | Ensure `BST.css`, `Stack.css`, `BST.js`, and `Stack.js` are in the same directory |
| **Buttons don't work**     | JavaScript errors      | Check browser console (`F12` > Console) |
| **Mobile gestures fail**   | Touch events disabled  | Test on a physical device |

## 🛠 Troubleshooting

<details>
<summary><b>Page doesn't load</b></summary>

**Cause:** Missing CSS/JS files  
**Fix:** Ensure all `.css` and `.js` files are in the same directory
</details>

<details>
<summary><b>Buttons unresponsive</b></summary>

**Cause:** JavaScript errors  
**Fix:** Open browser console (`F12`) and check for red error messages
</details>

## 🚦 Troubleshooting

### 🖥 Page won't load
- **Cause:** Missing files  
- **Fix:** Verify these files exist:  
  ```bash
  BST.css, Stack.css, BST.js, Stack.js

  
### 4. **Warning Boxes**
```markdown
## ⚠ Troubleshooting

> **Page Load Failure**  
> - Cause: Missing dependencies  
> - Solution: Check file paths in `<head>` tag

> **Mobile Issues**  
> - Cause: Touch event conflicts  
> - Solution: Use Chrome DevTools > Toggle Device Toolbar

## 🧰 Troubleshooting Steps

1. **Symptom:** Page blank  
   - Check: Browser console for 404 errors  
   - Fix: Reinstall dependencies

2. **Symptom:** Buttons frozen  
   - Check: JavaScript console logs  
   - Fix: Update event listeners in `BST.js`

8) Additional Notes
File Naming: The goHome() function in BinarySearch.html references Visulization.html, which seems to be a typo (should be Visualization.html). Correct the file name or update the reference to match.
Background Image: The NEO BST Visualizer has been updated to use a "starlit night sky" background as per your edited image. Ensure the background image URL in the settings panel is accessible.
Dependencies: The applications rely on external libraries. If you need to run offline, download these libraries and reference them locally.
Testing on Mobile: For the best mobile experience, use a local server to avoid CORS issues with touch events and file loading.
Customization: You can further customize the visualizers by modifying the CSS files (BST.css, Stack.css) or adding more background options in BinarySearch.html.   # Front-end-projects
# Front-end-project
# Front-end-project
# front-end-2
