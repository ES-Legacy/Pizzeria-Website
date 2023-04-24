# Style Guide
This is a comprehensive style guide with conventions that the whole app should end up following, to be consistent and better organized and such.

## HTML conventions
### Elements
- Elements must be lowercase
- Elements must have a closing tag
- Empty elements must have a closing tag for XML/XHTML software (it is a requirement for XML and XHTML)



### Attributes

#### Attribute Names
- Attributes must be follow a camelCase convention (i.e. instead of attribute classname or class-name, the appropriate spelling would be className)

#### Attribute Values
- Attribute values must have double quotes around them (i.e. className = "value")


## CSS conventions
- When defining dimmensions, try to avoid using absolute units (px, cm, in, etc.).... Instead use relative units such as (em,vw,vh,rem,%,etc.) this is good for responive design
- import stylesheets for relevent components and sections of the app
- Start with as little specificity as possible to avoid overwriting other css files
- If short use one line, otherwise give each css attribute its own line
- Do not use !important
- Try to avoid using ID selectors (this will make overwriting very cumbersome)
- Try to avoid using repeated selectors (i.e. .className1.className1), This can add weight to specificity columns, however makes the CSS look messy and harder to read
- If using repeated selectors, be extra sure to comment the css