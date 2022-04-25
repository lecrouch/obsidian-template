<%*    if (tp.file.title.startsWith("Article") || tp.file.title.startsWith("article") || tp.file.title.startsWith("📜") ||  tp.file.title.toUpperCase().includes("ARTICLE")) { %>
<%         tp.file.include("[[Article Template]]") %>
<%         await tp.file.move("__Inbox/" + tp.file.title) %>
<%*   } else if (tp.file.title.startsWith("Book") || tp.file.title.startsWith("book") || tp.file.title.startsWith("📚") ||  tp.file.title.toUpperCase().includes("BOOK")) { %>
<%         tp.file.include("[[Book Template]]") %>
<%         await tp.file.move("__Inbox/" + tp.file.title) %>
<%*   } else if (tp.file.title.startsWith("Podcast") || tp.file.title.startsWith("podcast") || tp.file.title.startsWith("🎙") ||  tp.file.title.toUpperCase().includes("PODCAST")) { %>
<%         tp.file.include("[[Podcast Template]]") %>
<%         await tp.file.move("__Inbox/" + tp.file.title) %>
<%*   } else if (tp.file.title.startsWith("Thought") || tp.file.title.startsWith("thought") || tp.file.title.startsWith("💭") ||  tp.file.title.toUpperCase().includes("THROUGHT")) { %>
<%         tp.file.include("[[Thought Template]]") %>
<%         await tp.file.move("__Inbox/" + tp.file.title) %>
<%*   } else if (tp.file.title.startsWith("Video") || tp.file.title.startsWith("video") || tp.file.title.startsWith("🎥") ||  tp.file.title.toUpperCase().includes("VIDEO")) { %>
<%         tp.file.include("[[Video Template]]") %>
<%         await tp.file.move("__Inbox/" + tp.file.title) %>
<%*   } else if (tp.file.title.startsWith("Habit")) { %>
<%         tp.file.include("[[Daily Habits]]") %>
<%         await tp.file.move("Daily Habits/" + tp.file.title) %>
<%*   } else { %>
              Unable to find a template match in [[_Auto Template]].
<%*   } %>