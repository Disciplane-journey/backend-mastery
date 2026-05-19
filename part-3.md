## Part 03 — fs Module (File System)


- `fs` module handles files in Node.js
- `fs.writeFileSync()` → synchronous write (blocks code)
- `fs.writeFile()` → asynchronous write (better)
- `fs.readFile()` → read file content
- `fs.appendFile()` → add content to existing file

### Key Code
```js
const fs = require("fs")

fs.writeFile("file.txt", "content", () => {
    fs.readFile("file.txt", (error, data) => {
        console.log(data.toString())
    })
})

fs.appendFile("file.txt", "more content", (e) => {
    console.log(e)
})
```
