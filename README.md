##  Create random string with rule.

## Install module

```
npm install --save randomaizer-util
```

or

```
yarn install --save randomaizer-util
```

### Import module
```
const random = require('randomaizer-util');
```

### Generate Integer with random length
```
random.int(_min, _max) // for example: 654 
```

### Generate random Number
```
random.count(_min, _max) // for example: 3 
```

### Generate random String (without special charset)
```
random.str(_min, _max) // for example: abC1 
```

### Generate random String (with special charset)
```
random.str_(_min, _max) // for example: A_b#1
```
### Generate random String (like licence key)
```
random.key(min_count_parts, min_charset_in_part, max_count_parts, max_charset_in_part) // for example: rKt7e4fL-xMBBEQjM-JM4e4Iyt-alRa7r8j
```
