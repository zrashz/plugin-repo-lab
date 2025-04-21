# Plugin Repository Lab

Welcome to the Plugin-Based App! 🎉

In this exercise, you will:
- Build your own plugin
- Register it in the system
- Resolve merge conflicts
- Analyze dependency trees

## 🔧 How to Run

1. Clone the repo:
```bash
git clone https://github.com/your-org/plugin-repo-lab.git
cd plugin-repo-lab
npm install
node app.js
```

2. Create your plugin inside `/plugins/your-name-plugin/`.

3. Register it in `plugins.json`.

4. Test it using `node app.js`.

---

## 🧩 Plugin Specification

- Each plugin is a JS module exporting a function:
```js
module.exports.run = () => {
  return "Hello from your plugin!";
};
```

- Add your plugin path and name to `plugins.json` like so:
```json
[
  {
    "name": "Your Name Plugin",
    "entry": "./plugins/your-name-plugin/plugin.js"
  }
]
```

---

## 🗂 Example Plugin

See `plugins/sample-plugin/plugin.js` for reference.

---

## 🧪 Tasks

- [ ] Create a plugin
- [ ] Register in plugins.json
- [ ] Pull changes and resolve merge conflicts
- [ ] Run `npm ls` and analyze dependencies
