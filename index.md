# Unlocking Growth for Bellabeat: What Smart Device Data Reveals About Women's Wellness Habits

**Lumi Luka | Data Analyst**

---

## Executive Summary

Bellabeat stands at an inflection point. As a wellness technology company focused on women's health, the key to our next phase of growth lies in understanding how consumers actually use smart devices—not how we assume they do.

This analysis examined fitness tracker data from 33 users over one month to uncover actionable insights for Bellabeat's marketing strategy. **The findings reveal three critical opportunities:**

1. **41% of users lead sedentary or physically inactive lifestyles**—a segment hungry for motivation and guidance
2. **38% of users don't wear their devices consistently**—representing lost engagement and data
3. **Users are chronically sleep-deprived**—averaging under 7 hours on 6 of 7 weekdays

These insights point to a clear strategic direction: Bellabeat should position itself not just as a tracker, but as a **wellness coach** that actively helps women build healthier habits.

---

## The Business Question

Bellabeat's leadership posed a straightforward challenge: *How can we use smart device usage data to inform our marketing strategy and reveal growth opportunities?*

To answer this, I analyzed publicly available FitBit fitness tracker data—a competitor product serving a similar market to Bellabeat's Time and Leaf devices. The goal: understand real user behavior and translate those patterns into strategic recommendations.

---

## Key Findings

### Finding 1: Most Users Aren't as Active as They Think

When I categorized users by their average daily steps using [established health guidelines](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5488109/), a striking pattern emerged:

![User Activity Levels by Daily Steps](index_files/figure-gfm/unnamed-chunk-22-1.png)

**The breakdown:**
- **58% are moderately to very active** (7,500+ steps daily)
- **21% are physically inactive** (5,000-7,499 steps)
- **21% lead sedentary lifestyles** (under 5,000 steps)

**What this means for Bellabeat:** Over 40% of smart device users represent an underserved segment—people who bought fitness trackers but haven't achieved their activity goals. These users need more than data; they need guidance, motivation, and accountability.

---

### Finding 2: More Steps = More Calories Burned (And Users Need to See This)

The data confirms what seems obvious but is powerful when visualized:

![Correlation Between Daily Steps and Calories Burned](index_files/figure-gfm/unnamed-chunk-23-1.png)

This correlation between daily steps and calories burned is clear and motivating. **Users who take more steps burn significantly more calories.**

Similarly, total active minutes strongly correlate with calorie burn:

![Total Active Minutes vs Calories Burned](index_files/figure-gfm/unnamed-chunk-25-1.png)

**What this means for Bellabeat:** These correlations should be front and center in the app experience. Showing users the direct impact of their activity creates a feedback loop that encourages continued engagement.

---

### Finding 3: Users Have Predictable Activity Windows

When are users most active? The hourly step data reveals clear patterns:

![Hourly Steps Distribution](index_files/figure-gfm/unnamed-chunk-24-1.png)

**Peak activity occurs during:**
- **Midday (12pm - 2pm)** — likely lunch breaks
- **Early evening (5pm - 7pm)** — post-work exercise

**What this means for Bellabeat:** Notification timing matters. Sending motivation or reminders during low-activity hours (morning, late evening) could help users add steps when they typically don't.

---

### Finding 4: Device Engagement Is a Major Challenge

Perhaps the most concerning finding: **38% of users don't use their devices frequently.**

![Device Usage Frequency](index_files/figure-gfm/unnamed-chunk-26-1.png)

Even among those who do wear their devices, many don't keep them on all day:

![Daily Wear Duration](index_files/figure-gfm/unnamed-chunk-27-1.png)

**What this means for Bellabeat:** Abandoned devices represent lost customers. The industry average shows significant drop-off in wearable usage after purchase. Bellabeat has an opportunity to differentiate by creating compelling reasons to keep the device on—whether through better comfort, longer battery life, or features that only work with continuous wear.

---

### Finding 5: Users Are Sleep-Deprived

The [CDC recommends](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4434546/) adults aged 18-60 get at least 7 hours of sleep per night. Our users fall short nearly every day of the week:

![Weekly Activity and Sleep Patterns](index_files/figure-gfm/unnamed-chunk-28-1.png)

![Average Sleep Hours by Day of Week](index_files/figure-gfm/unnamed-chunk-28-2.png)

**Only Wednesday averages over 7 hours of sleep.** The rest of the week, users are chronically under-rested.

**What this means for Bellabeat:** Sleep is a massive, underserved opportunity. Women juggling work, family, and personal wellness often sacrifice sleep first. A product that actively helps users protect their sleep—not just track it—could be transformative.

---

## Strategic Recommendations

Based on these findings, I recommend Bellabeat pursue four strategic initiatives:

### 1. Become a Sleep Coach, Not Just a Sleep Tracker

Users aren't getting enough sleep, and they know it. Bellabeat should introduce:
- **Personalized bedtime reminders** based on wake-up time and sleep goals
- **Weekly sleep reports** with actionable suggestions
- **Wind-down routines** triggered by the device (dim lights, play calming sounds via app integration)

### 2. Gamify Consistency to Combat Device Abandonment

38% device abandonment is a churn problem. Combat it with:
- **Streak rewards** for consecutive days of wear
- **Milestone celebrations** for total hours tracked
- **Gentle re-engagement nudges** when devices go inactive

### 3. Time Notifications for Maximum Impact

Instead of random reminders, leverage the activity data:
- **Morning motivation** before the typical sedentary period
- **Midday encouragement** when users are naturally active
- **Evening wind-down prompts** as activity decreases

### 4. Target the Sedentary Segment in Marketing

41% of users are underactive despite owning fitness trackers. Our marketing should speak directly to them:
- *"Not a gym person? Neither are we."*
- Emphasize wellness over fitness, lifestyle over performance
- Highlight features for busy women who want to be healthier without overhauling their lives

---

## Data Limitations

This analysis has important constraints to acknowledge:

- **Small sample size:** 33 users, limiting generalizability
- **Data age:** Collected in 2016; habits may have evolved
- **No demographics:** Unable to confirm if users match Bellabeat's target market of women
- **Self-selected participants:** May not represent typical consumer behavior

For more robust insights, I recommend Bellabeat conduct primary research with its own user base.

---

## Conclusion

Smart device users want to be healthier—that's why they bought the device. But the data shows many are struggling: too sedentary, too sleep-deprived, and inconsistent with device usage.

Bellabeat's opportunity isn't to be another tracker. **It's to be the wellness partner that helps women bridge the gap between intention and action.**

The technology exists. The user need is clear. The market is waiting.

---

*Analysis conducted using R with tidyverse and ggplot2*  
*Data source: [Kaggle FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit)*
