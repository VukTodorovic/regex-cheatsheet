# Regex Cheatsheet

| Regex Expression | Explanation |
|------------------|-------------|
| `^`              | Matches the **start of a string** or line (depending on multiline mode). |
| `$`              | Matches the **end of a string** or line (depending on multiline mode). |
| `\s`             | Matches any **whitespace character** (spaces, tabs, newlines). |
| `\S`             | Matches any **non-whitespace character**. |
| `[\s\S]`         | Matches **any character**, including newlines (often used as a dot-all alternative). |
| `+`              | Matches **one or more** of the preceding token (greedy by default). |
| `*`              | Matches **zero or more** of the preceding token (greedy by default). |
| `\s*`            | Matches **zero or more whitespace characters**. |
| `[\s\S]+`        | Matches **one or more of any character**, including newlines. |
| `?+`             | Matches **zero or one** of the preceding token (in **possessive mode**, no backtracking). |
| `[\s\S]?+`       | Matches **zero or one of any character (including newline)**, but **possessive** (no backtracking). |
| `re.DOTALL`      | A Python regex **flag** that makes `.` match **all characters, including newlines**. Without it, `.` stops at line breaks. |
| `re.MULTILINE`   | A Python regex **flag** that makes `^` and `$` match at the **start and end of each line** (not just the whole string). |
