# 🌟 Great Logical Vernal Calendar

An astronomically-aligned calendar system for the Northern Hemisphere, based on the Vernal Equinox and a logical 13-month structure. This was a collaborative project between human creativity and AI implementation.

## 🌐 Live Website
**Experience the calendar converter here:**  
[https://natte-anroxly.github.io/logical-vernal-calendar/](https://natte-anroxly.github.io/logical-vernal-calendar/)

*Last Updated: September 2025 | Version 7.0*

## 🗓️ How It Works
- **Epoch:** Year 1 began on the Vernal Equinox of 1583
- **Structure:** 13 months of 28 days + Year Day (+ Leap Day in leap years)
- **New Year:** Starts on the day of the March Equinox
- **Design Philosophy:** Harmony between astronomical symbolism and logical structure
- **Hemisphere:** Designed for the Northern Hemisphere (Spring-based renewal)
- **Time Standard:** All calculations use Coordinated Universal Time (UTC)

## 📜 The 13 Months
1. March
2. April
3. May
4. June
5. July
6. August
7. September
8. October
9. November
10. December
11. January
12. February
13. Sol

## 🚀 How to Use
1. Open the [live website](https://natte-anroxly.github.io/logical-vernal-calendar/)
2. Select any Gregorian date using the date picker
3. Click "Convert to Logical Vernal Date" to see its equivalent in the new calendar
4. The result shows the Logical Vernal date and its Gregorian year equivalent

## 📊 Technical Notes & Design Philosophy

### Leap Year Rule
This calendar uses the **exact same leap year algorithm as the Gregorian calendar** to maintain long-term astronomical accuracy. The rule follows this logic:
- A year is a leap year if it is divisible by 4
- But not if it is divisible by 100
- Unless it is also divisible by 400

**This means:**
- Years like 2024 (divisible by 4) are leap years
- Century years like 2100 (divisible by 100 but not 400) are not leap years
- Years like 2000 (divisible by 400) are leap years
- The extra day is added as **"Leap Day"** at the end of the year, following the standard **"Year Day"**

### Astronomical Alignment (A Pragmatic Approach)
The calendar is designed to be **astronomically logical**, not astronomically perfect to the second.

- **Equinox Date Determination:** For practicality, the start of the year (March 1) is determined by a simplified pattern where the equinox is set to **March 19** every 4 years (starting from 1588) and to **March 20** in other years
- **Accuracy:** This pattern is within one day of the actual astronomical event for most years
- **Why This Approach?** We prioritize ease of use and symbolic meaning over nanosecond precision
- **Long-Term Accuracy:** Inherits the Gregorian calendar's excellent stability (~1 day drift every 3,236 years)

### Design Choices & Trade-offs
This project prioritizes **logical elegance and symbolic meaning** alongside functional timekeeping:

- **Precision vs. Practicality:** Accepts ~1-day variance for a simpler system
- **Hemispheric Focus:** Symbolically tied to Northern Hemisphere's spring
- **Fixed Rules:** Uses consistent rules rather than dynamic calculations
- **Mathematical Beauty:** 13 × 28 = 364 + 1 = 365 + 1 = 366 (perfect structure)

### Example Conversions
| Gregorian Date | Logical Vernal Date | Notes |
| :--- | :--- | :--- |
| March 20, 2025 | March 1, 443 | Start of a new year |
| February 28, 2024 | Sol 28, 442 | Last day of 13-month structure |
| March 18, 2024 | Year Day, 442 | Standard year-end day |
| March 19, 2024 | Leap Day, 442 | Extra day for leap year 2024 |

## 🤝 Collaboration Credits
This project was created through a unique collaborative design process between:
- **Original Idea & Design:** [Natte-anroxly](https://github.com/Natte-anroxly)
- **AI System & Development:** [DeepSeek-V3](https://www.deepseek.com)

**We welcome feedback and contributions!** Please open an issue for discussions.

## 📄 License
This project is open source and available under the [MIT License](LICENSE).

---
