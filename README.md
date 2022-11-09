<!-- HEADINGS -->

# My tittle
## My title h2
### My tittle h3
#### My tittle h4
##### My tittle h5
###### My tittle h6


<!-- Line breaks -->
<!-- ENTER -->


<!-- Italic -->
this is an *italic* text

<!-- Strong -->
this is an **strong** text

<!-- Strikethrough -->
este es un texto ~~tachado~~


<!-- UL -->
* item 1
* item 2
* item 3
    * item 3.1
    * item 3.2    
* item 4

<!-- OL -->
1. item 1
1. item 2
1. item 3
1. item 4


<!-- Links -->
[google.com](http://www.google.com)

[google.com](http://www.google.com "Custom tittle")


<!-- Blockquote -->
> This is a quote


<!-- Horizontal Rule -->
---
___


<!-- Inline code -->
`console.log('Hello, world!')`

```javascript
import { connect } from "mongoose";
import { MONGODB_URI } from "../config";

// connection to db
(async () => {
  try {
    const db = await connect(MONGODB_URI);
    console.log("Db connectect to", db.connection.name);
  } catch (error) {
    console.error(error);
  }
})();
```

```python
print("Hello, world!")
```

```html
<h1>Hello, world!</h1>
```

<!-- Tables -->
| Product       | Price         |quantity   |
| ------------- |:-------------:| :--------:|
| Laptop        | 3.33          | 2         |
| Mouse         | 10.33         | 1         |

<!-- IMAGES -->
![Vscode Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/1200px-Visual_Studio_Code_1.35_icon.svg.png)

![Vscode Logo](vscode.png "Vscode Logo")

<!-- GITHUB MARKDOWN -->
* [X] Task 1
* [] Task 2
* [] Task 3
* [x] Tast 4


