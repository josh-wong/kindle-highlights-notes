---
kindle-sync:
  bookId: '63265'
  title: 'Modern Technical Writing: An Introduction to Software Documentation'
  author: Andrew Etter
  asin: B01A2QL9SS
  lastAnnotatedDate: '2023-03-13'
  bookImageUrl: 'https://m.media-amazon.com/images/I/71N2zYWXZoL._SY160.jpg'
  highlightsCount: 20
---
# Modern Technical Writing: An Introduction to Software Documentation

## Metadata

| Syntax | Description |
| ---------- | ---------- |
| **Title** | [Modern Technical Writing: An Introduction to Software Documentation](https://www.amazon.com/dp/B01A2QL9SS) |
| **Author** | [Andrew Etter](https://www.amazon.comundefined) |
| **Book on Kindle** | <a href="kindle://book?action=open&asin=B01A2QL9SS" target="_blank">Open in Kindle</a> |
| **Tags** | #Kindle #book |

---

## Highlight

Great documentation makes new hires productive in days instead of weeks, prevents thousands of calls to customer support, is the difference between crippling downtime and rock solid stability, and inspires true, fervent love of development platforms. ^ref-1121

- Location: [28](kindle://book?action=open&asin=B01A2QL9SS&location=28)

---
## Highlight

Huge blocks of writing look intimidating, and excessive content waters down useful content. Identify what the audience actually needs to know, and include only that. ^ref-12458

- Location: [47](kindle://book?action=open&asin=B01A2QL9SS&location=47)

---
## Highlight

Technical writers, first and foremost, are testers and researchers. Your job is to know what people want to achieve and precisely how to achieve it. Communicating that knowledge is the last step of the process and really shouldn't comprise more than 10% of your time. ^ref-54235

- Location: [55](kindle://book?action=open&asin=B01A2QL9SS&location=55)

---
## Highlight

When people say, "I was writing all day," they don't mean they were intermittently typing for eight straight hours. They mean they spent the entire day engaged in the writing process. And a big part of that process is installing, configuring, and testing software. In other words, learning. ^ref-25595

- Location: [57](kindle://book?action=open&asin=B01A2QL9SS&location=57)

---
## Highlight

The learning process is time-consuming, so don't be discouraged if your measurable output is essentially nil for days or even weeks after moving onto a new project. ^ref-27878

- Location: [68](kindle://book?action=open&asin=B01A2QL9SS&location=68)

---
## Highlight

What is this product? Why would anyone want it? These two questions are incredibly challenging for the average technical writer, a group of people much more focused on how than what or why. I've struggled with them many times. But if you can't answer these questions, you need to go back to the research phase, because you don't understand your audience at all. The answer to this question shouldn't come from a marketing department. Instead, it should be an honest, buzzword-free appraisal of capabilities and use cases. ^ref-64775

- Location: [116](kindle://book?action=open&asin=B01A2QL9SS&location=116)

---
## Highlight

How does this product fit into a broader ecosystem, if at all? Does it have any dependencies? ^ref-62670

- Location: [120](kindle://book?action=open&asin=B01A2QL9SS&location=120)

---
## Highlight

Where can I acquire this product? If there are multiple distribution packages, which should I choose and why? ^ref-13388

- Location: [123](kindle://book?action=open&asin=B01A2QL9SS&location=123)

---
## Highlight

How do I install the product? What are the basic configuration options, if any? ^ref-1523

- Location: [126](kindle://book?action=open&asin=B01A2QL9SS&location=126)

---
## Highlight

What does a simple, start to finish operation look like? ^ref-64678

- Location: [128](kindle://book?action=open&asin=B01A2QL9SS&location=128)

---
## Highlight

One of the most important functions of a technical writer is to record changes to a product. Good change logs convince people to upgrade, inspire confidence in the direction of a product, and help developers take advantage of new features. ^ref-47099

- Location: [162](kindle://book?action=open&asin=B01A2QL9SS&location=162)

---
## Highlight

Even the best documentation, like software, eventually goes out of date. PDFs get downloaded onto hard drives and then sit there like day-old bagels, growing more and more stale until they're actively harmful. You can never update them. Even if someone downloads updated versions, every modern web browser saves the new files as Admin_Guide (1).pdf rather than overwriting the old files. The whole situation gives me the chills. Hosting your content on a website gives you the power to fix inaccuracies almost instantly and keep your content in sync with the latest software release. ^ref-64342

- Location: [170](kindle://book?action=open&asin=B01A2QL9SS&location=170)

---
## Highlight

However you decide to write and distribute your documentation, you should do it in a way that encourages others to contribute. ^ref-5958

- Location: [179](kindle://book?action=open&asin=B01A2QL9SS&location=179)

### Note
This is extremely important. We can only become better at writing by involving ourselves in the process of writing. 

If we can give our colleagues the ability to improve or update documentation, we can become more knowledgeable about the intricacies of the product we are offering. 

Even better (and arguably), if we can give users the ability to revise our documentation, we can gain new perspective directly from them. This reduces the need for us to actively reach out  or make assumptions about the clarity of our documentation.

---
## Highlight

Storing content directly in XML-based languages like XHTML, DocBook, and DITA dramatically reduces people's ability to contribute. ^ref-61883

- Location: [226](kindle://book?action=open&asin=B01A2QL9SS&location=226)

---
## Highlight

Rather than being mere deterrents (like writing in XML), specialized applications actually prevent people from contributing. ^ref-64497

- Location: [230](kindle://book?action=open&asin=B01A2QL9SS&location=230)

---
## Highlight

If you have the opportunity to store your documentation in the same repository as its corresponding product source code, strongly consider doing so. The approach has some real appeal: Documentation and code branches stay in sync. Developers are more likely to contribute if they don't have to clone a separate repository. Of course, this approach also has some cons: If a repository is large (e.g. 2 GB), checking out the entire repository just to access the 40 KB ./docs directory can dramatically slow down documentation builds. Onerous commit hooks and pull request submission policies, designed to keep a code base stable, can make even simple documentation changes a chore. If your product is composed of code from many repositories, a single documentation repository offers simpler builds and a more cohesive writing experience. ^ref-39246

- Location: [284](kindle://book?action=open&asin=B01A2QL9SS&location=284)

---
## Highlight

The worst duplication sin of all is to store similar copies of the same documentation in version control. The root cause here is typically the desire to have one version for coworkers and another for customers, and it inevitably leads to a maintenance nightmare. Instead of multiple copies, the better approach is to use a feature sometimes called "conditional text." Conditional text lets you selectively include or exclude files (or portions of files) in the final output. AsciiDoc supports conditional text under the name "conditional inclusion macros." reStructuredText supports it through Sphinx with the .. only:: directive. Unfortunately, this feature is not present in Markdown. ^ref-52088

- Location: [303](kindle://book?action=open&asin=B01A2QL9SS&location=303)

---
## Highlight

Unfortunately, doing your job well might actually cause lawsuits. I've heard unsubstantiated rumors of patent trolls using publicly-available technical documentation as evidence of infringement. In this case, the open, forward-thinking spirit of enabling users to contribute to the documentation can be financially disastrous for your company. You might need to keep your source files in an internal repository, rather than GitHub. Further, you might need to protect your documentation website behind a customer login page. You should still use lightweight markup and distributed version control so that coworkers can contribute, but the general public might not be able to. ^ref-26875

- Location: [399](kindle://book?action=open&asin=B01A2QL9SS&location=399)

### Note
Interesting, considering many organizations are going the open-source route of publishing not only their product but also their documentation.

---
## Highlight

To show you how impressed they are, IT builds you a Linux VM with 256 MB of RAM and 3 GB of disk space and refuses to give you superuser privileges.↩︎ But they still don't submit the pull request.↩︎ ^ref-43071

- Location: [509](kindle://book?action=open&asin=B01A2QL9SS&location=509)

### Note
Comedy XD

---
## Highlight

Learn everything about a subject. Write down exactly what an audience needs to know and no more. Make the content beautiful, discoverable, scannable, and searchable. Consider everything a draft, and iterate relentlessly. Make contribution simple. ^ref-18965

- Location: [514](kindle://book?action=open&asin=B01A2QL9SS&location=514)

### Note
Good takeaways from this book for both technical writers and non-technical writers.

---
