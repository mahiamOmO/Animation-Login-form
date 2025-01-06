# "Different Types of CSS Selectors”
## "Different Types of CSS Selectors”

![Untitled Diagram drawio (3)](https://github.com/user-attachments/assets/d6d71708-d28f-4cd3-9e8e-a104ca29c507)

### Class Selector:
#### Code:
```html
<body>
    <p class="heighlight">class of "heighlight".</p>
    <p>does not have any specific class.</p>
    <p class="heighlight">a class of "heighlight".</p>
</body>
```

```html
<style>
.heighlight {
    color: red;
    font-weight: bold;
}
</style>
```

### Id Selector:
<!--- Id Selector -->

#### Code:
```html
<body>
    <h1 id="main-heading">This h1 has an id</h1>
    <p>This paragraph does not have an id</p>
    <p id="intro-paragraph">This paragraph has an id</p>
</body>
```
```html
<style>
#main-heading {
    color: blue;
    font-size: 24px;

}

#intro-paragraph {
    background-color: yellow;
    padding: 10px;

}
</style>

```


### Elementor Selector:


```html 
<body>
    <h1>Welcome to My Website</h1>
    <p>This is a paragraph</p>
    <p>This is another paragraph</p>
    <a href="https:///www.google.com">Visit Example Website</a>
</body>
```
```html
<style>
    h1 {
        color: blue;
    }
    p {
      font-size: 16px;

    }
    a {
        text-decoration: none;
        color: red;
    }
</style>
```
### Universal  Selector
#### Code:
```html
<body>
    <h1>Welcome to My Website</h1>
    <p>This is a paragraph</p>
    <div>
        <h2>About Us</h2>
        <p>This is another paragraph</p>
    </div>
</body>
```
```html
<style>
*{
    margin: 0;
    padding: 0;
    border: 1 px solid;
}
</style>
```

### Grouping Selector:
#### Code:
```html
<body>
    <h1>Welcome to My Website</h1>
    <p>This is a paragraph.</p>
    <a href="#">Click me</a>
    <button>Submit</button>
</body>
```
```html
<style>
    h1,p {
        color: blue;
    }
    a,button {
        background-color: yellow;
        padding: 10px;
    }
</style>
```
### Attribute Selector:
#### Code:

```html
<form>
    <label for="name">Name:</label>
    <input type="text" id="name" required />
    <input type="submit" value="Submit" />
</form>
```
```html
<style>
    input[type="submit"] {
        background-color: #4caf50;
        color: white;
    }
    input[required] {
        border: 1px solid red;
    }
</style>
```


