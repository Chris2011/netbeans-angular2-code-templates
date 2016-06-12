<h1>Angular 2 TypeScript Snippets for NetBeans</h1>
This extension for NetBeans adds snippets for Angular 2 for TypeScript and HTML.

It is based on the Visual Studio Code implementation: <a href="https://github.com/johnpapa/vscode-angular2-snippets">https://github.com/johnpapa/vscode-angular2-snippets</a>

<h3>TypeScript</h3>
<img src="images/NbAngular2TSSnippets.gif" alt="Use Extension" />

<h3>HTML</h3>
<img src="images/NbAngular2HTMLSnippets.gif" alt="Use Extension" />

<h2>Usage</h2>
Type part of a snippet, press <strong>enter</strong> or <strong>tab</strong>, and the snippet unfolds.

<h3>TypeScript Snippets</h3>
<ol>
    <li><strong>ng2-component-root</strong> - Angular 2 root App component</li>
    <li><strong>ng2-bootstrap</strong> - Angular 2 bootstraping, for main.ts</li>
    <li><strong>ng2-component</strong> - Angular 2 component</li>
    <li><strong>ng2-pipe</strong> - Angular 2 pipe</li>
    <li><strong>ng2-route-config</strong> - Angular 2 @RouteConfig</li>
    <li><strong>ng2-route-path</strong> - Angular 2 routing path</li>
    <li><strong>ng2-service</strong> - Angular 2 service</li>
    <li><strong>ng2-subscribe</strong> - Angular 2 observable subscription</li>
</ol>

<h3>HTML Snippets</h3>
<ul>
    <li><strong>ng2-ngClass</strong> - Angular 2 ngClass snippet</li>
    <li><strong>ng2-ngFor</strong> - Angular 2 *ngFor snippet</li>
    <li><strong>ng2-ngIf</strong> - Angular 2 *ngIf snippet</li>
    <li><strong>ng2-ngModel</strong> - Angular 2 ngModel snippet</li>
    <li><strong>ng2-routerLink</strong> - Angular 2 routerLink snippet</li>
    <li><strong>ng2-ngStyle</strong> - Angular 2 ngStyle snippet</li>
    <li><strong>ng2-ngSwitch</strong> - Angular 2 ngSwitch snippet</li>
</ul>


<h2>How to install</h2>
<p>Install the plugin.</p>
<p>Test it into a TypeScript or HTML file (Examples: typescript shortcut <strong>ng2-pipe</strong> + TAB => import { Pipe, PipeTransform..., html shortcut <strong>ng2-ngSwitch</strong> + TAB => &lt;div [ngSwitch]=...", ...)</p>
  
<h2>Known Bugs</h2>
HTML and TypeScript code completion doesn't include the code templates, but the code templates are working well. I created tickets for this.