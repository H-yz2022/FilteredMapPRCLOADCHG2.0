# FilteredMap new
(https://h-yz2022.github.io/FilteredMapPRCLOADCHG2.0/)


This map describes the projected changes in traffic volume on highways between 2035 and 2045, based on the SMRT model. Instead of showing the total change over the entire period, it focuses on incremental growth and decline, using percent change ranges to provide a more detailed analysis. The filters highlight different degrees of change in traffic load, from a significant decrease (below -1.0) to a major increase (greater than 1.0). By breaking down the data into 16 distinct ranges, the map provides a finer-grained analysis of how traffic loads are expected to evolve within this specific 10-year period, allowing users to identify areas with significant shifts, small changes, or no change at all. This granular filtering approach allows for a clear, interpretable visualization of specific change magnitudes, serving as an effective compromise between data detail and file size limitations, as it avoids a single, massive file by distributing the data across 16 smaller, more manageable GeoJSON files.

Filter 3: PRCLOADCHG -0.5 to -0.4

This is a moderate decrease, representing a drop of 40% to 50%. This level of change suggests a noticeable but not extreme reduction in traffic flow.
Filter 7: PRCLOADCHG -0.1 to 0

This range represents minimal to no decrease, showing traffic that is largely stable or has a negligible reduction. This is a common category for many segments that are not heavily impacted by the model's projections.

Filter 16: PRCLOADCHG > 1

This represents an extreme increase, with traffic volume more than doubling. These segments are a priority for further analysis as they indicate a critical projected change in the transportation network, possibly due to a major new road or interchange.
