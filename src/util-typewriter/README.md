# util-typewriter

Lean JS function to add typewriter effect to an HTML element

## Usage

To add a typewriter effect to and HTML element use

`type(element, "text");`

If you want to type multiple texts, you need to do it within an async function, and use await

`await type(element, "text1"); await type(element, "text2");`
