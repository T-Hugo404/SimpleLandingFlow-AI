## 🇧🇷 **Descrição (Português)**

Este projeto foi criado para gerar Landing Pages automaticamente usando inteligência artificial.
Ele funciona através de um conjunto de arquivos de configuração que definem como a IA deve montar o layout, o estilo, o conteúdo e a identidade visual. O objetivo é permitir que qualquer página seja criada seguindo um padrão claro, organizado e reutilizável.
O processo completo é controlado pelas instruções da pasta `ia-instructions` e por regras adicionais configuradas diretamente no ambiente da IA.

---

## 🇺🇸 **Description (English)**

This project was created to automatically generate Landing Pages using artificial intelligence.
It works through a set of instruction files that define how the AI must build the layout, style, content, and visual identity. The goal is to create a clean, structured, and easily reusable system for generating pages for different projects.

All logic is controlled by the instruction files inside `ia-instructions` and by an additional set of “rules” that guide how the AI should behave during execution.

---

# **📁 Project Structure**

```
/
├── ia-instructions
│   ├── instructions.md      → Defines how the AI must behave
│   ├── main-style.md        → Defines style, branding, identity and visual rules
│   └── content.md           → Defines page structure and section-by-section content
├── index.html
├── pages/                   → Additional HTML pages
└── src/
    ├── css/
    ├── js/
    └── img/
```

---

# **🎯 Purpose of Each File**

### **1. instructions.md**

Defines behavior rules for the AI:
– how to read files
– how to assemble pages
– how to follow the hierarchy
– how to generate clean, consistent code

This is the highest-priority file.

### **2. main-style.md**

Defines the entire visual identity:
– colors, typography, spacing
– branding and tone of voice
– layout styles
– naming conventions for sections and files
– rules for responsiveness
– rules for custom CSS/JS per section

The AI must apply these rules to *every* generated page.

### **3. content.md**

Defines what each page contains:
– which sections exist
– required classes
– layout description
– text
– images
– responsive behavior
– special interactions

This file guides the construction of each specific page.

---

# **🧠 AI Behavior Rules (Rules System)**

These rules are added inside the AI environment (not inside the project) and ensure the AI executes everything correctly.

### **Why the Rules Are Important**

They force the AI to:
– read files in the correct order
– avoid improvisation
– maintain consistency
– follow all instructions strictly
– generate stable, predictable output

With them, the project becomes reusable and behaves the same way for every new landing page.

---

## **Simplified Rule Set (English)**

```
USER GUIDELINES (AI)

0. Language
- Always answer in short, direct PT-BR (except technical terms).

1. Reading Order
1. instructions.md
2. main-style.md
3. content.md
Only start execution after fully interpreting all three.

2. File Purposes
- instructions.md: behavior and rules
- main-style.md: visual and writing identity
- content.md: structure and page content

3. General Rules
1. Follow all instructions strictly
2. Do not invent content or style not allowed
3. If anything is unclear: ask
4. Code must be clean, organized and consistent
5. Hierarchy always:
   instructions → main-style → content

4. Expected Result
- Complete pages
- Accurate content
- Correct visual identity
- Ready-to-use code
- No rule-breaking or improvisation
```

---

# **🚀 How to Use the Project**

1. Clone the project
2. Edit the three configuration files inside `ia-instructions`
3. Provide these files to the AI in the correct order
4. Ensure the rules are active in the AI environment
5. Ask the AI to generate or update the landing page
6. Copy the generated HTML/CSS/JS into the project folders

---

# **🛠 Recommended Workflow**

1. Adjust or clone `main-style.md` for each new client/project
2. Write the sections for each page inside `content.md`
3. Use the rules system to ensure consistent execution
4. Review the generated code and test responsiveness
5. Deploy or integrate with any backend if needed

---

# **📌 Notes**

Feel free to modify the rules, expand the configuration files, or adapt the project structure to better fit your workflow. The system was designed to evolve as needed.

### Notes About Language

All instruction files inside the `ia-instructions` folder are written in Brazilian Portuguese (pt-BR).
If you prefer to use the project in another language, simply translate the instruction files before starting a new landing page generation. The system will work normally as long as the structure and rules are preserved.
