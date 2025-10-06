# QLang v1.0 — Library of Universal Laws

> Explore cosmic knowledge through the fundamental laws that govern our universe

QLang is an interactive web application that catalogs and explores the fundamental laws spanning physics, cosmology, information theory, biology, mathematics, and chemistry. It's a digital compendium of humanity's understanding of universal principles.

---

## 🌟 Features

- 📚 **Comprehensive Library**: 27 universal laws across 6 scientific domains  
- 🔍 **Intelligent Query System**: Ask questions and get relevant laws  
- 🎲 **Random Discovery**: Explore random universal laws  
- 📊 **Mathematical Rendering**: Beautiful LaTeX formula display with MathJax  
- 🎨 **Cosmic Design**: Space-themed UI with smooth animations  
- 📱 **Responsive**: Works perfectly on desktop and mobile devices  

---

## 🗂️ Law Categories

| Category             | Laws Count | Description                                      |
|----------------------|------------|--------------------------------------------------|
| 🔬 Fundamental Physics | 15         | Relativity, quantum mechanics, thermodynamics, electromagnetism |
| 🌌 Cosmology          | 4          | Universe expansion, dark energy, cosmic inflation |
| 💻 Information        | 4          | Computation, entropy, information theory         |
| 🧬 Biology            | 1          | Evolutionary principles                          |
| 📐 Mathematics        | 2          | Probability, logic, incompleteness               |
| ⚗️ Chemistry           | 1          | Periodic table and elements                      |

> ℹ️ *Note: The term "law" is used broadly to include fundamental principles, theorems, and well-established scientific frameworks that govern or describe universal behavior.*

---

## 🚀 Quick Start

### Online Demo
Visit the live application: [QLang Demo](https://ouadimaakoul4.github.io/qlang/)

### Local Installation
```bash
# Clone the repository
git clone https://github.com/ouadimaakoul4/qlang.git
cd qlang

# ⚠️ Important: For full functionality (especially MathJax), serve the app via a local server.
# Double-clicking index.html may cause rendering issues in some browsers.

# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Then open http://localhost:8000 in your browser
```

---

## 💡 Usage Examples

### Asking Questions
Type questions like:
- "What governs the expansion of the universe?"
- "Tell me about quantum mechanics"
- "How does information relate to entropy?"
- "What are the fundamental conservation laws?"

### Exploring the Library
- Click **"View Library"** to see all laws organized by category  
- Use **"Random Law"** for serendipitous discovery  
- Browse mathematical formulations with proper LaTeX rendering  

---

## 🧩 Included Laws

### 🔬 Fundamental Physics (15 laws)
- Second Law of Thermodynamics  
- General Relativity  
- Principles of Quantum Mechanics  
- Mass-Energy Equivalence  
- Heisenberg Uncertainty Principle  
- Newton's Laws of Motion  
- Pauli Exclusion Principle  
- Born Rule  
- Conservation of Energy  
- Conservation of Momentum  
- Maxwell's Equations  
- Special Relativity  
- Schrödinger Equation  
- Dirac Equation  

### 🌌 Cosmology (4 laws)
- Hubble-Lemaître Law  
- Dark Energy Dominance  
- Cosmological Principle  
- Cosmic Inflation  

### 💻 Information Theory (4 laws)
- Bekenstein Bound  
- Landauer's Principle  
- Shannon's Information Entropy  
- Church-Turing Thesis  

### 🧬 Biology (1 law)
- Natural Selection  

### 📐 Mathematics (2 laws)
- Bayes' Theorem  
- Gödel's Incompleteness Theorems  

### ⚗️ Chemistry (1 law)
- Periodic Law  

---

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)  
- **Math Rendering**: MathJax 3.x  
- **Markdown Processing**: Marked.js  
- **Styling**: Custom CSS with CSS Variables  
- **Icons**: Unicode emojis  
- **Fonts**: System fonts (Segoe UI stack)  

---

## 🔧 Customization

### Adding New Laws
Edit the `universalLaws` object in the JavaScript:
```javascript
"your_law_id": {
    "name": "Law Name",
    "category": "category_name",
    "domains": ["domain1", "domain2"],
    "statement": "Law statement",
    "statement_latex": "LaTeX\\_formula",
    "implications": ["Implication 1", "Implication 2"],
    "confidence": 0.95,
    "discovery_date": "Year",
    "discoverers": ["Discoverer Name"]
}
```

### Modifying Categories
Update the `questionTypes` object to add new question categories and keyword mappings.

---

## 📊 Project Structure
```
qlang/
├── index.html          # Main application file
├── README.md           # This file
├── LICENSE             # MIT License
└── assets/             # (Optional) Additional assets
    ├── images/
    └── css/
```

---

## 🌐 Browser Compatibility

- Chrome 60+ (Desktop & Android)  
- Firefox 55+  
- Safari 12+ (macOS & iOS)  
- Edge 79+  
- Samsung Internet 12+  

---

## 🤝 Contributing

We welcome contributions to expand the library of universal laws! Please ensure:

- Laws are well-established scientific principles  
- Include proper mathematical formulations where applicable  
- Provide accurate historical context and discoverers  
- Maintain consistent data structure  

---

## 📜 License

[MIT License](LICENSE) — feel free to use this project for educational and research purposes.

---

## 🎯 Future Enhancements

### Near-term (v1.1–v2.0):
- Law relationships and dependencies  
- Export functionality (PDF, JSON)  
- Historical timeline visualization  

### Long-term:
- Interactive law comparisons  
- User accounts and saved queries  
- RESTful API for programmatic access  
- Multilingual support (i18n)  

---

## 📚 References & Further Reading

- [Stanford Encyclopedia of Philosophy](https://plato.stanford.edu/)  
- [Physics Today](https://physicstoday.scitation.org/)  
- [Nature Physics](https://www.nature.com/nphys/)  
- [Scientific American](https://www.scientificamerican.com/)  

---

## 👨‍💻 Author

Ouadi Maakoul  
- GitHub: [@ouadimaakoul4](https://github.com/ouadimaakoul4)

---

## 🙏 Acknowledgments

- The scientific community for centuries of discovery  
- MathJax team for beautiful mathematical rendering  
- All contributors to human knowledge  

---

<div align="center">

> “The most beautiful thing we can experience is the mysterious. It is the source of all true art and science.”  
> — Albert Einstein

</div>