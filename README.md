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
- **Choose your preferred programming language** (JavaScript, Python, or PHP) for path generation
- **Copy the generated path instantly** with a keyboard shortcut (Ctrl+Shift+C)

---


## 🚀 Usage

### Naming and Generating Path Expressions

1. **Paste your JSON** into the input area on the left.
2. **Click any node** in the tree to select a value or sub-object.
3. In the right panel, use the **Object name** input to set the variable/object name for the generated path.
4. Use the **Language** dropdown to select JavaScript, Python, or PHP for the path expression.
5. Only the relevant path for your selected language will be shown.
6. Click the **Copy** button or press **Ctrl+Shift+C** to copy the generated path to your clipboard instantly.

### Example

If you select a node and set Object name to `order` and Language to `Python`, you'll get:

```python
order["items"][0]["sku"]
```

If you select JavaScript, you'll get:

```js
order.items[0].sku
```

If you select PHP, you'll get:

```php
$order['items'][0]['sku']
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
