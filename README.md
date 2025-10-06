QLang — Library of Universal Laws
QLang is an open-source web application that provides an interactive library of fundamental universal laws across physics, cosmology, information theory, biology, chemistry, and mathematics. Users can query laws, explore the full library, view random laws, and download the dataset for offline use.
Features

Interactive Query System: Ask questions about universal laws and receive synthesized responses based on keyword and phrase matching.
LaTeX Formula Rendering: Mathematical formulations are displayed using MathJax for clarity.
Library View: Browse all laws, filter by category, and sort by name, confidence, or discovery date.
Random Law Display: Discover a random law with detailed information.
Query History: Revisit past questions stored in local storage.
Downloadable Data: Export the laws as a JSON file for analysis or offline use.
Accessible Design: ARIA labels, keyboard navigation, and high-contrast visuals for inclusivity.

Setup

Clone the Repository:
git clone https://ouadimaakoul4.github.io/Qlang


Serve the Application:

Use a local server (e.g., python -m http.server or VS Code Live Server) to serve index.html and laws.json.
Ensure an internet connection for CDN dependencies (MathJax, marked.js).


Dependencies:

No local installations required; all dependencies are loaded via CDN:
marked.js
MathJax
Polyfill


Contributing
We welcome contributions! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make changes (e.g., add new laws to laws.json, enhance query logic, improve UI).
Test locally to ensure compatibility.
Submit a pull request with a clear description of changes.

Adding New Laws

Edit laws.json with the same structure as existing entries.
Ensure statement_latex is valid for MathJax rendering.
Update questionTypes in index.html if new keywords or categories are introduced.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For questions or suggestions, open an issue or contact the maintainers at ouadimaakoul1@gmail.com .
