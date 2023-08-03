---
type: GCP Component 
share: true
creation date: <% tp.file.creation_date() %>
modification date: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
tags:
related:
---

<% await tp.file.move("/GCP/" + tp.file.selection()) %>
