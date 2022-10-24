---
kindle-sync:
  bookId: '34069'
  title: >-
    The Art of Readable Code: Simple and Practical Techniques for Writing Better
    Code
  author: Dustin Boswell and Trevor Foucher
  asin: B0064CZ1XE
  lastAnnotatedDate: '2022-10-24'
  bookImageUrl: 'https://m.media-amazon.com/images/I/81SHDpsLz3L._SY160.jpg'
  highlightsCount: 25
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

Here is a simple example with a large group of variable definitions: # Extract POST parameters to local variables details  = request.POST.get('details') location = request.POST.get('location') phone    = equest.POST.get('phone') email    = request.POST.get('email') url      = request.POST.get('url') As you may have noticed, the third definition has a typo (equest instead of request). Mistakes like these are more pronounced when everything is lined up so neatly. ^ref-28724
- Location: [965](kindle://book?action=open&asin=B0064CZ1XE&location=965)

---
## Highlight

The brain naturally thinks in terms of groups and hierarchies, so you can help a reader quickly digest your code by organizing it that way. ^ref-11332
- Location: [1001](kindle://book?action=open&asin=B0064CZ1XE&location=1001)

### Note
The same should be expected of documentation, for the sake of simplifying navigation and discovery without relying solely on search.

---
## Highlight

When you’re writing code, you have a lot of valuable information in your head. When other people read your code, that information is lost — all they have is the code in front of them. ^ref-19333
- Location: [1072](kindle://book?action=open&asin=B0064CZ1XE&location=1072)

### Note
This thinking applies to only to others, but also our future selves. As we make changes to the code, we should also review the knowledge that we have left behind.

---
## Highlight

Don’t comment on facts that can be derived quickly from the code itself. ^ref-7937
- Location: [1090](kindle://book?action=open&asin=B0064CZ1XE&location=1090)

---
## Highlight

A comment can also explain why the code isn’t in great shape: // This class is getting messy. Maybe we should create a 'ResourceNode' subclass to // help organize things. This comment acknowledges that the code is messy but also encourages the next person to fix it (with specifics on how to get started). Without the comment, many readers would be intimidated by the messy code and afraid to touch it. ^ref-44123
- Location: [1141](kindle://book?action=open&asin=B0064CZ1XE&location=1141)

---
## Highlight

The important thing is that you should always feel free to comment on your thoughts about how the code should change in the future. Comments like these give readers valuable insight into the quality and state of the code and might even give them some direction on how to improve it. ^ref-18463
- Location: [1161](kindle://book?action=open&asin=B0064CZ1XE&location=1161)

---
## Highlight

A general technique we use in this book is to imagine what your code looks like to an outsider — someone who isn’t as intimately familiar with your project as you are. This technique is especially useful to help you recognize what needs commenting. ^ref-10779
- Location: [1182](kindle://book?action=open&asin=B0064CZ1XE&location=1182)

### Note
This method also applies to writing documentation, like design docs, product specs, API references, and release notes.

---
## Highlight

Don’t get overwhelmed by the thought that you have to write extensive, formal documentation. A few well-chosen sentences are better than nothing at all. ^ref-2851
- Location: [1232](kindle://book?action=open&asin=B0064CZ1XE&location=1232)

---
## Highlight

A lot of coders don’t like to write comments because it feels like a lot of work to write a good one. When writers have this sort of “writer’s block,” the best solution is to just start writing. So the next time you’re hesitating to write a comment, just go ahead and comment what you’re thinking, however half-baked it may be. ^ref-34760
- Location: [1255](kindle://book?action=open&asin=B0064CZ1XE&location=1255)

### Note
Solid advice for trying to get started writing longer, structured documentation when you have writer's block or "blank page syndrome." 

---
## Highlight

The purpose of a comment is to help the reader know what the writer knew when writing the code. This whole chapter is about realizing all the not-so-obvious nuggets of information you have about the code and writing those down. ^ref-25285
- Location: [1274](kindle://book?action=open&asin=B0064CZ1XE&location=1274)

---
## Highlight

Put yourself in the reader’s shoes: Anticipate which parts of your code will make readers say “Huh?” and comment those. Document any surprising behavior an average reader wouldn’t expect. Use “big picture” comments at the file/class level to explain how all the pieces fit together. Summarize blocks of code with comments so that the reader doesn’t get lost in the details. ^ref-21831
- Location: [1282](kindle://book?action=open&asin=B0064CZ1XE&location=1282)

---
## Highlight

Look at your code from a fresh perspective when you’re making changes. Step back and look at it as a whole. ^ref-28731
- Location: [1630](kindle://book?action=open&asin=B0064CZ1XE&location=1630)

---
## Highlight

When writing a comparison (while (bytes_expected > bytes_received)), it’s better to put the changing value on the left and the more stable value on the right (while (bytes_received < bytes_expected)). ^ref-60222
- Location: [1679](kindle://book?action=open&asin=B0064CZ1XE&location=1679)

---
## Highlight

Chapter 8. Breaking Down Giant Expressions ^ref-39764
- Location: [1690](kindle://book?action=open&asin=B0064CZ1XE&location=1690)

---
