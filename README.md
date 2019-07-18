# Programming

- [Javascript.info](https://javascript.info/) - The Modern JavaScript Tutorial

- [SICP](https://github.com/marsupialmarcos/Resources/blob/master/Structure%20and%20Interpretation%20of%20Computer%20Programs.pdf) - Structure and Interpretation of Computer Programs for JS

# Data Structures

### Stack  🥞  
```javascript
function Stack() {
    this._size = 0;
    this._storage = {};
}
```
#### Operations of a Stack
Let's define the two operations of a stack:

- `push(value)` adds value to the top of the stack.
- `pop()` removes most recently added value from the stack.

### Queue 🎢
```javascript
function Queue() {
    this._oldestIndex = 1;
    this._newestIndex = 1;
    this._storage = {};
}
```
#### Operations of a Queue
Let's define the two operations of a Queue:

- `enqueue(value)` adds value to end of queue.
- `dequeue` removes oldest value in the queue.

### LinkedList  🔍 
```javascript
class LinkedList{
  constructor(){
  this._storage = {}
  }
} 

class Node{
  constructor(val){
    this._val = val;
    this._next = null;
    }
}
```
#### Operations of a LinkedList
Since every LinkedList contains nodes, which can be a separate constructor from a tree, we will outline the operations of both constructors: Node and LinkedList.

##### Node
`_val` stores a value.
`_next` points at the next node in the list.

##### LinkedList
- `_root` points to the root node of a tree.
- `traverseDF(callback)` traverses nodes of a tree with DFS.
- `traverseBF(callback)` traverses nodes of a tree with BFS.
- `contains(data, traversal)` searches for a node in a tree.
- `add(data, toData, traverse)` adds a node to a tree.
- `remove(child, parent)` removes a node in a tree. 

### Tree 🌳
```javascript
class Tree {
    constructor(val){
    var node = new Node(val);
    this._root = node;
}

class Node {
  constructor(val){
    this._val = val;
    this._parent = null;
    this._children = [];
    }
}

let leaf = new Tree('leaf');
console.log(leaf) // Tree {_root: Node {_val: leaf, _parent: null, _children: []}}
```
#### Operations of a Tree
Since every tree contains nodes, which can be a separate constructor from a tree, we will outline the operations of both constructors: Node and Tree.

##### Node
`_val` stores a value.
`_parent` points to a node's parent.
`_children` points to the next node in the list.

##### Tree
- `_root` points to the root node of a tree.
- `traverseDF(callback)` traverses nodes of a tree with DFS.
- `traverseBF(callback)` traverses nodes of a tree with BFS.
- `contains(data, traversal)` searches for a node in a tree.
- `add(data, toData, traverse)` adds a node to a tree.
- `remove(child, parent)` removes a node in a tree. 

### Graphs 📍
```javascript
class Graph{
  constructor(){
  this._adjList = {};
  }
} 

class Node{
  constructor(val){
    this.val = val;
    }
}
```

# Algorithms

- BubbleSort  🔮 
- SelectionSort 🎣
- InsertionSort ♠️
- MergeSort 🍻
- QuickSort ⌚️

# Visualizing

- [Javascript Visualizer](https://tylermcginnis.com/javascript-visualizer/) - A tool for visualizing Execution Context, Hoisting, Closures, and Scopes in JavaScript

- [The Event Loop, the Callback Queue](http://latentflip.com/loupe/) - A tool for visualizing the Event Loop and Callback Queue

- [Javascript Tutor](http://pythontutor.com/javascript.html#mode=edit) - Visualize JavaScript code execution

- [VisuAlgo](https://visualgo.net) - A tool for visualizing Algorithms and Data Structures

# System Design

- [System Design Primer](https://github.com/donnemartin/system-design-primer) - Learn how to design large-scale systems, includes flashcards.


- [Design A Parking Lot](https://www.educative.io/collection/page/5668639101419520/5692201761767424/5770234338213888) - Design A Parking Lot

- [Design A Library Management System](https://www.educative.io/collection/page/5668639101419520/5692201761767424/5636470266134528) - Design A Library Management System


- [Design A URL Shortening Service](https://www.educative.io/collection/page/5668639101419520/5649050225344512/5668600916475904) - Design A URL Shortening Service

- [Design Instagram](https://www.educative.io/collection/page/5668639101419520/5649050225344512/5673385510043648) - Design Instagram


# Design Patterns

- [ES6 Design Patterns](https://loredanacirstea.github.io/es6-design-patterns/) GoF Design Patterns in ES6+

### Creational

Creational | Definition
--- | --- |
**Factory Method** | Makes an instance of several derived classes based on interfaced data or events
**Abstract Factory** | Creates an instance of several families of classes without detailing concrete classes.
**Builder** | Separates object construction from its representation, always creates the same type of object.
**Prototype** | A fully initialized instances used for copying or cloning.
**Singleton** | A class with only a single instance with global access points.

### Structural
Structural | Definition
--- | --- |
**Adapter** | Match interfaces of different classes therefore classes can work together despite incompatible interfaces.
**Bridge** | Separates an object's interface from its implementation so the two can vary independently
**Composite** | A strucuture of simple and composite objects which makes the total object more than just the sum of its parts
**Decorator** | Dynamically add alternate processing to objects.
**Flyweight** | A fine-grained instance used for efficient sharing of information that is contained elsewhere.
**Proxy** | A pace holder object representing the true object.

### Behavioral
---|---|
**Interpreter** | Away to include language elements in an application to match the grammar of the intended language.
**Template Method** | Creates the shell of an algorithm in a method, then defer the exact steps to a subclass
**Chain of Responsibility** | A way of passing a request between a chain of objects to find the object that can handle the request
**Command** | Encapsulate a command request as an object to enable, logging and/or queuing of requests, and provides error-handling for unhandled requests.
**Iterator** | Sequentially access the elements of a collection without knowing the inner workings of the collection
**Mediator** | Defines simplified communication between classes to prevent a group of classes from referring explicitly to each other
**Memento** | Capture an object's internal state to be able to restore it later.
**Observer** | A way of notifying change to a number of classes to ensure consistency between the classes.
**State** | Alter an object's behavior when its state changes
**Strategy** | Encapsulates an algorithm inside a class separating the selection from the implementation
**Visitor** | Adds a new operation to a class without changing the class.

# Node.JS

- [Node School](https://nodeschool.io/) - Open source workshops that teach web software skills. Do them on your own or at a workshop nearby.

- [Rithm School Node/Express Fundamentals](https://www.rithmschool.com/courses/node-express-fundamentals) - Rithm School Node and Express.js Fundamentals.

# Networking

- [Computer Networking](https://github.com/marsupialmarcos/Resources/blob/master/Computer%20Networking.pdf)

- [Wireshark Labs](http://gaia.cs.umass.edu/wireshark-labs/)

# Operating Systems and Architecture

- [The Elements of Computing Systems](https://github.com/marsupialmarcos/Resources/blob/master/The%20Elements%20of%20Computing%20Systems.pdf) - Building a Modern Computer from First Principles

- [Operating Systems](https://github.com/marsupialmarcos/Resources/blob/master/Operating%20Systems.pdf) - Three Easy Pieces centered around three conceptual pieces that are fundamental to operating systems: virtualization, concurrency, and persistence.

# Security

- [Buggy Web App](http://www.itsecgames.com/) - Buggy Web App!

- [OWSAP](https://cheatsheetseries.owasp.org/) - Collection of high value info on specific app security topics created by various application security professionals with expertise in specific topics.

- [OSCP Preparation Roadmap](https://security-prince.github.io/PWK-OSCP-Preparation-Roadmap/) - OSCP Prep

- [Pentester Academy](https://www.pentesteracademy.com/)

# Robotics

- [Johny-Five](http://johnny-five.io/) - JavaScript Robotics & IoT Platform

- [Node Red](https://nodered.org/) - Node-RED provides a browser-based editor that makes it easy to wire together flows using the wide range of nodes that can be deployed to its runtime in a single-click.

# Game Dev 👾

- [Game Development](https://github.com/marsupialmarcos/Resources/blob/master/Building%20JavaScript%20Games%20for%20Phones%2C%20Tablets%2C%20and%20Desktop.pdf)

# Artificial Intelligence

- [Neural Network Zoo](http://www.asimovinstitute.org/neural-network-zoo/) - Neural Networks and corresponding academic papers

- [Neural Network Zoo](http://www.asimovinstitute.org/neural-network-zoo/) - Neural Networks and corresponding academic papers

- [Neural Networks](https://github.com/marsupialmarcos/Resources/blob/master/neuron.pdf)

# Finance

- [Corporate Finance](https://github.com/marsupialmarcos/Resources/blob/master/corporate-finance.pdf)

- [Investments](https://github.com/marsupialmarcos/Resources/blob/master/Investments_11e_-_Zvi_Bodie.pdf-min.pdf)

- [Python for Finance: Analyze Big Financial Data](https://github.com/marsupialmarcos/Resources/blob/master/Python%20for%20Finance_%20Analyze%20Big%20Financial%20Data%20%5BHilpisch%202014-12-27%5D.pdf)

# Notable Scientists in AI:

- Ian Goodfellow
- Andrew Ng
- Yann LeCunn
- Yoshua Bengio
- Geoffrey Hinton
