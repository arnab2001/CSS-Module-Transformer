
# Buildtime CSS Module Transformer 

Babel CSS Module Transformer is a Babel plugin designed to automatically transform classnames in JSX attributes to use CSS modules. This plugin replaces className="example" with className={styles.example} for static classnames and className={dynamicClassName} with className={styles[dynamicClassName]} for dynamic classnames.


## Features

- Automatic Transformation: The plugin automatically detects and transforms classnames containing hyphens to use CSS modules.
- Static Classnames: Replaces static classnames defined in JSX attributes with the corresponding CSS module syntax.
- Dynamic Classname Support: Seamlessly handle both static and dynamic classnames in JSX
- Dynamic Classname Support: Seamlessly handle both static and dynamic classnames in JSX
- Preserve other JSX attributes while transforming classnames


## Installation

Install my-project with npm

```bash
npm install babel-css-module-transformer --save-dev
```
    
## Usage/Examples

```json
{
  "plugins": ["babel-css-module-transformer"]
}
```

