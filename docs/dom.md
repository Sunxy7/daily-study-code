# DOM 是什么？

Dom 是 xxxx

# DOM 常见操作

##

## 创建 DOM 节点

`document.createElement(tagName) //创建一个元素节点 cloneNode.cloneNode(isDeepClone) // 克隆一个节点`

## 增加一个 DOM 节点

let body = document.querySeletor('body');
const h1 =document.createElement('h1');
body.appendChild(h1);
parentNode.insterBefore(newNode,oldNode);
replaceNode();

## 删除节点

removeChild();

## 查找节点

document.querySelector(tagName/className/idName); // 只获取第一个
document.querySelectorAll(tagName/className/idName); // 获取所有，并且可以通过 for 循环遍历
document.getElementById('id');//获取第一个 id 为查询条件的元素
document.getElementsByClassName('className'); //
document.getElementsByName('name'); // 根据 name 属性获取元素返回 nodeList 类型
document.getElementsByTagName('li'); // 返回所有 li 标签元素，返回一个 Html 元素集合

## 根据节点关系查找相关节点

Element.parentNode //
Element.parentElement //

Element.childNodes // 所有子节点，
Element.children // 所有子元素节点

Element.firstChild;
Element.firstElementChild);

Element.nextElementSibling;
Element.nextSibling;
Element.previousElementSibling;
Element.previousSibling;
