# Lesson 1

Test paragraph—easy as this one—goes here.

```python
print("I have some Python code in this file")
```

If you want to put some command, like `print` inline, you want to make sure to use the backticks as in this example. To illustrate any HTML, I also want to include that:

```html
<div class="testing-things-out">What do you think?</div>
```

If we wanted to style the class, we would create CSS:

```css
.testing-things-out {
    'background-color': blue;
}
```

# You don't have to keep "Lesson 2" in the title, but keep it short. This is a bad example

When you are ready to switch to the next lesson, just use another level one heading (`#`) like I just did here! That will automatically become a new paginated "page" on the website.

(VS Code will give you a warning but don't listen to it. It's just because VS Code thinks there should only be one level one header in a document.)

## What else can we do?

We can add more headers, just like that. (Make sure they are of the correct level. If the previous one is level one—`#`—then make this one level two: `##`. If you need to go deeper, level three headers is the last depth that we can do, using `###` before your header.)

We can use **bolding** or _italicizing_. It would really be good if you use `**` to surround bolded text and `_` to surround italicized text. (Then I can use regular expressions to make sure your texts are interpreted correctly!)

- We can use bulletpoint lists, of course!
- Add as many bulletpoints as you want

1. Or numbered lists.
2. With as many items as you need.

If you want to, you can add separators for clarity:

---

Very importantly, we can add images, and we do that by putting the following on _one line_. Also, make sure to move the files into the a new `images` directory (that you create) in the root directory of your workshop! This is what the image tag looks like in markdown if you need a reminder:

![This is the alt-text that describes the image](images/test-screenshot.png)

And if you want to, add a HTML comment with questions, concerns, mental notes, and where you think we could add other content (videos, gifs, interactive features) — see the [raw markdown for this file to see the comment below](http://www.github.com/DHRI-Curriculum/project-lab/blob/v2.0-kalle-testing-lessons/assessment.md)!

<!-- This is less structured so feel free to just add this content however you see fit. Perhaps, right here, we want a gif that shows the way that you'd interact with a text editor, or something similar? -->

At the end of each workshop, we would like you to include two specific headers:

## Challenge

Where you put a smaller challenge that our learners can try on their own and that ties in with the lesson above. It could, of course, also be a "reflection"—think about an ethical question, perhaps?

## Solution

Under this header, you would add the `solution` for the challenge above. Or whatever text explains the "challenge."

In both the solution and challenge headers, you can use any of the features of the rest of the file—multiple paragraphs, [links](), `inline codes` or images, or whatever you can imagine!

### Level 3 Header!

You can even add a submenu in the challenge or solution section if you want, like the menu above here.