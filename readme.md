# Cours sur les Display css
Ce cours est dédié à la compréhension des display css

```css
    main ul{
    padding: 1.0rem;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 1rem;
}


main ul li:last-child{
    grid-column: 1 / 5;
    grid-row: 3;
}
```
## Liste des display
* display block
* display inline-block
* display grid