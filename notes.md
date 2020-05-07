# Naming Conventions and Standard CSS styling

## An example of a standard css file would look like:

```css
.container {
    width: 500px;
    height: 100%;
    display: flex;
    flex-direction: column;
}

.row {
    width: 80%; /* 400px */
}

.row-50 {
    width: 50%; /* 200px */
}
```

Container would hold the entire document. So if container was 500 pixels:
1. `.row`, which is within `.container`, at **80%**, would be **400px**.
2. `.row-25`, which is within `.row`, at **50%**, would be **200px**.