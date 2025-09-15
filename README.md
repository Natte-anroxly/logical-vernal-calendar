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
```

· This means years like 2024 (divisible by 4) are leap years.
· Century years like 2100 (divisible by 100 but not by 400) are not leap years.
· The extra day is added as "Leap Day" at the end of the year, following the standard "Year Day".

Astronomical Alignment (A Pragmatic Approach)

The calendar is designed to be astronomically logical, not astronomically perfect to the second.

· Equinox Date Determination: For practicality, the start of the year (March 1) is determined by a simplified, rule-based pattern where the equinox is set to March 19 every 4 years (starting from 1588) and to March 20 in other years. This pattern is accurate to within one day of the actual astronomical event for the vast majority of years.
· Why This Approach? The goal was to create a calendar that is easy to compute, understand, and use while maintaining a powerful symbolic connection to the Vernal Equinox. A hyper-precise calculation requiring complex astronomical formulae was deemed unnecessary for the calendar's philosophical goals. This is a conscious design choice favoring elegance and simplicity over nanosecond precision.
· Long-Term Accuracy: By inheriting the Gregorian leap year rules, this calendar shares the same excellent long-term accuracy, drifting by only about 1 day every 3,236 years.

Design Choices & Trade-offs

This project prioritizes logical elegance and symbolic meaning alongside functional timekeeping. Key trade-offs include:

· Precision vs. Practicality: We accept a potential ~1-day variance from the true equinox for a vastly simpler system.
· Hemispheric Focus: The calendar is symbolically tied to the Northern Hemisphere's spring. A future version could offer a Southern Hemisphere mode.
· Fixed Rules vs. Dynamic Calculation: The rule-based equinox is fixed for clarity, not dynamically calculated each year.

Example Conversions

Gregorian Date Logical Vernal Date Notes
March 20, 2025 March 1, 444 Start of a new year (common equinox date)
February 28, 2024 Sol 28, 443 Last day of the 13-month structure
March 18, 2024 Year Day, 443 Standard year-end day
March 19, 2024 Leap Day, 443 Extra day added for leap year 2024

🤝 Collaboration Credits

This project was created through a unique collaborative design process between:

· Original Idea & Design: Natte-anroxly
· AI System & Development: DeepSeek-V3

We welcome feedback and contributions! Please open an issue for discussions.

📄 License

This project is open source and available under the MIT License.

