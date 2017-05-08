jslint.js that can be executed by Rhino.

# usage

```sh
java -Dfile.encoding=UTF-8 -jar js.jar jslint.js target_js_file.js
```

OR

```sh
java -Dfile.encoding=UTF-8 -jar js.jar jslint.js -file file_list.txt
```

file_list.txt is like this:
```
a.js
b.js
c.js
d.js
e.js
```
