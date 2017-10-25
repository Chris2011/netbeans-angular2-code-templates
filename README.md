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
    <li><strong>aComponent</strong> - component</li>
    <li><strong>aComponent-inline</strong> - component with inline template</li>
    <li><strong>aComponent-root</strong> - root app component</li>
    <li><strong>aDirective</strong> - directive</li>
    <li><strong>aGuardCanActive</strong> - <code>CanActivate</code> guard</li>
    <li><strong>aPipe</strong> - pipe</li>
    <li><strong>aResolver</strong> - resolver</li>
    <li><strong>aRoute-config</strong> - @RouteConfig</li>
    <li><strong>aRoute-path</strong> - routing path</li>
    <li><strong>aService</strong> - service</li>
    <li><strong>aSubscribe</strong> - observable subscription</li>
</ol>

<h3>TypeScript RxJS Snippets</h3>
<ul>
    <li><strong>rxObservable</strong> - Rx <strong>Observale</strong> import</li>
    <li><strong>rxSubject</strong> - Rx <strong>Subject</strong> import</li>
    <li><strong>rxReplaySubject</strong> - Rx <strong>ReplaySubject</strong> import</li>
    <li><strong>rxBehaviorSubject</strong> - Rx <strong>BehaviorSubject</strong> import</li>
    <li><strong>rxAddOperator</strong> - Rx add operator import</li>
    <li><strong>rxAddObservable</strong> - Rx add observale import</li>
</ul>

<h3>HTML Snippets</h3>
<ul>
    <li><strong>aClass</strong> - [class] binding</li>
    <li><strong>aNgClass</strong> - ngClass</li>
    <li><strong>aNgContainer</strong> - &lt;ng-container&gt; element</li>
    <li><strong>aNgContent</strong> - &lt;ng-content&gt; element</li>
    <li><strong>aNgFor</strong> - *ngFor</li>
    <li><strong>aNgForAsync</strong> - *ngFor with async</li>
    <li><strong>aNgForTrackBy</strong> - *ngFor with trackBy</li>
    <li><strong>aNgIf</strong> - *ngIf</li>
    <li><strong>aNgIfElse</strong> - *ngIf with else</li>
    <li><strong>aNgModel</strong> - ngModel</li>
    <li><strong>aNgStyle</strong> - ngStyle</li>
    <li><strong>aNgSwitch</strong> - ngSwitch</li>
    <li><strong>aNgTemplate</strong> - &lt;ng-template&gt; element</li>
    <li><strong>aPrej</strong> - show the JSON form of a model</li>
    <li><strong>aPreja</strong> - show the JSON form of a model, using async</li>
    <li><strong>aRouterLink</strong> - routerLink</li>
    <li><strong>aRouterLinkParam</strong> - routerLink with a route parameter</li>
    <li><strong>aSelect</strong> - &lt;select&gt; control</li>
    <li><strong>aStyle</strong> - [style] binding</li>
</ul>


<h2>How to install</h2>
<p>Install the plugin.</p>
<p>Test it into a TypeScript or HTML file (Examples: typescript shortcut <strong>a-pipe</strong> + TAB => import { Pipe, PipeTransform..., html shortcut <strong>a-ngSwitch</strong> + TAB => &lt;div [ngSwitch]=...", ...)</p>
  
<h2>Known Bugs</h2>
HTML code completion doesn't include the code templates, but the code templates are working well. A Ticket was created: https://netbeans.org/bugzilla/show_bug.cgi?id=250321
