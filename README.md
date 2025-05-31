# CXR (Sixer): Comment-Driven Code Editor

Welcome to **CXR (Comment eXecution and Review)**, pronounced **"Sixer"** — a unique web-based code editor powered by **CPGI (Comment Programmer Generative AI)**. Developed by a team of two, CXR redefines coding by enabling users to write logic as plain-language comments that are then translated into fully functional code. It also functions as a smart code analyzer, capable of detecting and correcting errors in existing code.

---

##  The CPGI Advantage

While traditional AI code generation relies on internal inference, **CPGI** takes a user-first approach: you define the logic through comments, and the AI generates code that exactly matches your intention. This makes it ideal for:

- Learning new programming languages  
- Rapid prototyping  
- Debugging and code validation  
- Educational and instructional use

---

##  Key Features

- ** Comment-to-Code Conversion**  
  Write your logic as comments; CXR converts them into executable code.

- ** Code Analysis & Correction**  
  Paste existing code to get real-time analysis and corrections. If no errors are found, a sample execution is provided.

- ** Multi-Language Support**  
  Select from multiple programming languages or define your own.

- **Downloadable Code**  
  Export the generated or corrected code to a file with the correct extension.

- ** Customizable Themes**  
  Toggle between light and dark modes for an optimized experience.

---

##  How to Use CXR

### Accessing the App

- Run locally at: `http://127.0.0.1:5001/`
- Or use the URL provided after deployment.

###  Interface Overview

- **Header**
  - App name (`CXR`)
  - Theme toggle button
  - Language selection dropdown

- **Main Editor**
  - **Input Section**
    - Text area for writing comments or pasting code
    - `Run` button to trigger generation/analysis
  - **Output Section**
    - Displays the generated code or analysis result
    - `Download`, `Clear`, and `Guide` buttons

- **Footer**
  - Currently reserved for future use

---

##  Functionality

###  Generating Code (Using Comments)

1. Write your logic in the input area using comment syntax:
// create a function that adds two numbers
// print "Hello, World!"
2. Click `Run`.
3. The generated code will appear in the Output section.

###  Analyzing Existing Code

1. Paste code into the input section.
2. Click `Run`.
3. CXR will:
- Correct errors and annotate them, or
- Display sample output if the code is already valid

---

##  Output Section Tools

- **Download**: Saves the code as `project.[extension]` based on selected language
- **Clear**: Clears both input and output fields
- **Guide**: Opens the user guide in a new tab

---

##  Theme Customization

Click the **Theme** toggle in the header to switch between dark and light modes, based on your preference.

---

##  Tips for Best Results

- **Use Clear Comments**: Simple and direct instructions yield better code
- **Be Specific**: Naming variables or functions helps generate more accurate results
- **Always Review Output**: Validate the generated code before use
- **Experiment**: Explore different styles and logic to better understand CPGI’s capabilities

---

##  Conclusion

**CXR (Sixer)** is more than just a code editor — it’s an intelligent, user-guided development tool. Whether you're a beginner learning to code, a teacher designing instructional material, or a developer prototyping fast, CXR gives you full control through natural-language interaction.

Crafted with care by a team of two.  
**Happy Coding!**
