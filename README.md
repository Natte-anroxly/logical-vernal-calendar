# 🌟 Great Logical Vernal Calendar

An astronomically-aligned calendar system for the Northern Hemisphere, based on the Vernal Equinox and a logical 13-month structure. This was a collaborative project between human creativity and AI implementation.

## 🌐 Live Website
**Experience the calendar converter here:**  
[https://natte-anroxly.github.io/logical-vernal-calendar/](https://natte-anroxly.github.io/logical-vernal-calendar/)

## 🗓️ How It Works
- **Epoch:** Year 1 began on the Vernal Equinox of 1583.
- **Structure:** 13 months of 28 days + Year Day (+ Leap Day in leap years).
- **New Year:** Starts on the day of the March Equinox.
- **Design Philosophy:** Harmony between astronomical symbolism and logical structure.
- **Hemisphere:** Designed for the Northern Hemisphere (Spring-based renewal).
- **Time Standard:** All calculations use Coordinated Universal Time (UTC).

## 📜 The 13 Months
1.  March
2.  April
3.  May
4.  June
5.  July
6.  August
7.  September
8.  October
9.  November
10. December
11. January
12. February
13. Sol

## 🚀 How to Use
1.  Open the [live website](https://natte-anroxly.github.io/logical-vernal-calendar/).
2.  Select any Gregorian date using the date picker.
3.  Click "Convert to Logical Vernal Date" to see its equivalent in the new calendar.
4.  The result shows the Logical Vernal date and its Gregorian year equivalent.

## 📊 Technical Notes & Design Philosophy

### Leap Year Rule
This calendar uses the **exact same leap year algorithm as the Gregorian calendar** to maintain long-term astronomical accuracy:
- A year is a leap year if it is exactly divisible by 4.
- Century years (e.g., 2100, 2200) are **not** leap years unless they are also exactly divisible by 400 (e.g., 2000 was a leap year).
- The extra day is added as **"Leap Day"** at the end of the year, following the standard **"Year Day"**.

### Astronomical Alignment (A Pragmatic Approach)
The calendar is designed to be **astronomically logical**, not astronomically perfect to the second.

-   **Equinox Date:** The start of the year (March 1) is determined by a simplified pattern where the equinox falls on **March 19** every 4 years (starting from 1588) and on **March 20** in other years. This pattern is accurate to within one day of the actual astronomical event.
-   **Why This Approach?** The goal was to create a calendar that is **easy to compute and understand** while maintaining a powerful symbolic connection to the Vernal Equinox. For all practical human purposes, this level of precision is sufficient. A hyper-precise calculation requiring complex astronomical formulae was deemed unnecessary for the calendar's philosophical goals.
-   **Long-Term Accuracy:** By inheriting the Gregorian leap year rules, this calendar shares the same excellent long-term accuracy, drifting by only about 1 day every 3,236 years.

This project prioritizes **logical elegance and symbolic meaning** alongside functional timekeeping.

## 🤝 Collaboration Credits
This project was created through a unique collaborative design process between:
-   **Original Idea & Design:** [Natte-anroxly](https://github.com/Natte-anroxly)
-   **AI System & Development:** [DeepSeek-V3](https://www.deepseek.com)

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
