# Advanced CSS and Sass: Flexbox, Grid, Animations and More!

## Notebook for the course

Course link: https://www.udemy.com/course/advanced-css-and-sass/

# Checkpoints

## Class 10: Pseudo-elements

In this class we created a pseudo-element to create a fade to infinity animation for a button.

### Challenges

In this lecture I was experiencing a bug in the fade in animation for the header. The animation would start and the whole header would jump uppwards. This was a bug in chrome browser. To avoid this bug we should create a dummy script tag at the beginning of the body element.

    <body>
        <script>0</script>
        ...
    </body>
