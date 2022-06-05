# Toggle-Button-CSS
This project includes converting `checkboxes` to stylized switch and select type `buttons`. The process is as follows:  
1. The checkbox is hidden.
2. The `::before` pseudo element is used to create the Indicator
3. The `:checked` criteria is used to style for the `ON` condition, `OFF` is default.
4. The `+`(sibling element selector is used to syle the `button` when the `checkbox` is checked)
