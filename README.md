
---

## 📝 Features Implemented

### 1. Basic Selectors
- **Element Selector** → Styles applied directly to `h1`, `p`, etc.  
- **Class Selector (`.classname`)** → Used for reusable styles (e.g., `.menu`, `.posts`).  
- **ID Selector (`#id`)** → Can be used for unique elements (not used much here).  

### 2. Combinators
- **Descendant Selector (`A B`)** → Targets elements inside another.  
- **Child Selector (`A > B`)** → Targets direct children only.  
- **Adjacent Sibling (`A + B`)** → Styles the element immediately after another.  
- **General Sibling (`A ~ B`)** → Styles all siblings after another element.  

### 3. Pseudo-classes
Pseudo-classes style elements based on their **state or position**.

- **`:hover`** → Changes style when hovering over an element.  
- **`:active`** → Styles when an element is being clicked.  
- **`:focus`** → Styles an input when focused (for forms).  
- **`:first-child`** → Styles the first child of a parent.  
- **`:last-child`** → Styles the last child of a parent.  
- **`:nth-child(n)`** → Styles elements at a specific position.  
- **`:nth-of-type(n)`** → Styles elements of a specific type at a position.  
- **`:not(selector)` (Negation)** → Styles elements that **do not** match the selector.  

---

## 💻 Example Code Snippets

### HTML
```html
<ul class="menu">
  <li><a href="#">Home</a></li>
  <li><a href="#">Articles</a></li>
  <li><a href="#">About</a></li>
  <li><a href="#">Contact</a></li>
</ul>
