# ClipBoard
📗 A custom clipboard made with ClipBoard.js


👉 Why
Copying text to the clipboard shouldn't be hard. It shouldn't require dozens of steps to configure or hundreds of KBs to load. But most of all, it shouldn't depend on Flash or any bloated framework.

That's why clipboard.js exists.

👨‍💻 Install
You can get it on npm.
npm install clipboard --save

Or if you're not into package management, just download a ZIP file.
👉 ZIP Link https://github.com/zenorocha/clipboard.js/archive/master.zip
OR :
🚩 Third party CDN
👉 <script src="https://cdnjs.cloudflare.com/ajax/libs/clipboard.js/2.0.4/clipboard.min.js"></script>

🤷‍♂️ Setup
First, include the script located on the dist folder or load it from a third-party CDN provider.

<script src="dist/clipboard.min.js"></script>
Now, you need to instantiate it by passing a DOM selector, HTML element, or list of HTML elements.

new ClipboardJS('.btn');
