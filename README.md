# ClipBoard
📗 A custom clipboard made with ClipBoard.js


👉 Why copying text to the clipboard shouldn't be hard. It shouldn't require dozens of steps to configure or hundreds of KBs to load. But most of all, it shouldn't depend on Flash or any bloated framework.
<br>
That's why clipboard.js exists.
<hr>

👨‍💻 Install
You can get it on npm.
```
npm install clipboard --save

```
<br>

Or if you're not into package management, just download a ZIP file.
👉 [Click here](https://github.com/zenorocha/clipboard.js/archive/master.zip)
<br>
OR :
🚩 Third party CDN
👉 ```
<script src="https://cdnjs.cloudflare.com/ajax/libs/clipboard.js/2.0.4/clipboard.min.js"></script>
```
<br>
🤷‍♂️ Setup
First, include the script located on the dist folder or load it from a third-party CDN provider.

```
<script src="dist/clipboard.min.js"></script>
```
Now, you need to instantiate it by passing a DOM selector, HTML element, or list of HTML elements.

new ```javascript
ClipboardJS('.btn');
```
