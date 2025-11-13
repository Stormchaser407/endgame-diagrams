# ENDGAME DIAGRAMS - QUICK START GUIDE

**Get up and running with the Endgame Diagram Set in 5 minutes.**

---

## 🚀 FASTEST PATH TO VIEWING

### Option 1: Mermaid Live Editor (Recommended)
1. Go to **https://mermaid.live**
2. Open any `.mmd` file from this repository
3. Copy the entire contents
4. Paste into the Mermaid Live Editor
5. Diagram renders instantly
6. Export as PNG/SVG if needed

### Option 2: VS Code
1. Install **Mermaid Preview** extension
2. Open any `.mmd` file
3. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
4. Type "Mermaid: Preview"
5. Diagram renders in preview pane

### Option 3: GitHub
1. Create a markdown file (`.md`)
2. Add a mermaid code block:
   ````markdown
   ```mermaid
   [paste diagram code here]
   ```
   ````
3. GitHub automatically renders it

---

## 📂 WHICH DIAGRAM DO I NEED?

### Starting Point
- **New to Endgame?** → Start with `01_endgame_system_overview.mmd`
- **Want the full map?** → Check `00_endgame_master_index.mmd`

### By Use Case
- **Understanding Cerberus mythology** → `02_cerberus_lore_map.mmd`
- **Technical architecture** → `04_cerberus_architecture_map.mmd`
- **Hardware setup** → `05_endgame_device_constellation.mmd`
- **Operational workflow** → `06_endgame_operational_stack.mmd` or `07_intelligence_workflow_pipeline.mmd`
- **Content/writing systems** → `08_endgame_creative_ecosystem.mmd`
- **Learning tools** → `10_endgame_learning_stack.mmd`
- **Business structure** → `09_endgame_business_infrastructure.mmd`
- **Knowledge domains** → `03_endgame_knowledge_pillars.mmd`

---

## 🎨 CUSTOMIZING DIAGRAMS

### Basic Edits
1. Open the `.mmd` file in any text editor
2. Find the node you want to change
3. Edit the text between quotes or brackets
4. Save and re-render

### Example: Changing a Node Label
```mermaid
Before: REC["Recon - The Eye<br/>Sees Patterns Others Miss"]:::head
After:  REC["Recon - The Eye<br/>Your Custom Text Here"]:::head
```

### Adding New Nodes
```mermaid
PARENT --> NEWNODE["New Node Name"]:::node;
```

### Maintaining Style
Always use one of these class definitions:
- `:::core` - For main/central nodes
- `:::head` - For major subsystem nodes
- `:::node` - For detail/leaf nodes

---

## 💾 EXPORTING DIAGRAMS

### As PNG (High Quality)
1. Open in Mermaid Live Editor
2. Click "Actions" → "PNG"
3. Download image

### As SVG (Scalable)
1. Open in Mermaid Live Editor
2. Click "Actions" → "SVG"
3. Download vector file

### Using CLI (Advanced)
```bash
npm install -g @mermaid-js/mermaid-cli
mmdc -i diagram.mmd -o diagram.png
```

---

## 🔧 TROUBLESHOOTING

### Diagram Won't Render
- Check for syntax errors (missing semicolons, brackets)
- Verify class definitions are at the bottom
- Ensure all node references are defined

### Colors Look Wrong
- Confirm `classDef` statements are present
- Check that nodes have `:::core`, `:::head`, or `:::node` applied
- Verify hex codes match brand standards

### Text Overlapping
- Add `<br/>` for line breaks in long labels
- Shorten text if necessary
- Adjust graph direction (`TD` vs `LR`)

---

## 📚 LEARNING MERMAID

### Essential Syntax
```mermaid
graph TD;              %% Top-Down graph
A[Node A]:::class;     %% Node with class
A --> B[Node B];       %% Arrow connection
A --> C[Node C];       %% Multiple connections
```

### Resources
- **Official Docs:** https://mermaid.js.org/
- **Live Editor:** https://mermaid.live
- **Syntax Guide:** https://mermaid.js.org/syntax/flowchart.html

---

## 🎯 NEXT STEPS

1. **View all diagrams** - Start with the master index
2. **Understand the system** - Read through each diagram category
3. **Customize if needed** - Edit diagrams for your specific use case
4. **Export for presentations** - Generate PNG/SVG files
5. **Keep updated** - Check CHANGELOG.md for new versions

---

## 💡 PRO TIPS

- Use the master index as a navigation hub
- Keep original files as backups before editing
- Export diagrams at high resolution for presentations
- Use SVG format for scalable graphics
- Combine multiple diagrams in presentations for full context

---

**Questions?** Refer to the main README.md for detailed documentation.

**"Intelligence. Action. Endgame."**