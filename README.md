# Netflix Content Analysis (2023)

## Dataset Overview

We used a dataset containing the following columns for all shows and movies released on Netflix in 2023:

- **Title**: The title of the show or movie
- **Release Date**: The release date of the content
- **Language**: The language of the content
- **Content Type**: Whether the content is a show or a movie
- **Availability Status**: Availability status of the content
- **Hours Viewed**: Total viewership hours for the content

## Data Cleaning

The `Hours Viewed` column was cleaned by removing commas and converting it to a float type to enable further analysis.

## Data Analysis 1: Top 5 Most-Viewed Content

The top 5 most-viewed Netflix titles in 2023 were:

1. **The Night Agent: Season 1** (English, Show) – 812.1 million hours viewed
2. **Ginny & Georgia: Season 2** (English, Show) – 665.1 million hours viewed
3. **King the Land: Limited Series** (Korean, Movie) – 630.2 million hours viewed
4. **The Glory: Season 1** (Korean, Show) – 622.8 million hours viewed
5. **ONE PIECE: Season 1** (English, Show) – 541.9 million hours viewed

While English-language shows dominate the top spots, the strong performance of Korean content highlights its growing global popularity.

## Data Analysis 2: Content Type Viewership Distribution

The analysis of total viewership hours between shows and movies revealed that shows have significantly more viewership than movies in 2023.

### Visualization:
![Content Type Viewership Distribution](https://github.com/ManuKashyap01/Netflix_Data_Analysis/blob/main/content_type_viewership_distribution.png)

*In 2023, people spent more time watching shows on Netflix than movies.*

## Data Analysis 3: Viewership by Language

The analysis showed that Netflix's viewership is heavily dominated by English-language content. However, non-English content, such as Korean shows and movies, also saw significant viewership, reflecting Netflix’s global appeal and diverse content strategy.

### Visualization:
![Viewership by Language](https://github.com/ManuKashyap01/Netflix_Data_Analysis/blob/main/viewership_by_language.png)  

*English-language content dominates, but Korean content shows growing popularity.*

## Data Analysis 4: Viewership by Release Month

The total viewership hours were analyzed by release month, highlighting key trends in viewership, such as a noticeable spike in June and a sharp rise in December. These spikes suggest that strategic content releases, seasonal trends, or the holiday season drive increased viewership during these months.

### Visualization:
![Viewership by Release Month](https://github.com/ManuKashyap01/Netflix_Data_Analysis/blob/main/viewership_by_release_month.png)  

*Viewership spikes in June and December, with steady engagement in other months.*

## Data Analysis 5: Viewership by Content Type and Release Month

This analysis compared viewership trends for shows and movies by release month. It shows that shows consistently outperform movies, with peaks in December, while movie viewership fluctuates, peaking in months like June and October.

### Visualization:
![Viewership by Content Type and Release Month](https://github.com/ManuKashyap01/Netflix_Data_Analysis/blob/main/viewership_by_content_and_release_month.png)  

*Shows maintain higher viewership, especially in December.*

## Data Analysis 6: Viewership and Release Distribution by Month

While the number of releases remained relatively steady, viewership experienced spikes in June and December. These increases are likely attributed to high-impact content and strategic timing, such as holiday season releases.

### Visualization:
![Viewership and Release Distribution by Month](https://github.com/ManuKashyap01/Netflix_Data_Analysis/blob/main/viewership_and_release_by_month.png)  

*Viewership spikes during June and December, despite steady content releases.*

## Data Analysis 7: Viewership and Release Distribution by Weekday

The release and viewership data by weekday shows that Netflix releases the majority of its content on Fridays, with viewership peaking on that day. This strategy likely aims to capture weekend viewers. Viewership tends to drop off on Saturdays and Sundays, as audiences consume content early in the weekend.

### Visualization:
![Viewership and Release Distribution by Weekday](https://github.com/ManuKashyap01/Netflix_Data_Analysis/blob/main/viewership_and_release_by_day.png)

*Most content is released on Fridays, capturing peak viewership before the weekend.*

## Conclusion

Netflix’s content strategy in 2023 focused on maximizing viewership by releasing shows more frequently than movies and timing releases around peak engagement periods. Shows consistently outperformed movies, with December and June showing notable viewership spikes, likely due to holiday season content. Most content was released on Fridays, aligning with increased weekend viewership. The steady number of releases suggests that Netflix emphasizes high-impact content and optimal timing rather than sheer volume of releases.
