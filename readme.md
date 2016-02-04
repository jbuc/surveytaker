#what if forms or surveys could be built rapidly?

what if you could use a human readable shorthand to build user forms in plain text?

## What if...

- a text input was made like this? :: 
    - with a label was made like this? [label]::
    - with default text was made like this? [label] :: ("default text")
    - with a label default text and a character limit was made like this? 
        - [label] :: ("default text" 20)
    - with a custom validator was made like this? :: (/text/)
    - or this? ::(/email/)
    - or this, regex eh? ::(/*^[\d]+?$*/)
    - range inputs was made like this ::(10-200)
    - date inputs was made like this ::(mm/dd/yyyy)
    - date range inputs was made like this ::(02/12/2014-mm/dd/yyyy)

- different imputs was made like this? 
    - number keyboards ::(#)
    - email keyboards ::(@)
    - url keyboards ::(www)
    - password masking ::(*)

- selects were made like this ::(-)
    : option 1 [value]
    : option 2 [value]
    :: option 3 default [value]

- radio groups were made like this? ::(o)
    : option 1 [value]
    : option 2 [value]
    :: option 3 default [value]

- checkbox groups was made like this? ::([])
    : option 1 [value]
    : option 2 [value]
    :: option 3 default [value]

- buttons were made like this {Send your form!}("post/url.html")
- or like this? {Send your form!}{id}