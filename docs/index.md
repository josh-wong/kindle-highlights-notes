# READ FIRST: Overview and sync process

## Overview

This is a knowledge base of my highlights and notes from books I have read or am currently reading on Kindle.

Feel free to also check out [my Goodreads profile](https://www.goodreads.com/user/show/70600963-joshua-wong) for additional details about particular books on my "shelf."

!!! info

	**Disclosure:** Some of the links on this site contain affiliate links. If you go through those links to make a purchase, I may earn a commission.

## Sync process

### 1. Sync highlights and notes from Kindle to Obsidian

The [Obsidian Kindle Plugin](https://github.com/hadynz/obsidian-kindle-plugin) generates these pages, syncing highlights and notes to my [Obsidian](https://obsidian.md/) vault.

!!! note
	
	Because of a limitation with the [Obsidian Kindle Plugin](https://github.com/hadynz/obsidian-kindle-plugin), if you do any of the following, your highlights and notes will not be updated unless you delete the .md files and re-sync:
	
    - Delete highlights
    - Add, modify, or delete notes

To ensure I have the most updated version of my Kindle highlights and notes in Obsidian, a script runs on a daily basis to do the following: 

!!! note

	In order for this script to work properly, you must be logged in to your Amazon account within the Obsidian Kindle Plugin and have "**Sync on Startup**" set to enabled in the plugin settings.

1. Delete the .md files in the Obsidian folder where the contents of this vault live.
2. Open the vault.
3. Wait about 15 minutes for Kindle highlights and notes to re-sync.
4. Close the vault.

That script is based on [app-open-close-script](https://github.com/josh-wong/app-open-close-script/).

### 2. Sync highlights and notes from Obsidian to local GitHub folder

A script runs on a daily basis to sync any new highlights and notes with this GitHub repository. 

That script is based on [remove-copy-folder-scripts](https://josh-wong.github.io/remove-copy-folder-scripts/).

### 3. Sync highlights and notes from local GitHub folder to GitHub-hosted repository

After the previous script runs, another script runs to sync any new highlights and notes from my local GitHub folder to my GitHub-hosted repository. 

That script is based on [commit-submit-merge-script](https://github.com/josh-wong/commit-submit-merge-script).

## Plugin templates

After installing the Obsidian Kindle Plugin in Obsidian, you can configure templates. The plugin provides default templates for both "File template" and "Highlights template."

The following are my customiozed templates. 

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

### Highlights template

```yaml
## Highlight

{{ text }}
- Location: [{{ location }}]({{appLink}})

{% if note %}### Note
{{note}}{% endif %}

---
```
