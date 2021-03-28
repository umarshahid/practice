
# practice

article .begin-examples ~ h2,
article .begin-examples ~ h2 + p {
    width: 100%;
    clear: both;
}


article .begin-examples ~ h3,
article .begin-examples ~ p,
article .begin-examples ~ .highlight {
    width: 50%;
}

article .begin-examples ~ h3,
article .begin-examples ~ p {
    float: left;
    box-sizing: border-box;
    padding-right: 1rem;
    clear: both;
}

article .begin-examples ~ .highlight {
    float: right;
    clear: right;
    margin-bottom: 1rem;
}

.end-examples {
    clear: both;
}

article .end-examples ~ p,
article .end-examples ~ h3,
article .end-examples ~ .highlight {
    width: auto;
    float: none;
    clear: none;
}

article .begin-examples ~ h3,
article .begin-examples ~ p,
article .begin-examples ~ .highlight {
    width: 100%;
    float: none;
    clear: none;
}


<div class="begin-examples"></div>

## Section title

## Section title
This text, along with the title, remains in a single column

### Main you want to make point here

### Main point
Some explanatory text.

### Main point about code block 1

```
code block 1
```

More text explaining code block 2

```
code block 2
```

<div class="end-examples"></div>
