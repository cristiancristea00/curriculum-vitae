### <<entry.title>> ((* if entry.doi *))([<<entry.doi>>](<<entry.doi_url>>))((* elif entry.url *))([<<entry.url>>](<<entry.clean_url>>))((* endif *))

**<<entry.authors|join(", ")>>**

((* if entry.date_string *))
Acquired in **<<entry.date_string>>**
((* endif *))

((* if entry.journal *))
- <<entry.journal>>
((* endif *))
