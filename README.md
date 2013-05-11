# Sublime Text 2 Snippets

A collection of my [Sublime Text 2](http://www.sublimetext.com/) snippets to simplify the development workflow.

## Installation

These snippets can be installed by simply checkout the source code into Sublime Text's packages directory. The location is system specific:

### For OSX

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User
    $ git clone https://github.com/andreruffert/subl-snippets.git -b master

### For Windows

    $ cd %APPDATA%/Sublime Text 2/Packages/User
    $ git clone https://github.com/andreruffert/subl-snippets.git -b master

## Snippets and Bindings

### Comments
<table>
    <tr>
        <th>Tab trigger</th>
        <th>Description</th>
        <th></th>
    </tr>
    <tr>
        <td>c-gb</td>
        <td>
            Group comment block<br>
            For multi-line explanations and documentation
        </td>
        <td>
            /**
             * comment
             */
        </td>
    </tr>
    <tr>
        <td>c-hb</td>
        <td>Header comment block</td>
    </tr>
    <tr>
        <td>c-sb</td>
        <td>Section comment block</td>
    </tr>
    <tr>
        <td>c-s</td>
        <td>Seperator comment</td>
    </tr>
    <tr>
        <td>c-ssb</td>
        <td>Sub-section comment block</td>
    </tr>
</table>

### HTML
<table>
    <tr>
        <th>Tab trigger</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>html5</td>
        <td>Create blank HTML5 document</td>
    </tr>
    <tr>
        <td>h5bp</td>
        <td>Create blank h5bp document</td>
    </tr>
</table>

### JavaScript
<table>
    <tr>
        <th>Tab trigger</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>log</td>
        <td>console.log()</td>
    </tr>
</table>

### jQuery
<table>
    <tr>
        <th>Tab trigger</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>jq-ready</td>
        <td>$(document).ready(); shorthand method</td>
    </tr>
    <tr>
        <td>jq-plugin</td>
        <td>jQuery prototypal inheritance plugin boilerplate</td>
    </tr>
</table>

### Misc
<table>
    <tr>
        <th>Tab trigger</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>editorconfig</td>
        <td>editorconfig boilerplate</td>
    </tr>
    <tr>
        <td>packagejson</td>
        <td>package.json boilerplate</td>
    </tr>
</table>
