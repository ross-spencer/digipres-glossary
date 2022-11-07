# digipres-glossary

Digital preservation glossary demo...

## Template

The template for this glossary is made available by @hilverd at:

* https://github.com/hilverd/glossary-page-template

## Editing locally

With node.js installed:

```bash
   sed -n '/START OF editor.js$/,$p' index.htm | node
```

Using this approach, a user is presented with a user-friendly interface for
adding content - including 'see also' links that include suggestions.
