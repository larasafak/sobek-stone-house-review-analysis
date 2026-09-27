# Sobek Stone House: Guest Review Analysis

I analysed guest reviews of Sobek Stone House Cappadocia to understand
how satisfaction changed over time, what guests praised or criticised,
and which service issues the hotel should prioritise.

## At a glance

- **Period:** 2020 to September 2026
- **Sources:** Google, Tripadvisor, Booking.com, Expedia and Trip.com
- **Reviews collected:** 966
- **Unique reviews analysed:** 919
- **Tools:** Python, pandas, data visualisation, machine translation,
  RoBERTa sentiment analysis and keyword-based topic analysis

## What I did

I combined reviews from five platforms, standardised ratings to a
five-point scale and removed duplicate reviews. I translated
non-English comments, analysed sentiment in reviews and sentences,
identified recurring service topics, and compared ratings and
complaints over time.

## Key findings

- The overall average rating was **4.62/5**.
- The average fell from **4.84 in 2020–2022** to **4.45 in
  2023–2026**.
- Pricing and payment complaints became more prominent in later
  reviews.
- The view and location remained consistent strengths.

The analysis identifies patterns in guest feedback. It does not
establish that any single issue caused the rating decline.

## Recommendations

I prioritised clearer pricing and payment information, improvements
to room quality and pool maintenance, more consistent food and drink
service, and better responses to guest reviews. The notebook contains
the detailed analysis, charts and recommendations.

## View the analysis

Open [SobekStoneHouse_Reviews.ipynb](SobekStoneHouse_Reviews.ipynb)
to explore the code, results and visualisations.

## Data availability

The raw review exports are not published in this repository. The
notebook includes saved results, but rerunning the full analysis
requires the source CSV files from the five platforms in a `data/`
folder.

## Limitations

Guest reviews are not a random sample of all guests. Some platforms
have relatively few reviews, translations and keyword-based topic
labels may be imperfect, and 2026 includes reviews only through
September.
