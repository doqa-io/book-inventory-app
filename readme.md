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
Passed:1. You should have an h1 element with the text Book Inventory.
Passed:2. You should have only one h1 element.
Passed:3. You should have a table element.
Passed:4. You should have one thead element and one tbody element inside table.
Passed:5. Inside the thead there should be one tr with 5 th elements.
Passed:6. Your first column should have the text Title as the heading.
Passed:7. Your second column should have the text Author as the heading.
Passed:8. Your third column should have the text Category as the heading.
Passed:9. Your fourth column should have the text Status as the heading.
Passed:10. Your fifth column should have the text Rate as the heading.
Passed:11. Your table should have at least four rows.
Passed:12. Each row should always have 5 columns.
Passed:13. Each table row except the heading row should have either the class read, to-read, or in-progress.
Passed:14. td elements of the Status column should contain a span element.
Passed:15. Each span element of the Status column should have the class of status.
Passed:16. Each .status element should have the text Read, To Read, or In Progress, depending on the class of its row.
Passed:17. td elements of the Rate column should contain a span element.
Passed:18. Each span element which is a direct child of a td element of the Rate column should have the class of rate as the first class.
Passed:19. Each .rate element should contain three empty span elements.
Passed:20. .rate elements placed inside .read rows should have an additional class after the rate class with the value of either one, two, or three, depending on the personal rate.
Passed:21. You should have an attribute selector to target rows that have the class of read.
Passed:22. You should use an attribute selector to target rows that have the class of read and set their background-image property to a linear gradient of your choice.
Passed:23. You should have an attribute selector to target rows that have the class of to-read.
Passed:24. You should use an attribute selector to target rows that have the class of to-read and set their background-image property to a linear gradient of your choice.
Passed:25. You should have an attribute selector to target rows that have the class of in-progress.
Passed:26. You should use an attribute selector to target rows that have the class of in-progress and set their background-image property to a linear gradient of your choice.
Passed:27. You should set the display property of each span element to inline-block.
Passed:28. You should have an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of to-read.
Passed:29. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of to-read and set their border property.
Passed:30. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of to-read and set their background-image property.
Passed:31. You should have an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of read.
Passed:32. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of read and set their border property.
Passed:33. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of read and set their background-image property.
Passed:34. You should have an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of in-progress.
Passed:35. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of in-progress and set their border property.
Passed:36. You should use an attribute selector to target the span elements with the class of status that are descendants of tr elements with the class of in-progress and set their background-image property.
Passed:37. You should have an attribute selector to target the span elements with the class of status and the span elements with the class value starting with rate.
Passed:38. You should use an attribute selector to target the span elements with the class of status and the span elements with the class value starting with rate and set their height property.
Passed:39. You should use an attribute selector to target the span elements with the class of status and the span elements with the class value starting with rate and set their width property.
Passed:40. You should use an attribute selector to target the span elements with the class of status and the span elements with the class value starting with rate and set their padding property.
Passed:41. You should have an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate.
Passed:42. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their border property.
Passed:43. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their border-radius property.
Passed:44. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their margin property.
Passed:45. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their height property.
Passed:46. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their width property.
Passed:47. You should use an attribute selector to target the span elements which are direct children of span elements with the class value starting with rate and set their background-color property.
Passed:48. You should have an attribute selector to target the first descendant of span elements that have the word one as a part of their class value.
Passed:49. You should use an attribute selector to target the first descendant of span elements that have the word one as a part of their class value and set its background-image property to use a linear-gradient.
Failed:50. You should have an attribute selector to target the first two descendants of span elements that have the word two as a part of their class value.
Failed:51. You should use an attribute selector to target the first two descendants of span elements that have the word two as a part of their class value and set their background-image property to use a linear-gradient.
Passed:52. You should have an attribute selector to target the span elements that are descendants of span elements that have the word three as a part of their class value.
Passed:53. You should use an attribute selector to target the span elements that are descendants of span elements that have the word three as a part of their class value and set their background-image property to use a linear-gradient.