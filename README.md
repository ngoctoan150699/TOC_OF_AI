# TOC_OF_AI
Bookmarklet: Conversation TOC (Table of Contents)
This JavaScript bookmarklet adds a collapsible, resizable sidebar to a Grok or ChatGPT conversation page that displays a Table of Contents (TOC) of the conversation turns. Each entry shows:

The turn number

Whether it was from Grok (bot) or You

A summary of the first part of the message (up to a certain length)

Main Features:
📌 Sidebar Panel (#toc-panel): Fixed on the right side of the screen, shows all the conversation turns in a list format.

🎛️ Controls:

"↑" and "↓" buttons to increase/decrease the summary length of each message.

🧠 Smart Detection: Works with both Grok and ChatGPT message layouts using common class name patterns.

🖱️ Clickable Entries: Clicking an item scrolls smoothly to that message in the conversation.

🎨 Dark Mode Compatible: Adapts to light/dark themes using prefers-color-scheme.

🪟 Collapsible Handle (#toc-handle): A vertical "TOC" tab on the side that toggles the panel in and out.

🔄 Auto-refresh: Automatically watches for new messages via MutationObserver, updating the TOC every time something changes.

Credits
Based on original idea/code from Brostoffed on GitHub Gist https://gist.github.com/Brostoffed
