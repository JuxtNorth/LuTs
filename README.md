# Look-up Tables

This repo contains various look-up tables for different purposes. A look-up table is an array or object that replaces runtime computation with a simpler look-up. Look-up tables are useful for speeding up calculations, validating input values, and implementing programmable hardware functionality.

<hr>

## Contents

As of now, This repo contains the following look-up tables:

- CSS Color Table: This Look-up table can be used to obtain an object consisting of RGB values using a given key string with the same name as any built-in CSS color.

<hr>

# Usage

To use a look-up table, simply import the corresponding file into your project and access the object or array with the desired key. Here is a simple example to get an object of rgb values with a CSS built-in color as the key:

```js
import { Lut } from '/path/to/LuT.js';

const key = "fuchsia";
const rgb = Lut[ key ]; // { r: 255, g: 0, b: 255 }
```

### Note: Keys are case-sensitive.
### Note 2: Don't forget to export the look-up table before importing it.

<hr>

# License
This repo is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.