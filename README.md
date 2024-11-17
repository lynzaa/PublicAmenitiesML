**Optimizing Public Amenities in the City of Melbourne**

**Authored by**: Liny Jose Alias

**Duration**: 90 mins

**Level**: Intermediate

**Pre-requisite Skills**: Python, Data Visualization, Data Wrangling, Machine Learning Models,Deep Learning

**Scenario**
As a regular pedestrian, I would like to know the location of public amenities like the nearest drinking fountain and public toilets in the city of Melbourne.

***Project Objective, Overview & Research***

This usecase aims  to optimize the allocation and availability of public amenities in the City of Melbourne, focusing on public toilets and drinking fountains. Using pedestrian traffic data from the Pedestrian Counting System, the aim is to identify high-demand areas that lack sufficient public amenities and suggest new locations for improvements. This project will assist city planners in ensuring that services are equitably distributed and aligned with public needs.

**Dataset 1:**
https://data.melbourne.vic.gov.au/explore/dataset/drinking-fountains/information/
This dataset holds the description, type and geographical location of all drinking fountains in the City of Melbourne

**Dataset 2:**
https://data.melbourne.vic.gov.au/explore/dataset/public-toilets/information/
Public toilets known about or operated by the council. 

**Dataset 3:**
https://data.melbourne.vic.gov.au/explore/dataset/pedestrian-counting-system-monthly-counts-per-hour/information/
This dataset contains hourly pedestrian counts since 2009 from pedestrian sensor devices located across the city. The data is updated on a monthly basis and can be used to determine variations in pedestrian activity throughout the day.

## Executive Summary

This project presents the findings of a data-driven analysis to identify optimal locations for new public amenities (toilets and drinking fountains) in Melbourne. By analyzing pedestrian traffic data and the current distribution of existing amenities, we have identified nine high-priority locations that would benefit from new public facilities.

## Key Findings

1. **High-Traffic Areas**: Our analysis revealed several high-foot-traffic areas that are currently underserved by public amenities. The top location (near Swa31) sees an average daily foot traffic of 1,643 pedestrians.

2. **Amenity Gaps**: Despite the presence of existing facilities, we identified areas where the distance to the nearest toilet or drinking fountain is significant, indicating potential gaps in amenity coverage.

3. **Priority Locations**: The analysis highlighted nine specific locations that should be prioritized for new amenities, based on a combination of high foot traffic and distance from existing facilities.

## Detailed Recommendations

Based on our analysis, we recommend considering the following locations for new public amenities, listed in order of priority:

1. **Near Swa31** (-37.816686, 144.966897)
   - Highest foot traffic (1,643 daily average)
   - Moderate distance to existing amenities (146m to nearest toilet, 118m to nearest fountain)

2. **Near Swa295_T** (-37.811015, 144.964295)
   - High foot traffic (823 daily average)
   - Relatively far from nearest toilet (259m)

3. **Near PriNW_T** (-37.818742, 144.967877)
   - Significant foot traffic (766 daily average)
   - Moderate distances to existing amenities

4. **Near Col620_T** (-37.818880, 144.954492)
   - High foot traffic (730 daily average)
   - Farthest from existing toilets among top locations (330m)

5. **Near MCEC_T** (-37.824018, 144.956044)
   - Consistent high foot traffic (655 daily average)
   - Balanced distances to both toilets and fountains

The remaining four locations (near VAC_T, Spen229_T, Hammer1584_T, and Bou688_T) also show significant need for new amenities, with daily foot traffic ranging from 497 to 648 pedestrians.

## Implementation Considerations

1. **Type of Amenity**: For each location, consider whether a toilet, a drinking fountain, or a combined facility would be most appropriate based on the specific distances to existing amenities.

2. **Accessibility**: Ensure that any new facilities are accessible to all, including those with disabilities.

3. **Environmental Impact**: Consider sustainable and eco-friendly designs for new amenities to align with Melbourne's environmental goals.

4. **Public Feedback**: Before finalizing locations, it may be beneficial to gather public input, especially from frequent users of these high-traffic areas.

5. **Budget Allocation**: Prioritize the top locations if budget constraints prevent implementing all recommendations simultaneously.

## Long-Term Strategy

1. **Regular Updates**: Conduct this analysis periodically (e.g., annually) to account for changes in pedestrian patterns and new developments in the city.

2. **Expand Analysis**: Consider incorporating additional data sources such as tourist hotspots, event locations, or demographic information to further refine recommendations.

3. **Performance Monitoring**: After implementing new amenities, monitor their usage and impact on pedestrian satisfaction to inform future decision-making.

## Conclusion

This data-driven approach has identified specific, high-impact locations for new public amenities in Melbourne. By addressing these gaps in amenity coverage, the city can significantly improve the urban experience for pedestrians, potentially increasing foot traffic and enhancing the overall livability of these areas. I recommend using this analysis as a starting point for a targeted expansion of public amenities, always in conjunction with on-the-ground assessments and community feedback.

