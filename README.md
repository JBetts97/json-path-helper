# JSON Path Helper

JSON Path Helper is a lightweight web app that makes it easier to **navigate, explore, and generate JSONPath expressions** for working with JSON data.  
It’s designed to help developers quickly find and extract values from complex JSON structures.

🌐 **Live demo available at:**  
👉 [https://jbetts97.github.io/json-path-helper/](https://jbetts97.github.io/json-path-helper/)

---


## ✨ Features
- Paste or load JSON data directly into the tool
- Highlight and test JSONPath queries interactively
- See matching results in real time
- Copy expressions for use in your code or pipelines
- **Name your generated JSON object** for easy integration into your codebase
- **Choose your preferred programming language** (JavaScript or Python) for code snippet generation
- **Copy generated code instantly** with a keyboard shortcut (Ctrl+Shift+C)

---


## 🚀 Usage

### Naming and Generating Code

1. **Paste your JSON** into the input area on the left.
2. **Click any node** in the tree to select a value or sub-object.
3. In the right panel, use the **Object name** input to set the variable/object name for the generated code.
4. Use the **Language** dropdown to select JavaScript or Python for the code snippet.
5. The **Generated Code** area will show the code to create the selected object/value in your chosen language.
6. Click the **Copy** button or press **Ctrl+Shift+C** to copy the generated code to your clipboard instantly.

### Example

If you select a node and set Object name to `orderData` and Language to `Python`, you'll get:

```python
orderData = {
	"extension_attributes": {"method": "courier"},
	"items": [
		{"sku": "ABC", "qty": 2},
		{"sku": "XYZ", "qty": 1}
	]
}
```

---

You don’t need to install anything — just open the app in your browser:

👉 [https://jbetts97.github.io/json-path-helper/](https://jbetts97.github.io/json-path-helper/)

If you’d like to run it locally:

```bash
git clone https://github.com/jbetts97/json-path-helper.git
cd json-path-helper
# if it's just static HTML/CSS/JS
open index.html

```

---

## 🤝 Contributing

Contributions are welcome! Here’s how you can help:

1. **Fork** the repository  
2. Create a new **feature branch** (`git checkout -b feature/my-feature`)  
3. Commit your changes (`git commit -m "Add my feature"`)  
4. **Push** to your fork (`git push origin feature/my-feature`)  
5. Open a **Pull Request** with a description of your changes  

Issues, bug reports, and feature requests are also appreciated.  

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
