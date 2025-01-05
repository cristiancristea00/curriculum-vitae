## <<entry.institution>>

**((* if entry.degree *))<<entry.degree>> in ((* endif *))<<entry.area>>**

((* if entry.date_string *))**Period:** <<entry.date_string>>
((* endif *))

((* if entry.location *))**Location:** <<entry.location>>
((* endif *))

((* for item in entry.highlights *))
- <<item>>
((* endfor *))
