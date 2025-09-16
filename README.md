# 🌟 Great Logical Vernal Calendar

An innovative calendar system offering multiple modes to respect astronomical and cultural differences across Earth. Features a logical 13-month structure and was a collaborative project between human creativity and AI implementation.

## 🌐 Live Website
**Experience the calendar converter here:**
[https://natte-anroxly.github.io/logical-vernal-calendar/](https://natte-anroxly.github.io/logical-vernal-calendar/)

## 🗓️ How It Works
- **Epoch:** Year 1 began on the Vernal Equinox of 1583 (Northern Mode).
- **Structure:** 13 months of 28 days + Year Day (+ Leap Day in leap years).
- **Design Philosophy:** Harmony between astronomical symbolism, logical structure, and global inclusivity.
- **Time Standard:** All calculations use Coordinated Universal Time (UTC).

## 🌍 About The Modes

The calendar operates in three distinct modes, allowing users to choose a New Year that aligns with their astronomical or cultural perspective.

### Northern Mode (Default)
- **New Year Start:** Vernal Equinox (approx. March 19-20).
- **Hemisphere Focus:** Designed for the Northern Hemisphere, symbolizing Spring-based renewal and rebirth.

### Southern Mode
- **New Year Start:** Autumnal Equinox (approx. Sep 22-23).
- **Hemisphere Focus:** Designed for the Southern Hemisphere, aligning its New Year with the beginning of Spring in the south.

### Universal Mode (Sidereal)
- **New Year Start:** Fixed on Sidereal Aries (April 14).
- **Philosophy:** Offers a stable, non-moving anchor point for the year, independent of the shifting equinoxes. It represents a universal constant.

## 📜 The 13 Months
The month names are consistent across all modes.
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

### Leap Year Rule (Consistent Across All Modes)
This calendar uses the **exact same leap year algorithm as the Gregorian calendar** to maintain synchronization and long-term accuracy:
- A year is a leap year if it is exactly divisible by 4.
- Century years (e.g., 2100, 2200) are **not** leap years unless they are also exactly divisible by 400 (e.g., 2000 was a leap year).
- The extra day is added as **"Leap Day"** at the end of the year, following the standard **"Year Day"**.

### Special Note for Universal Mode

#### April 14th Meaning & Leap Year Handling
In Universal Mode, the fixed date of April 14th serves as the anchor for the New Year. To maintain perfect synchronization with the Gregorian calendar, a unique rule is applied in leap years:
- **In a leap year, April 14th serves a dual purpose:**
  - It is **Leap Day** (the final day of the old year).
  - It is **also March 1** (the first day of the new year).

#### Why This Works
This elegant solution maintains the simple April 14th anchor while inheriting the proven leap year rules of the Gregorian system, ensuring perfect long-term sync.

**Example from leap year 2024:**
- `April 13, 2024 (Gregorian)` = **Leap Day, 441**
- `April 14, 2024 (Gregorian)` = **March 1, 442**

### Astronomical Alignment (A Pragmatic Approach)
The calendar is designed to be **astronomically logical**, not astronomically perfect to the second.

-   **Equinox Date (Northern/Southern Modes):** The start of the year is determined by a simplified pattern where the equinox falls on **March 19** every 4 years and on **March 20** in other years. This pattern is accurate to within one day of the actual astronomical event.
-   **Why This Approach?** The goal was to create a calendar that is **easy to compute and understand** while maintaining a powerful symbolic connection to the equinoxes. For all practical human purposes, this level of precision is sufficient.
-   **Long-Term Accuracy:** By inheriting the Gregorian leap year rules, this calendar shares the same excellent long-term accuracy.

This project prioritizes **logical elegance, symbolic meaning, and global inclusivity** alongside functional timekeeping.

## 🤝 Collaboration Credits
This project was created through a unique collaborative design process between:
-   **Original Idea & Design:** [Natte-anroxly](https://github.com/Natte-anroxly)
-   **AI System & Development:** [DeepSeek-V3](https://www.deepseek.com)

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
