# READ FIRST: Overview and sync processes

This is a knowledge base of my highlights and notes from books I have read or am currently reading on Kindle.

Feel free to also check out [my Goodreads profile](https://www.goodreads.com/user/show/70600963-joshua-wong) for additional details about particular books on my "shelf."

## Sync process

### 1. Sync highlights and notes from Kindle to Obsidian

The [Obsidian Kindle Plugin](https://github.com/hadynz/obsidian-kindle-plugin) generates these pages, syncing highlights and notes to my [Obsidian](https://obsidian.md/) vault.

> **Note**
> 
> I haven't automated this process yet. Automating this process would require deleting all .md files except index.md, and then re-syncing all highlights and notes. 
> 
> Because of a limitation with the [Obsidian Kindle Plugin](https://github.com/hadynz/obsidian-kindle-plugin), if you do any of the following, your highlights and notes will not be updated unless you delete the .md files and re-sync:
> - Deleted highlights
> - New, modified, or deleted notes
> 
> Creating a script to do the following should work:
> - Delete the .md files in the Obsidian folder where the contents of this vault live.
> - Open this vault.
> - Wait about 10 minutes for Kindle highlights and notes to re-sync.
> - Close this vault.

### 2. Sync highlights and notes from Obsidian to local GitHub folder

A script runs on a daily basis to sync any new highlights and notes with this GitHub repository. That script is based on [remove-copy-folder-scripts](https://josh-wong.github.io/remove-copy-folder-scripts/).

### 3. Sync highlights and notes from local GitHub folder to GitHub-hosted repository

After the previous script runs, another script runs to sync any new highlights and notes from my local GitHub folder to my GitHub-hosted repository. That script is based on [commit-submit-merge-script](https://github.com/josh-wong/commit-submit-merge-script).

## Plugin templates

The following are the templates I use for the Kindle Highlights plugin.

### File template


```yaml
# {{longTitle}}

## Metadata

 | Syntax | Description |
 | ---------- | ---------- |
 | {% if url %}**Title** | [{{longTitle}}]({{url}}){% endif %} |
 | {% if authorUrl %}**Author** | [{{author}}]({{authorUrl}}){% elif author %}[[{{author}}]]{% endif %} |
 | {% if appLink %}**Book on Kindle** | <a href="{{appLink}}" target="_blank">Open in Kindle</a>{% endif %} |
 | **Tags** | #Kindle #books |
 
---

{{highlights}}
```

#### Highlights template

```yaml
## Highlight

{{ text }}
- Location: [{{ location }}]({{appLink}})

{% if note %}### Note
{{note}}{% endif %}

---
```
