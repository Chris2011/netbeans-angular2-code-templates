# Angular 2 TypeScript Snippets for NetBeans
This extension for NetBeans adds snippets for Angular 2 for TypeScript and HTML.

It is based on the Visual Studio Code implementation: https://github.com/johnpapa/vscode-angular2-snippets

![Use Extension](images/NbAngular2TSSnippets.gif)

## Usage
Type part of a snippet, press `enter` or `tab`, and the snippet unfolds.

### TypeScript Snippets
```typescript
ng2-component-root  // Angular 2 root App component
ng2-bootstrap       // Angular 2 bootstraping, for main.ts
ng2-component       // Angular 2 component
ng2-pipe            // Angular 2 pipe
ng2-route-config    // Angular 2 @RouteConfig
ng2-route-path      // Angular 2 routing path
ng2-service         // Angular 2 service
ng2-subscribe       // Angular 2 observable subscription
```

###HTML Snippets
```html
ng2-ngClass     <!-- Angular 2 ngClass snippet -->
ng2-ngFor       <!-- Angular 2 *ngFor snippet -->
ng2-ngIf        <!-- Angular 2 *ngIf snippet -->
ng2-ngModel     <!-- Angular 2 ngModel snippet -->
ng2-routerLink  <!-- Angular 2 routerLink snippet -->
ng2-ngStyle     <!-- Angular 2 ngStyle snippet -->
ng2-ngSwitch    <!-- Angular 2 ngSwitch snippet -->
```


Not supported yet, created a ticket to bring code templates to the code completion for TypeScript and HTML
---Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.---

##How to install

You can't import directly the file into Netbeans. Indeed, you have to export FIRST your Custome Code Templates. Once it's done, go into the zip file et paste the content of thus XML file into your XML files. If you don't do like this, you will loose every Code Templates created before it.

##Steps:
  1) In Netbeans, go to Tools->Options->Editor->Code Templates->Export. In the window, enter the path for the configuration ZIP file and go to "Editor" and check "Code Templates". 
  
  2) Extract the ZIP file and then you have to navigate to "...\config\Editors\text\typescript\CodeTemplates\" and "...\config\Editors\text\html\CodeTemplates\"
  
  3) Open the XML file called "org-netbeans-modules-editor-settings-CustomCodeTemplates.xml" with a text editor and paste the content of the XML file that you have downloaded here BETWEEN the tags <codetemplates> and </codetemplates>.
  
  4) Close your text editor and now you have to zip the folder "config" (and the others files into root of config folder)
  
  5) Go back in Netbeans and now into Tools->Options->Editor->Code Templates, click on Import to import the new Code Templates.
  
  6) Test it into a TypeScript or HTML file (Examples: typescript shortcut "ng2-pipe" + TAB => import { Pipe, PipeTransform..., html shortcut "ng2-ngSwitch" + TAB => <div [ngSwitch]=...", ...)
  
  !!!Be Carefull!!!
  If you don't export all your code templates in the first step, when you will import the new code templates, all your previous code templates will be erase.

##Known Bugs
HTML and TypeScript code completion doesn't include the code templates, but the code templates are working well. I created bugs for this.