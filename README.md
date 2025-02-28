# Hexo-plugin-tabs

## Introduction
**Version: 0.01 DEV**

This is a plugin for building styled tabs in hexo.

**Example**:

Not uploaded

**Dependencies: Node.js>=0.10.0, hexo, windows (Available for only windows)**

## How to use
- **Installation**

Simply run "npm install hexo-plugin-tabs" or download the source code and unzip it to "yourwebpage/node_modules/"

```bash
npm install hexo-plugin-tabs
```
**or**
```bash
git clone https://github.com/sclass53/hexo-plugin-tabs.git node_modules/hexo-plugin-tabs
```

Then add one line "hexo-plugin-tabs>=0.0.1 "in the "dependencies" of "package.json" of your webpage folder, 

```json
"dependencies":{
  "example>=x.x.x",
  //etc.
  "hexo-plugin-tabs>=0.0.1"
}
```

- **Syntax**

Example:

```markdown
!!! tabs
++++First tab
First tab section
++++Second tab
Second tab section
++++
```

Simply type **!!! tabs** at the section you want to insert tabs, and add "++++tab title 1" to add a tab
Insert tab text between tab markings (aka. ++++).
To end, mark "++++"

It will automatically be converted into html
```html
<iframe src="\httabs\ok.html"></iframe>
```
**Result**:

![Result-image]()

A postname.html will be created under the /source/httabs/ dir (httabs is created after first generating process). Check /bin/source.html for more imformation.

run
```
hexo g
hexo s
```
to test

## License

CC-BY-SA 4.0

## Contributors

@ginoblog, @melvinzhang (not a user)
