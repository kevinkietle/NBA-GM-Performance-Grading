NBA GM Performance Grading Project
==================================

A full project memo can be found [HERE](https://docs.google.com/document/d/1Obkl-_2tqnhVXmnmAHXaHeDJyw-jXJzJ/edit?usp=sharing&ouid=117233643725020281980&rtpof=true&sd=true).

This project evaluates NBA GM performance from 2022 to 2024, focusing on signings, trades, and draft picks. The timeframe is limited to ensure relevance, as many GMs were not with their current teams before 2022. Each category is graded individually, with scores combined into a holistic GM performance rating.

The analysis demonstrates key technical skills, including data scraping with Beautiful Soup, data cleaning, linear regression modeling with Scikit-Learn, and expected win share projections by draft slot.

### Project Structure

This repository includes five main components:

-   Data Scraping Scripts -- Scrapes win share data from Basketball Reference and compiles transaction datasets.

-   GM Signings Analysis -- Evaluates cost per win share for free-agent acquisitions.

-   GM Trades Analysis -- Assesses trade efficiency using a cost-per-win-share ratio.

-   GM Draft Pick Analysis -- Models expected win shares by draft slot to measure drafting success.

-   Holistic GM Performance Grading -- Combines all three categories into a single performance metric.

### Methodology & Key Insights

#### Signings

This section analyzes free-agent signings from 2022-2024, calculating cost per win share based on player contracts and subsequent performance. GM performance is then aggregated based on these values.

![Image](https://github.com/user-attachments/assets/1c05f269-1e5e-4769-909d-04497a634ecd)

#### Trades

This section calculates the ratio of incoming vs. outgoing win shares value in trades. A higher ratio indicates more efficient transactions by the GM.

![Image](https://github.com/user-attachments/assets/581421ee-178d-44a7-b246-57ce4b956420)

#### Draft Picks

To assess drafting success, we analyzed win shares for all draft picks since 2012 over their first three seasons. A linear regression model was used to estimate expected win shares per draft slot, which served as a benchmark for evaluating GMs' selections from 2022-2024.

-   2024 rookies: Compared to expected win shares for Year 1.

-   2023 rookies: Compared to expected two-year sum of win shares.

-   2022 rookies: Compared to expected three-year sum of win shares.

The primary metric is the percent change between actual and expected win shares, measuring how well GMs outperformed or underperformed draft expectations.

![Image](https://github.com/user-attachments/assets/f3619294-dd57-4a14-8086-336e8e4b52cb)

#### Holistic GM Performance

Final grades are determined by standardizing results using z-scores across all three categories. These are then summed to produce an overall GM performance ranking.

Notably, Sam Presti (OKC Thunder) ranked as the top-performing GM during this period.

![Image](https://github.com/user-attachments/assets/9aa26942-779e-4edc-b479-b3f1b937d5b5)

![Image](https://github.com/user-attachments/assets/32b26cb7-26a2-4352-adc0-5b133d7d4dfb)

* * * * *

### Contact & Additional Work

For questions or further discussion, feel free to reach out:

![📩](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdLJJ8672q8J1oM_8IQ39zVA-TDsMr1Udjua1J_Rw0hRMLHYh6K4vbd2VrbkH-a8Ptz1bWsJIv1aAm_tMFtJWUannauAB5VSgKbJ31mx6o5HhYrRDp2yKyH7jP4jK2USapsEA5RTw?key=WPuBJTkq44Y4mBjkSZAcUQ)  Email: kevinkietle@gmail.com\
![🔗](https://lh7-rt.googleusercontent.com/docsz/AD_4nXc_f6w_fHVuZhslvce_gFtqig19xQQ4g4Vqw78_VUUUdVm-vHJHWw1yoegTaFF8d508CEIsFTaOtNH_F3SkX-uWD2z2m_YtgPlkgCEwlcwbgEaJfTY8rmINnUBy_b2iIEeT-43Hvg?key=WPuBJTkq44Y4mBjkSZAcUQ)  LinkedIn:  [linkedin.com/in/kevinkietle/\
![📊](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeZUBcrPflFnnWMh1yg3rEP1vRy2ddsM1hocq12uRfm-9kNDmveM5X2HBJBPawwbKhspH8E8Hkah_JhPqpT-YEmzxeJaLJIk2Ibn_7TuzwQdB3ZHzgBg5FkD6fVWgfFwnMcCL-F?key=WPuBJTkq44Y4mBjkSZAcUQ)](https://www.linkedin.com/in/kevinkietle/)  Portfolio:  [kevinkietle.github.io/Bootstrap-Website-Portfolio/](https://kevinkietle.github.io/Bootstrap-Website-Portfolio/)