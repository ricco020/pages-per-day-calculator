# Pages per day calculator

Free, single-file reading planner for one book or a whole stack. Enter the books and their page counts, the page you are on, your deadline, the days you read and your reading speed. It:

- spreads the pages left evenly over your reading days (rounded up, so you are never behind and the last day ends on the last page),
- gives the page to reach each reading day and the date you finish each book,
- converts it to minutes per day at your own speed,
- recalculates from today when you change the page you are on,
- exports the plan to your calendar (.ics, one all-day event per reading day) or a spreadsheet (CSV).

Use it online: https://ricco020.github.io/pages-per-day-calculator/

Checked on 300 random cases (1 to 6 books, any start page, 0 to 200 days, 1 to 7 reading weekdays, 16 838 reading days) against a separate Python implementation that walks the pages one by one: 0 difference. The .ics output parses with the Python `icalendar` library.

Printable version (books read with dates and rating, 52-book shelf to colour, quotes page, daily reading minutes log): https://tidysheets.shop/p/reading-log-printable

Runs fully in the browser, no tracking, no network calls. MIT licence.
