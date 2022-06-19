# tiny.obj
A compact Wavefront .obj parser

Example code:
```js
import {parseObj} from "./parseObj.js"

let parsedObj = parseObj(obj_file_contents)

let verts = parsedObj.v
let texts = parsedObj.vt
let norms = parsedObj.vn
```
