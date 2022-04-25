# The purpose of this document is to describe what's happening in [[_Auto Template]] so you can properly trigger it on new documents with the  **Templater** hotkey (`CMD+SHFT+T`).

#### Relates to: [[___README#My Current Note-Taking Workflow]], [[Inbox Note Tag Taxonomy]] 

### Articles
Any file that *starts with* "Article", "article", "📜", or *contains* the word "article" (any case) will be moved to the `__Inbox` with the [[Article Template]] applied.
- *note*: you can remove the "any case" match across the whole title by removing this:
	- ` ||  tp.file.title.toUpperCase().includes("ARTICLE")`
### Books
Any file that *starts with* "Book", "book", "📚", or *contains* the word "book" (any case) will be moved to the `__Inbox` with the [[Book Template]] applied.
- *note*: you can remove the "any case" match across the whole title by removing this:
	- ` ||  tp.file.title.toUpperCase().includes("BOOK")`

### Podcasts
Any file that *starts with* "Podcast", "podcast", "🎙", or *contains* the word "podcast" (any case) will be moved to the `__Inbox` with the [[Podcast Template]] applied.
- *note*: you can remove the "any case" match across the whole title by removing this:
	- ` ||  tp.file.title.toUpperCase().includes("PODCAST")`

### Thoughts
Any file that *starts with* "Thought", "thought", "💭", or *contains* the word "thought" (any case) will be moved to the `__Inbox` with the [[Thought Template]] applied.
- *note*: you can remove the "any case" match across the whole title by removing this:
	- ` ||  tp.file.title.toUpperCase().includes("THOUGHT")`

### Videos
Any file that *starts with* "Video", "video", "🎥", or *contains* the word "video" (any case) will be moved to the `__Inbox` with the [[Video Template]] applied.
- *note*: you can remove the "any case" match across the whole title by removing this:
	- ` ||  tp.file.title.toUpperCase().includes("VIDEO")`