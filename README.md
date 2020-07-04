## Salesforce Snippets

A [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=ajinkya-hingne.salesforce-snippets) for Salesforce developers.
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/ajinkya-hingne.salesforce-snippets?color=darkgreen)](https://marketplace.visualstudio.com/items?itemName=ajinkya-hingne.salesforce-snippets)

### Features
This extension will give developers a lot of Salesforce code snippets which can be easily used while writing code in Apex and Aura Components to write code faster.  

##### Available Snippets
[![Apex](https://img.shields.io/badge/Apex-41-red?style=flat-square)](https://github.com/meajinkya/salesforce-snippets/blob/master/docs/apex-snippets.md#apex-snippets-reference) 
[![Aura Markup](https://img.shields.io/badge/Aura_Markup-12-green?style=flat-square)](https://github.com/meajinkya/salesforce-snippets/blob/master/docs/html-snippets.md#aura-component) 
[![Aura JavaScript](https://img.shields.io/badge/Aura_JavaScript-06-blue?style=flat-square)](https://github.com/meajinkya/salesforce-snippets/blob/master/docs/javascript-snippets.md#aura-component-js) 
![LWC](https://img.shields.io/badge/LWC-Coming_Soon-lightgrey?style=flat-square)  
*Tip: Click on above badges to open the list of respective language snippets and their prefixes.*

#### Few commonly used Salesforce snippets
|Snippet Name|Snippet Prefix|Language|
|------------|--------------|--------|
|List|list|Apex
|Map|map|Apex
|Advanced for loop|fora|Apex
|System debug without variable|debug|Apex
|Test method|testmethod|Apex
|Init Handler|aura-init-handler|Aura Markup
|Aura Iteration|aura-iteration|Aura Markup
|Call Apex Action|aura-call-apex-action|Aura JavaScript

But those are not all the snippets! To explore all the other snippets available in the extension, go to the [docs](https://github.com/meajinkya/salesforce-snippets/tree/master/docs) folder.  
The [Available Snippets](#available-snippets) section has direct links to language wise snippet reference.

#### How to use?
- After [installing the extension](#installation) in VS Code, the snippets will start appearing automatically when a file with appropriate language is opened.
- Each snippet has a really short *trigger text/snippet prefix* which you can type in and VS Code IntelliSense will show the available snippets.
- For example: if you are writing an Apex Test class and want to write a new test method:  
  - type `testmethod`  
  - press *`Tab`* or press *`Enter`* when VS Code shows the list of snippets
  ... and a test method with placeholders will be inserted in your class!

  ###### Note: *tabCompletion* option in VS Code must be enabled for this to work with Tab press.

> The snippets will be added continuously as and when we find more use cases. Any feedback and pull requests are welcome.

### Installation

Extension installation is as easy as clicking a button from Extensions window in VS Code. To install,
1. Go to File > Preferences > Extensions *or* press Ctrl + Shift + X
2. Search for *Salesforce Snippets*
3. Click Install

---

If you see any issue(s) or have any enhancement request(s), feel free to [create an issue](https://github.com/meajinkya/salesforce-snippets/issues) on GitHub.
### Happy coding! ❤