# JavaScript First Code

A small collection of beginner-friendly JavaScript exercises paired with HTML pages. The examples practice core syntax and show how scripts can respond to page loads and update content in the browser.

## Why use this project?

- Explore variables, functions, conditionals, loops, arrays, and array methods in [`Syntax/`](Syntax/).
- See JavaScript update page content in the root example and [`customjs/`](customjs/).
- View an array of book titles rendered in the page in [`Library/`](Library/).
- Run everything in a browser without installing project dependencies or building the code.

## Get started

### Requirements

A modern web browser is all you need. This repository has no package manager dependencies or build step.

### Run the examples

Clone the repository and start a local web server from its root:

```sh
git clone https://github.com/VoidLance/course-files-javascript-firstcode.git
cd course-files-javascript-firstcode
python3 -m http.server 8000
```

Open <http://localhost:8000> in your browser. You can also navigate directly to each example:

| Example | Page | What it demonstrates |
| --- | --- | --- |
| Main page | [`index.html`](index.html) | A button updates a heading; JavaScript also logs a greeting to the console. |
| Syntax exercises | [`Syntax/index.html`](Syntax/index.html) | Variables, functions, conditionals, loops, arrays, and console output. |
| Library | [`Library/index.html`](Library/index.html) | Displays a list of book titles from an array. |
| Custom JavaScript | [`customjs/index.html`](customjs/index.html) | A welcome alert and a button that changes page text. |

Click the page's button to see its content change. Open your browser's developer console to inspect messages produced by the examples.

For example, the main page's script updates an element by its ID:

```js
function replace() {
  const heading = document.getElementById("demo");
  heading.textContent = "New Text!";
}
```

## Get help

- For questions or to report a problem, [open a GitHub issue](https://github.com/VoidLance/course-files-javascript-firstcode/issues).
- For JavaScript and browser API references, see [MDN's JavaScript Guide](https://developer.mozilla.org/docs/Web/JavaScript/Guide) and [DOM documentation](https://developer.mozilla.org/docs/Web/API/Document_Object_Model).

## Maintainers and contributing

The repository is maintained by its GitHub owner and contributors. Contributions are welcome: open an issue to discuss a change, or submit a pull request with a focused improvement and a description of how you checked it in a browser. There is no separate contribution guide in the repository.
