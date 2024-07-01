# ES6 data manipulation
## Description:
Array... Array everywhere
- How to use map, filter and reduce on arrays
- Typed arrays
- The Set, Map, and Weak link data structures

## Resources:
Read or watch:
- [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
- [Typed Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Typed_arrays)
- [Set Data Structure](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)
- [Map Data Structure](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)
- [WeakMap](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap)

## Requirements:
- Ubuntu 18.04 LTS using NodeJS 12.22.x
- Jest Testing Framework
- ESLint

### Install NodeJS 12.22.x
```console
$ curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
$ sudo bash nodesource_setup.sh
$ sudo apt install nodejs -y
```

### Check version
```console
$ nodejs -v
v12.22.1
$ npm -v
6.14.12
```

### Install Jest, Babel, and ESLint
```console
$ npm install --save-dev jest
$ npm install --save-dev babel-jest @babel/core @babel/preset-env
$ npm install --save-dev eslint
$ npm install
```

## Files:
[0. Basic list of objects](./0-get_list_students.js)

[1. More mapping](./1-get_list_student_ids.js)

[2. Filter](./2-get_students_by_loc.js)

[3. Reduce](./3-get_ids_sum.js)

[4. Combine](./4-update_grade_by_city.js)

[5. Typed Arrays](./5-typed_arrays.js)

[6. Set data structure](./6-set.js)

[7. More set data structure](./7-has_array_values.js)

[8. Clean set](./8-clean_set.js)

[9. Map data structure](./9-groceries_list.js)

[10. More map data structure](./10-update_uniq_items.js)

[11. Weak link data structure](./100-weak.js)
