# powerbi-dax-calendar
<em>This DAX statement generates a calendar table for use in Power BI or another SSAS oriented data model.</em>
<br><br>Columns labeled BC refer to "Broadcast Calendar" which is a weekly calendar scheme used in the television and radio broadcast industry for advertising and ratings, following these rules:
- Each week begins on Monday and ends on Sunday
- Each week belongs to a the month in which the Sunday of the week falls. For example, the week ending Sunday, January 1, 2023 belongs to the month of January. A broadcast month consists of either four or five weeks.
- Each week belongs to a year which is baed on the calendar year in which the Sunday of the week falls. For example, the week ending Sunday, January 1, 2023 belongs to the year 2023. A broadcast year consists of either 52 or 53 weeks.
- NOTE: The week-based broadcast calendar is different from the week-based ISO calendar defined by ISO 8601 and used in many other industries (The ISO week belongs to the the Month and Year where the Wednesday of that week lands)
