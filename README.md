
## CSS FLEX

css flex properties has two kinds of properties
 1. parent properties
 2. child properties
### Parent Properties

 `use display:flex; for parent properties first`
 ### flex-wrap
 ``By default, flex items will all try to fit onto one line. but we can change that and allow the items to wrap as needed with flex-wrap property``

 `.container {
     flex-wrap: nowrap | wrap | wrap-reverse;
    }
 `
 ### flex-flow 
 `flex-flow: shorhand of flex-direction and flex-wrap`
 `
    .container {
        flex-flow: row wrap;
    }
 `