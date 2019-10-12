# 使用 highlight.js 或 prism.js 高亮代码

## HTML
```html
<div id="list">
    <li>1-1</li>
    <li>1-2</li>
    <li>1-3</li>
</div>
```

## CSS
```css
 .list {
    list-style: none;
    color: aqua;
}

.list li {
    text-align: center;
    font-size: 14px;
}
```

## SCSS
```scss
#main p {
  color: #00ff00;
  width: 97%;
  .redbox {
    background-color: #ff0000;
    color: #000000;
  }
}
```

## JavaScript 
```js
var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}
```

## JSON
```json
{
  "name": "ShenBao",
  "occupation": "Web App Developer"
}
```


## XML
```xml
<note>
    <to>George</to>
    <from>John</from>
    <heading>Reminder</heading>
    <body>Don't forget the meeting!</body>
</note>
```

## Angular
```js
import { Component } from '@angular/core';

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.scss']
})
export class AppComponent {

  title = 'Angular CNode';

  constructor() {

  }
}
```
## TypeScript
```js
let str:string = 'str';
const tml = `${str}`;
let isDone: boolean = false;
let list: number[] = [1, 2, 3];

interface LabelledValue {
  label: string;
}

function printLabel(labelledObj: LabelledValue) {
  console.log(labelledObj.label);
}

class Greeter {
    greeting: string;
    constructor(message: string) {
        this.greeting = message;
    }
    greet() {
        return "Hello, " + this.greeting;
    }
}

let greeter = new Greeter("world");
```

## java
```java
/**
*   java HelloWorld
*/
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

## ruby
```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

## bash
```bash
#!/bin/sh
sed 's/abc/cba/' 
curl
#!/bin/bash  
echo "Hello World !" 
chmod +x ./test.sh  #使脚本具有执行权限  
./test.sh  #执行脚本  
/bin/sh test.sh
```


## diff

```diff
##webpack-demo
  |- package.json
  |- webpack.config.js
  |- /dist
    |- bundle.js
    |- index.html
  |- /src
-   |- style.css
+   |- style.scss
    |- index.js
  |- /node_modules
```

```diff
- <title>Getting Started</title>
+ <title>Asset Management</title>
```

```diff
  const path = require('path');

  module.exports = {
    entry: './src/index.js',
    output: {
      filename: 'bundle.js',
      path: path.resolve(__dirname, 'dist')
    },
+   module: {
+     rules: [
+       {
+         test: /\.css$/,
+         use: [
+           'style-loader',
+           'css-loader'
+         ]
+       }
+     ]
+   }
  };
```

```diff
  let str:string = 'str';
- const tml = str + 'ing';
+ const tml = `${str}ing`;
```

## 百行代码测试
```js
var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}


var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}


var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}

var str = 'string';
var num = 88;
var bool = true;
var fn = function(){
    console.log(str);
}
function hFn(){
    alert('test');
}
```
