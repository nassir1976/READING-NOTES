[*HOME*](https://nassir1976.github.io/reading-notes/)

## Readnote-11
 ### EJS -Embedded JavaScript templates
EJS is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things.

many EJS examples that sometimes use <%= when outputting HTML or strings, while other examples (sometimes within the same template) use <%- .
 ### Ejs Tags
    % 'Scriptlet' tag, for control-flow, no output
     <%_ ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it
    <%= Outputs the value into the template (HTML escaped)
    <%- Outputs the unescaped value into the template
    <%# Comment tag, no execution, no output
    <%% Outputs a literal '<%'
    %> Plain ending tag
    -%> Trim-mode ('newline slurp') tag, trims following newline
    _%> ‘Whitespace Slurping’ ending tag, removes all whitespace after it
### What are these Ejs templating engines ?
Do they work as well server side and client side?
The general idea is to be working with the same language client and server side (isomorphic)
They all basically seem to achieve the same thing, with different semantics
The end result is always html...
attribution : https://blog.karmacomputing.co.uk/what-is-ejs-and-why-do-i-need-it/ 

https://ejs.co/ https://ejs.co/