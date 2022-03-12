---
title: 'Autocomplete'
metaTitle: 'Bootstrap 5 Animations - Bootstrap CSS tutorial '
metaDescription: 'Bootstrap 5 Autocomplete makes it easy to write anything, it simply anticipates the words you want to write based on the first few letters written by a user. '
---

# Bootstrap Autocomplete

Bootstrap 5 Autocomplete anticipates words based on the first few letters typed by the user. It accepts a list of suggestions in the form of a `Array`.
The `↑` and `↓` arrow keys can be used to traverse through options, and the `↵` key can be used to choose the required option.

## Default Autocomplete

![Bootstrap Autocomplete](./images/autocomplete1.png)

######Script

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

######HTML

```html
<div class="cdb-form" style="width: 100%">
  <input type="text" class="form-control" id="cdb-autocomplete" name="q" />
  <label>Email</label>
</div>
```
