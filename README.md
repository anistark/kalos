# Project Kalos

_A 13-Month Open Source Calendar_

> Kalos is an open-source calendar system that rethinks the way we measure time. By dividing the year into 13 months of 28 days each, Kalos offers a consistent, predictable, and simplified alternative to the traditional 12-month Gregorian calendar.

## Structure:
  - **13 months × 28 days = 364 days per year**  
  - Each month comprises exactly 4 weeks, ensuring that every month starts on the same day of the week.
  
### Leap Year Adjustment:
  To account for the solar year of approximately 365.2422 days, Kalos introduces a leap adjustment:
  - A **leap day (or leap week)** is added approximately every 5 to 6 years.
  - Over long periods (e.g., 10,000 years), about **1,775 leap weeks** are required, averaging a leap week every **5.63 years**.
  - A practical rule might be to add a leap day every 5 years, with periodic adjustments (e.g., skipping a leap day every 30 years) to fine-tune alignment with the solar year.

## Benefits Over the Gregorian Calendar

### 1. Consistency
- **Every Month is the Same:**  
  Unlike the varying lengths (28–31 days) in the Gregorian calendar, every month in Kalos is identical.
  
- **Regular Start Days:**  
  The calendar’s uniformity ensures that scheduling is predictable and easier to manage.

### 2. Simplified Date Calculations
- **Uniformity Reduces Errors:**  
  With consistent month lengths, programmers and businesses alike can avoid common pitfalls in date arithmetic.
  
- **Streamlined Financial Calculations:**  
  Fixed month durations simplify interest computations, payroll cycles, and other financial operations.

### 3. Logical Year Structure
- **No More Odd Extra Days:**  
  The complete division into weeks (52 weeks exactly) avoids the irregular “extra” days found in the Gregorian calendar.
  
- **Easier Long-Term Planning:**  
  The leap week system is designed for a predictable adjustment over millennia, ensuring long-term alignment with the solar year.

### 4. Enhanced Productivity
- **Balanced Work-Life Cycles:**  
  The calendar’s regularity can contribute to more balanced scheduling for work, holidays, and vacations.
  
- **Improved Digital Scheduling:**  
  AI-driven tools and scheduling applications benefit from a consistent, fixed calendar system.

## Leap Year Calculation Details

### The Solar Year vs. Kalos Year
- **Solar Year:** Approximately 365.2422 days
- **Kalos Year:** 364 days

### Annual Shortfall and Accumulation
- **Difference per Year:** 365.2422 - 364 = 1.2422 days
- **Over 10,000 Years:**  1.2422 x 10,000 ≅ 12,422 days

### Leap Week Requirement
- **Each Leap Week Adds:** 7 days
- **Total Leap Weeks Needed:**  12,422 / 7 ≅ 1,775 leap weeks
- **Average Interval:** 10,000 / 1,775 ≅ 5.63 years

### Proposed Rule
- **Add a leap day every 5 years**, with periodic adjustments (e.g., skipping a leap day every 30 years) to maintain the alignment with the solar year.
- However, do not count this day in week. Make it a universal holiday as extra day. This keeps the balance with 7 day week throughout.

---

## License

Kalos is released under the [MIT License](LICENSE). You are free to use, modify, and distribute the calendar system under the terms of this license.

## Contact & Support

For any questions, suggestions, or support, please start a discussion or open an issue on our GitHub repository. Your feedback is vital to the ongoing development of Kalos.

> Kalos represents a bold step toward a more logical, consistent, and efficient way of keeping time. Let's reimagine the calendar to simplify our lives, both digitally and in our day-to-day planning!
