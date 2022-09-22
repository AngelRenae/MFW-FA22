# media queries
    @media (max-width:540px) {
        .card {
            width: 100%;
            margin: 0;
        }
    }

broken down:
    @media(parameter){
        code
    }

    max-wdith:"value"
- when the webpage is a the size "value" and below, the code is applied
- when using max-width, must start with the largest "value" for the first media query and work downwards. otherwise, it'll overwrite

    min-width:"value
- mobile-first approach
- must start with the smallest dimensions for "value" and work your way up

- try not to use fixed widths so that content grows with page. avoid assigning height

## font sizing
    clamp(min, scale, max)
    clamp(min height, what you want the scale to be, max height)
- media query for font size in one line