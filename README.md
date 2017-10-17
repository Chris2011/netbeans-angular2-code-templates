<h1>Angular TypeScript Snippets for NetBeans</h1>
<h3>Now Updated for Angular 4.3.0 release</h3>

This extension for NetBeans adds snippets for Angular for TypeScript and HTML.

It is based on the Visual Studio Code implementation: <a href="https://github.com/johnpapa/vscode-angular2-snippets">https://github.com/johnpapa/vscode-angular2-snippets</a>

<h3>TypeScript</h3>
<img src="images/NbAngular2TSSnippets.gif" alt="Use Extension" />

<h3>HTML</h3>
<img src="images/NbAngular2HTMLSnippets.gif" alt="Use Extension" />

<h2>Usage</h2>
Type part of a snippet, press <strong>enter</strong> or <strong>tab</strong>, and the snippet unfolds.

<h3>TypeScript Angular Snippets</h3>
<ol>
    <li><strong>a-component-root</strong> - root App component</li>
    <li><strong>a-bootstrap</strong> - bootstraping, for main.ts</li>
    <li><strong>a-component</strong> - component</li>
    <li><strong>a-pipe</strong> - pipe</li>
    <li><strong>a-route-config</strong> - @RouteConfig</li>
    <li><strong>a-route-path</strong> - routing path</li>
    <li><strong>a-service</strong> - service</li>
    <li><strong>a-subscribe</strong> - observable subscription</li>
</ol>

<h3>TypeScript RxJS Snippets</h3>
<ul></ul>

<h3>HTML Snippets</h3>
<ul>
    <li><strong>a-class</strong> - [class] binding</li>
    <li><strong>a-select</strong> - &lt;select&gt; control</li>
    <li><strong>a-style</strong> - [style] binding</li>
    <li><strong>a-ngClass</strong> - ngClass</li>
    <li><strong>a-ngFor</strong> - *ngFor</li>
    <li><strong>a-ngForAsync</strong> - *ngFor with async</li>
    <li><strong>a-ngFor-trackBy</strong> - *ngFor with trackBy</li>
    <li><strong>a-ngIf</strong> - *ngIf</li>
    <li><strong>a-ngIfElse</strong> - *ngIf with else</li>
    <li><strong>a-ngModel</strong> - ngModel</li>
    <li><strong>a-routerLink</strong> - routerLink</li>
    <li><strong>a-routerLink-param</strong> - routerLink with a route parameter</li>
    <li><strong>a-ngStyle</strong> - ngStyle</li>
    <li><strong>a-ngSwitch</strong> - ngSwitch</li>
    <li><strong>a-prej</strong> - show the JSON form of a model</li>
    <li><strong>a-preja</strong> - show the JSON form of a model, using async</li>
</ul>


<h2>How to install</h2>
<p>Install the plugin.</p>
<p>Test it into a TypeScript or HTML file (Examples: typescript shortcut <strong>a-pipe</strong> + TAB => import { Pipe, PipeTransform..., html shortcut <strong>a-ngSwitch</strong> + TAB => &lt;div [ngSwitch]=...", ...)</p>
  
<h2>Known Bugs</h2>
HTML code completion doesn't include the code templates, but the code templates are working well. A Ticket was created: https://netbeans.org/bugzilla/show_bug.cgi?id=250321
