# `<lorem-ipsum>` Custom Element

The `<lorem-ipsum>` component is built using the HTML Custom Elements v1 spec. This element takes two attributes:

- `type` - `{string}` (`paragraph`, `list`, or `words`).
- `length` - `{number|number[]}` a number or range of numbers to use to generate random Lorem Ipsum text.

### Paragraph
```html
<lorem-ipsum type="paragraph" length="3"></lorem-ipsum>
```

### Words
```html
<lorem-ipsum type="words" length="[5, 20]"></lorem-ipsum>
```
### Lists
```html
<lorem-ipsum type="list" length="5"></lorem-ipsum>
```
### Transcluding HTML Elements
```html
<lorem-ipsum type="paragraph" length="1">
    <ul>
        <li><button>Spin Me</button></li>
        <li><strong>Right Round</strong></li>
        <li>><small>Like A Record <sup>Baby</sup></small></li>
        <li><em>Right round round round</em></li>
    </ul>
</lorem-ipsum>
```
### Nesting <lorem-ipsum> Elements
```html
<lorem-ipsum type="paragraph" length="2">
    <h4><lorem-ipsum type="words" length="[2, 5]"></h4>
    <lorem-ipsum type="list" length="6"></lorem-ipsum>
    <h4><lorem-ipsum type="words" length="3"></h4>
    <lorem-ipsum type="list" length="3"></lorem-ipsum>
    <h4><lorem-ipsum type="words" length="[2, 5]"></h4>
    <lorem-ipsum type="list" length="10"></lorem-ipsum>
    <p><lorem-ipsum type="words" length="[20, 50]"></p>
</lorem-ipsum>
```

-----------
#### Donate

- **BTC:** 18o3S3rzdBqfUndc4pZm9dNUrNJ5zijDon
- **ETH:** 0x9289E1B3a846061B14E81FD521a3ac910EC908A7
