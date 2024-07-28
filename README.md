# Optimizing Uber/Lyft Driver Allocations in NYC with Graph Computing

**Project Duration:** October 2023 - December 2023

## Project Overview

This project aims to optimize driver allocations for Uber and Lyft in New York City by analyzing extensive trip data using graph computing techniques. By understanding ride patterns and key locations, we provide actionable insights for fleet optimization and dynamic driver allocation.

## Dataset

- **Source:** Uber/Lyft trip data
- **Size:** 745 million trips (19GB)

## Tools and Technologies

- **Big Data Processing:** PySpark
- **Cloud Platform:** Google Cloud Platform (GCP)
- **Graph Computing:** Implemented using PageRank algorithm

## Methodology

### Data Analysis

1. **Data Loading and Preprocessing:**
   - Loaded 745 million trip records into PySpark.
   - Preprocessed the data to ensure consistency and accuracy.

2. **Graph Construction:**
   - Constructed eight time-based graphs to capture different ride patterns throughout the day.
   - Nodes represent locations, and edges represent trip frequencies between locations.

### Graph Computing and Analysis

1. **PageRank Algorithm:**
   - Applied the PageRank algorithm to identify key locations in the network.
   - Focused on influential areas that attract high volumes of rides.

2. **Temporal Analysis:**
   - Analyzed the temporal distribution of rides to understand demand shifts.
   - Mapped ride patterns from Manhattan in the morning to Brooklyn in the evening.
   - Identified airports as consistent hubs of activity.

### Insights

1. **Demand Shifts:**
   - Highlighted significant demand shifts from Manhattan (AM) to Brooklyn (PM).
   - Provided visualizations showing these shifts.

2. **Service Comparison:**
   - Demonstrated that Uber has a broader geographic influence compared to Lyft.
   - Mapped influential locations for both services to highlight differences.

## Results

- **Key Locations:**
  - Identified and mapped key locations with high ride activity.
  - Provided insights into optimal driver placement to meet demand efficiently.

- **Dynamic Allocation:**
  - Offered recommendations for dynamic driver allocation based on temporal and spatial ride patterns.
  - Enhanced understanding of ride demand to improve fleet management.

## Conclusion

This project successfully leverages graph computing and big data analytics to optimize driver allocations for ride-sharing services in NYC. By identifying key locations and understanding demand shifts, we provide valuable insights for enhancing service efficiency and driver satisfaction.

## Future Work

- Extend analysis to include additional factors such as weather and events.
- Implement real-time data processing for dynamic, real-time driver allocation.
