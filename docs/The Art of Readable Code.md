---
kindle-sync:
  bookId: '34069'
  title: >-
    The Art of Readable Code: Simple and Practical Techniques for Writing Better
    Code
  author: Dustin Boswell and Trevor Foucher
  asin: B0064CZ1XE
  lastAnnotatedDate: '2022-10-21'
  bookImageUrl: 'https://m.media-amazon.com/images/I/81SHDpsLz3L._SY160.jpg'
  highlightsCount: 12
---
# The Art of Readable Code: Simple and Practical Techniques for Writing Better Code

## Metadata

| Syntax | Description |
| ---------- | ---------- |
| **Title** | [The Art of Readable Code: Simple and Practical Techniques for Writing Better Code](https://www.amazon.com/dp/B0064CZ1XE) |
| **Author** | [Dustin Boswell and Trevor Foucher](https://www.amazon.com/Dustin-Boswell/e/B0068WNFOW/ref=dp_byline_cont_ebooks_1) |
| **Book on Kindle** | <a href="kindle://book?action=open&asin=B0064CZ1XE" target="_blank">Open in Kindle</a> |
| **Tags** | #Kindle #books |

---

## Highlight

Code should be written to minimize the time it would take for someone else to understand it. ^ref-64014
- Location: [260](kindle://book?action=open&asin=B0064CZ1XE&location=260)

---
## Highlight

For someone to fully understand your code, they should be able to make changes to it, spot bugs, and understand how it interacts with the rest of your code. Now, you might be thinking, Who cares if someone else can understand it? I’m the only one using the code! Even if you’re on a one-man project, it’s worth pursuing this goal. That “someone else” might be you six months later, when your own code looks unfamiliar to you. And you never know — someone might join your project, or your “throwaway code” might get reused for another project. ^ref-42650
- Location: [264](kindle://book?action=open&asin=B0064CZ1XE&location=264)

---
## Highlight

So even though having fewer lines of code is a good goal, minimizing the time-till-understanding is an even better goal. ^ref-24032
- Location: [279](kindle://book?action=open&asin=B0064CZ1XE&location=279)

### Note
If adding comments in the code improves the likelihood of understanding by yourself or others in the future, doing that is better than overall minimizing the lines of code. Also, adding comments improves searchability and discovery when searching code repositories.

---
## Highlight

A lot of the time, they’re overused out of pure laziness. This is understandable — when nothing better comes to mind, it’s easier to just use a meaningless name like foo and move on. But if you get in the habit of taking an extra few seconds to come up with a good name, you’ll find your “naming muscle” builds quickly. ^ref-52026
- Location: [426](kindle://book?action=open&asin=B0064CZ1XE&location=426)

### Note
Personally, following this method has been a habit of mine for a while for the exact reasons the author states. 

In the past, I've taken sample code and kept the naming conventions that the developer used. But when I would revisit the code, especially weeka or months later, I wouldn't be able to remember what the function names meant. If I had heavily customized the original code sample, I would need to revisit the original code sample and spend time remembering what that function was and how the function was intended to work. 

---
## Highlight

Having different formats for different entities is like a form of syntax highlighting — it helps you read the code more easily. Most of the formatting in this example is pretty common — using CamelCase for class names, and using lower_separated for variable names. ^ref-28647
- Location: [608](kindle://book?action=open&asin=B0064CZ1XE&location=608)

---
## Highlight

For instance, in JavaScript: The Good Parts (Douglas Crockford, O’Reilly, 2008), the author suggests that “constructors” (functions intended to be called with new) should be capitalized and that ordinary functions should start with a lowercase letter: var x = new DatePicker();  // DatePicker() is a "constructor" function var y = pageHeight();      // pageHeight() is an ordinary function ^ref-2357
- Location: [624](kindle://book?action=open&asin=B0064CZ1XE&location=624)

---
## Highlight

Actively scrutinize your names by asking yourself, “What other meanings could someone interpret from this name?” ^ref-35321
- Location: [661](kindle://book?action=open&asin=B0064CZ1XE&location=661)

---
## Highlight

The clearest way to name a limit is to put max_ or min_ in front of the thing being limited. ^ref-37109
- Location: [701](kindle://book?action=open&asin=B0064CZ1XE&location=701)

---
## Highlight

Finally, it’s best to avoid negated terms in a name. For example, instead of: bool disable_ssl = false; it would be easier to read (and more compact) to say: bool use_ssl = true; ^ref-38422
- Location: [747](kindle://book?action=open&asin=B0064CZ1XE&location=747)

---
## Highlight

Before you decide on a name, play devil’s advocate and imagine how your name might be misunderstood. The best names are resistant to misinterpretation. ^ref-6052
- Location: [843](kindle://book?action=open&asin=B0064CZ1XE&location=843)

---
## Highlight

When it comes to defining an upper or lower limit for a value, max_ and min_ are good prefixes to use. For inclusive ranges, first and last are good. For inclusive/exclusive ranges, begin and end are best because they’re the most idiomatic. When naming a boolean, use words like is and has to make it clear that it’s a boolean. Avoid negated terms (e.g., disable_ssl). ^ref-12825
- Location: [844](kindle://book?action=open&asin=B0064CZ1XE&location=844)

---
## Highlight

Chapter 4. Aesthetics ^ref-47940
- Location: [852](kindle://book?action=open&asin=B0064CZ1XE&location=852)

---
