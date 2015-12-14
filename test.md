_This styleguide has been adapted from https://google.github.io/styleguide/htmlcssguide.xml._

-------------------------------------------------------------------------------

# CSS Guidelines

This is a collection of CSS guidelines that Hack Club workshops should follow to
stay consistent.

**Capitalization** Use only lowercase.

**80 characters wide** Where possible, limit lines to 80 characters wide.

**Indentation** CSS should use 2 spaces per level of indentation.

**Multi-line CSS** CSS rules should always be multipule lines to

_Example:_

```css
// Correct:
.icon {
  width: 16px;
}
```

```css
/* Incorrect: */
.icon {width: 16px;}
```

**Single Line Comments**
Single line comments should be encased in `/*` and `*/`. Comments follow regular
indentation practices.

_Example:_ `/* Header */`

**Multi-line Comments**
Multiline comments should be encased in an opening (`/*`) and closing (`*/`)
comment. Comments follow regular indentation.

_Example:_ 

```css
p {
  /*
  The following lines are rules that apply to the 'p' selector. Each rule is
  paired with a value after the colon.
  */
  margin: 1em;
  padding: 2em; 
  color: white;
  background-color: blue;
}
```
      
**Declaration Block Seperation**

_Example:_ 

_Correct:_

```css
/* Recommended */
#video {
  margin-top: 1em;
}
```

_Incorrect:_

```css
/* Not recommended: missing space */
#video{
  margin-top: 1em;
}

/* Not recommended: unnecessary line break */
#video
{
  margin-top: 1em;
}
```

