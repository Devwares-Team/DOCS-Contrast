---
title: 'Autocomplete'
metaTitle: 'Bootstrap 5 Autocomplete - Bootstrap CSS tutorial '
metaDescription: 'Bootstrap 5 Autocomplete makes it easy to write anything, it simply anticipates the words you want to write based on the first few letters written by a user. '
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/autocomplete.md"
---

# Bootstrap Autocomplete

Bootstrap 5 Autocomplete is a powerful tool designed to help developers quickly and easily create dynamic, data-driven web pages. The Autocomplete feature allows users to quickly filter through large data sets and find the information they need.

It accepts a list of suggestions in the form of an `Array`.
The `↑` and `↓` arrow keys can be used to traverse through options, and the `↵` key can be used to choose the required option.

The bootstrap autocomplete also provides a variety of customization options for developers to ensure that the user experience is tailored to the specific needs of their website or application.

The bootstrap autocomplete feature is composed of three main components: an input field, a list of suggestions, and a selection field. The input field is an HTML input field that accepts user input. When a user types in the field, the Autocomplete feature will automatically generate a list of suggestions based on the input. The user then selects the desired item from the list, and the Autocomplete feature will populate the selection field with the selected item.

## Default Autocomplete

<Autocomplete1/>

###### JavaScript

```js
    <script defer type="module">
      var demo1 = new CDBAutocomplete({
        selector: '#cdb-autocomplete',
        minChars: 1,
        source: function (term, suggest) {
          term = term.toLowerCase();
          var choices = [
            'ActionScript',
            'AppleScript',
            'Asp',
            'Assembly',
            'BASIC',
            'Batch',
            'C',
            'C++',
            'CSS',
            'Clojure',
            'COBOL',
            'ColdFusion',
            'Erlang',
            'Fortran',
            'Groovy',
            'Haskell',
            'HTML',
            'Java',
            'JavaScript',
            'Lisp',
            'Perl',
            'PHP',
            'PowerShell',
            'Python',
            'Ruby',
            'Scala',
            'Scheme',
            'SQL',
            'TeX',
            'XML',
          ];
          var suggestions = [];
          for (var i = 0; i < choices.length; i++)
            if (~choices[i].toLowerCase().indexOf(term))
              suggestions.push(choices[i]);
          suggest(suggestions);
        },
      });
    </script>
```

###### HTML

```html
<div class="cdb-form" style="width: 100%">
  <input type="text" class="form-control" id="cdb-autocomplete" name="q" />
  <label>Email</label>
</div>
```
