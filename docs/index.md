---
hide:
  - footer
comments: true
---

# Welcome to the Amuzil Docs

Amuzil has many projects, including LWST[^1]. :smile:


???+ warning "Work in progress"

     This site is a work in progress. Please be patient.

## LaTeX

Inlined like this $\exists a,b\in G$

Or as a block:

$$
\operatorname{ker} f=\{g\in G:f(g)=e_{H}\}{\mbox{.}}
$$

## Critic

We also have a critic markup extension. Using it, we can showcase {++added++} and {--removed--} text.

We can also show {~~unchanged~>changed~~} text, {>>comments<<}, and {==highlights==}.

## Fancy code block

```javascript title="Timer" linenums="1" hl_lines="8 9 10 11 12"
Timer.prototype.applyEasing = function() {
  var t = this.percentage; // (1)!
  if (this.easing === 'ease-in') {
    return t * t;
  } else if (this.easing === 'ease-out') {
    return t * (2 - t);
  } else if (this.easing === 'ease-in-out') {
    if (t < 0.5) {
      return 2 * t * t;
    } else {
      return -1 + (4 - 2 * t) * t;
    }
  }
  return t; // default is linear.
};
```

1.  Between 0 and 1

## Now, a task list

- [x] This is a complete item
- [ ] This is an incomplete item
- [ ] This is an incomplete item
- [ ] This is an incomplete item

## Tabs

=== "Python"

    ```python
    def foo():
        if not bar:
            return True
    ```

=== "JavaScript"

    ```javascript
    function foo() {
        if (!bar) {
            return true;
        }
    }
    ```

=== "C"

    ```c
    int foo() {
        if (!bar) {
            return 1;
        }
        return 0;
    }
    ```

Now the second item

=== "Python"
    
    ```python
    def bar():
        if not foo:
            return True
    ```

=== "JavaScript"

    ```javascript
    function bar() {
        if (!foo) {
            return true;
        }
    }
    ```

[^1]: Our Discord bot.
