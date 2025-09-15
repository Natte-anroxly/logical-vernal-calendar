# 🌟 Great Logical Vernal Calendar

An astronomically-aligned calendar system for the Northern Hemisphere, based on the Vernal Equinox and a logical 13-month structure. This was a collaborative project between human creativity and AI implementation.

## 🌐 Live Website
**Experience the calendar converter here:**  
[https://natte-anroxly.github.io/logical-vernal-calendar/](https://natte-anroxly.github.io/logical-vernal-calendar/)

*Last Updated: September 2025 | Version 7.0*

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
This calendar uses the **exact same leap year algorithm as the Gregorian calendar** to maintain long-term astronomical accuracy. The rule is implemented in code as:

```javascript
function isLeapYear(year) {
    return (year % 4 === 0 && (year % 100 !== 0 || year % 400 === 0));
}
