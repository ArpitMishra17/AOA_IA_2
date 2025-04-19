# Sum of Subsets Problem Simulation

Welcome to the **Sum of Subsets Problem Simulation**, a web-based tool that visualizes the backtracking algorithm for solving the Sum of Subsets problem. This README provides comprehensive user documentation to help you use the application effectively.

---

## Overview

The **Sum of Subsets Problem Simulation** allows users to input a set of positive integers and a target sum, then find all subsets that sum to the target. The tool offers an interactive interface to:

- Enter numbers and a target sum.
- Step through the algorithm manually or automatically.
- Visualize the decision tree as the algorithm explores subsets.
- View step-by-step explanations and solutions.

Designed for educational purposes, this simulation helps users understand backtracking and pruning in combinatorial problem-solving.

---

## System Requirements

- **Web Browser**: Google Chrome, Mozilla Firefox, Safari, or Microsoft Edge (latest versions recommended).
- **Internet Access**: Required to access the simulation online (e.g., via GitHub Pages at https://arpitmishra17.github.io/AOA_IA_2/). Not needed for local use.
- **Device**: Compatible with desktops, laptops, tablets, or smartphones. A larger screen is recommended for optimal viewing of the decision tree.
- **No Additional Software**: The application runs entirely in the browser.

---

## Getting Started

### Access the Simulation

1. Visit the deployed site (e.g., [https://arpitmishra17.github.io/AOA_IA_2/](https://arpitmishra17.github.io/AOA_IA_2/)).
2. Alternatively, open `index.html` locally by double-clicking it in your file explorer.

---

### Interface Overview

#### Input Section:
- **Numbers**: Enter comma-separated positive integers (e.g., `1,2,3,4`).
- **Target Sum**: Enter the desired sum (e.g., `7`).

#### Buttons:
- **Solve**: Initiates the algorithm.
- **Next Step**: Advances one step (enabled after solving).
- **Auto Solve**: Runs the algorithm automatically (enabled after solving).
- **Reset**: Clears the simulation (enabled after solving).

#### Legend: Color codes for the decision tree:
- **Blue**: Exploring (current node).
- **Green**: Solution (subset sums to target).
- **Red**: Pruned/Rejected (subset cannot lead to a solution).
- **Gray**: Normal (visited but not current).

#### Decision Tree:
- SVG visualization of the algorithm’s exploration.

#### Algorithm Steps:
- Scrollable list of step explanations.

#### Results:
- Displays solutions or a message if none are found.

---

## Usage Instructions

### Enter Inputs

- Input positive integers in the “Numbers” field, separated by commas (e.g., `1,2,3,4`). Spaces are optional.
- Enter a positive integer in the “Target sum” field (e.g., `7`).
  - Example: For subsets of `[1,2,3,4]` summing to `7`, enter `1,2,3,4` and `7`.

---

### Start the Simulation

- Click **“Solve”** to begin.
- Valid inputs enable the **“Next Step,”** **“Auto Solve,”** and **“Reset”** buttons, which display a purple border and shadow.
- Invalid inputs (e.g., empty numbers or non-numeric target) trigger an alert to correct them.

---

### Explore the Algorithm

#### Manual Stepping:
- Click **“Next Step”** to progress one step.
- Updates occur in:
  - **Decision Tree**: Current node highlighted in blue.
  - **Algorithm Steps**: New step added (highlighted with a purple border).
  - **Results**: Solutions displayed as found.

#### Automatic Running:
- Click **“Auto Solve”** for continuous execution (updates every 0.5 seconds).
- Button changes to **“Stop Auto”**; click to pause.

#### Resetting:
- Click **“Reset”** to clear the tree, steps, and results.

---

### Interpret Outputs

- **Decision Tree**: Shows nodes (subsets) and edges (include/exclude decisions), color-coded by status.
- **Algorithm Steps**: Details each decision (e.g., including a number, pruning a branch).
- **Results**: Lists subsets summing to the target (e.g., `[1,2,4], [3,4]`) or indicates no solutions.

---

### Experiment with Inputs

Try various numbers and targets, such as:
- **Numbers**: `1,2,3,4`, **Target**: `7` → Solutions: `[1,2,4], [3,4]`.
- **Numbers**: `2,3,4,5`, **Target**: `9` → Solutions: `[2,3,4], [4,5]`.

---

## Example Walkthrough

### Input:
- **Numbers**: `1,2,3,4`
- **Target Sum**: `7`

### Steps:
1. Enter `1,2,3,4` in the numbers field and `7` in the target field.
2. Click **“Solve.”** The **“Next Step,”** **“Auto Solve,”** and **“Reset”** buttons enable with a purple border and shadow.
3. Click **“Next Step”** to step through:
   - The decision tree grows, with nodes turning blue (exploring), green (solution), or red (pruned).
   - Steps list decisions like **“Include 1”** or **“Pruning: Including 3 would exceed target.”**
4. Solutions `[1,2,4]` and `[3,4]` appear in the results section.
5. Use **“Auto Solve”** to complete automatically or **“Reset”** to start over.

---

## Troubleshooting

- **“Please enter valid numbers and target sum” Alert**:
  - Ensure numbers are comma-separated positive integers (e.g., `1,2,3`).
  - Verify target is a positive integer (e.g., `7`, not empty or `abc`).

- **Buttons Not Enabling**:
  - Click **“Solve”** first.
  - Correct invalid inputs if prompted.

- **Decision Tree Issues**:
  - Update your browser, as SVG rendering requires modern support.
  - Check the browser’s console (F12, “Console” tab) for errors.

- **Site Not Loading**:
  - Verify the URL (e.g., [https://arpitmishra17.github.io/AOA_IA_2/](https://arpitmishra17.github.io/AOA_IA_2/)).
  - Clear cache or try another browser.

- **Slow Performance**:
  - Use smaller inputs for complex trees (e.g., fewer than 10 numbers).
  - Ensure your device has adequate resources.

---

## Additional Notes

- **Accessibility**: The interface is visual. Request enhancements like keyboard navigation or screen reader support if needed.
- **Performance**: Optimized for small to medium inputs. Large inputs may slow due to backtracking’s exponential nature.
- **Deployment**: Hosted on GitHub Pages. Local use requires no internet.
- **Feedback**: Report bugs or request features via the GitHub repository ([https://github.com/ArpitMishra17/AOA_IA_2](https://github.com/ArpitMishra17/AOA_IA_2n)).
- **Educational Use**: Suitable for students, teachers, or anyone learning backtracking algorithms.

---

## Contact

For support, visit the GitHub repository’s issues page or contact the developer through GitHub. Enjoy the **Sum of Subsets Problem Simulation**!