Objective: Fulfill the user stories below and get all the tests to pass to complete the lab.

User Stories:

You should have an h1 element with the text Book Inventory.
You should have a table element with columns named Title, Author, Category, Status, and Rate.
Your table should have at least four rows, the first for the column headings and the rest filled with book information.
Each table row inside the table body should have either the class read, to-read, or in-progress.
td elements of the Status column should contain a span element with the class of status surrounding the text Read, To Read, or In Progress, depending on the class of that row.
td elements of the Rate column should contain a span element with the class of rate wrapping three empty span elements.
.rate elements placed inside .read rows should have an additional class with the value of either one, two, or three, depending on the personal rate. This value should come after rate.
You should create three attribute selectors to target the elements with the class of read, to-read, and in-progress, and set their background-image property to use a linear-gradient of your choice.
You should set the display property of each span element to inline-block.
You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of to-read and set their border and background-image properties.
You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of read and set their border and background-image properties.
You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of in-progress and set their border and background-image properties.
You should use an attribute selector to target the span elements with the class of status and the span elements with the class value starting with rate and set their height, width, and padding properties.
You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their border, border-radius, margin, height, width, and background-color properties.
You should use an attribute selector to target the first descendant of span elements that have the word one as a part of their class value and set its background-image property to use a linear-gradient.
You should use an attribute selector to target the first two descendants of span elements that have the word two as a part of their class value and set their background-image property to use a linear-gradient.
You should use an attribute selector to target the three span elements that are descendants of span elements that have the word three as a part of their class value and set their background-image property to use a linear-gradient.

Tests
1. You should have an h1 element with the text Book Inventory.
2. You should have only one h1 element.
3. You should have a table element.
4. You should have one thead element and one tbody element inside table.
5. Inside the thead there should be one tr with 5 th elements.
6. Your first column should have the text Title as the heading.
7. Your second column should have the text Author as the heading.
8. Your third column should have the text Category as the heading.
9. Your fourth column should have the text Status as the heading.
10. Your fifth column should have the text Rate as the heading.
11. Your table should have at least four rows.
12. Each row should always have 5 columns.
13. Each table row except the heading row should have either the class read, to-read, or in-progress.
14. td elements of the Status column should contain a span element.
15. Each span element of the Status column should have the class of status.
16. Each .status element should have the text Read, To Read, or In Progress, depending on the class of its row.
17. td elements of the Rate column should contain a span element.
18. Each span element which is a direct child of a td element of the Rate column should have the class of rate as the first class.
19. Each .rate element should contain three empty span elements.
20. .rate elements placed inside .read rows should have an additional class after the rate class with the value of either one, two, or three, depending on the personal rate.
21. You should have an attribute selector to target rows that have the class of read.
22. You should use an attribute selector to target rows that have the class of read and set their background-image property to a linear gradient of your choice.
23. You should have an attribute selector to target rows that have the class of to-read.
24. You should use an attribute selector to target rows that have the class of to-read and set their background-image property to a linear gradient of your choice.
25. You should have an attribute selector to target rows that have the class of in-progress.
26. You should use an attribute selector to target rows that have the class of in-progress and set their background-image property to a linear gradient of your choice.
27. You should set the display property of each span element to inline-block.
28. You should have an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of to-read.
29. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of to-read and set their border property.
30. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of to-read and set their background-image property.
31. You should have an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of read.
32. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of read and set their border property.
33. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of read and set their background-image property.
34. You should have an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of in-progress.
35. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of in-progress and set their border property.
36. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of in-progress and set their background-image property.
37. You should have an attribute selector to target the span elements with the class of status and the span elements with the class value starting with rate.
38. You should use an attribute selector to target the span elements with the class of status and the span elements with the class value starting with rate and set their height property.
39. You should use an attribute selector to target the span elements with the class of status and the span elements with the class value starting with rate and set their width property.
40. You should use an attribute selector to target the span elements with the class of status and the span elements with the class value starting with rate and set their padding property.
41. You should have an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate.
42. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their border property.
43. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their border-radius property.
44. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their margin property.
45. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their height property.
46. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their width property.
47. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their background-color property.
48. You should have an attribute selector to target the first descendant of span elements that have the word one as a part of their class value.
49. You should use an attribute selector to target the first descendant of span elements that have the word one as a part of their class value and set its background-image property to use a linear-gradient.
Failed:50. You should have an attribute selector to target the first two descendants of span elements that have the word two as a part of their class value.
Failed:51. You should use an attribute selector to target the first two descendants of span elements that have the word two as a part of their class value and set their background-image property to use a linear-gradient.
52. You should have an attribute selector to target the span elements that are descendants of span elements that have the word three as a part of their class value.
53. You should use an attribute selector to target the span elements that are descendants of span elements that have the word three as a part of their class value and set their background-image property to use a linear-gradient.