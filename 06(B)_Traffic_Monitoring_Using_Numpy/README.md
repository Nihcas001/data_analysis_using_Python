Problem statement

A traffic monitoring system wants to identify high-density traffic regions. Use NumPy aggregations, masking, Boolean operations, and fancy indexing for traffic datasets.

1. Understanding the Problem

Imagine a city has several traffic monitoring locations:

    Main Market
    Bus Stand
    Railway Station
    University Road
    Industrial Area
    Airport Road
    Hospital Road
    Mall Road
    Highway Junction
    Court Road

Sensors record:

    Number of vehicles
    Average speed
    Number of cars
    Number of buses
    Number of trucks
    Number of two-wheelers

Our goal is to answer questions such as:

    Which locations have heavy traffic?
    Which regions have more than 1,000 vehicles?
    Which regions have low average speed?
    Which locations have both high vehicle count and low speed?
    What is the average traffic volume?
    Which are the top 5 most congested regions

This is exactly where NumPy's masking, Boolean operations, aggregation and fancy indexing become useful.

2. NumPy Concepts We Will Cover

| No. | Concept              | Application                 |              |
| --- | -------------------- | --------------------------- | ------------ |
| 1   | NumPy array creation | Store traffic data          |              |
| 2   | `ndim`               | Dimensions                  |              |
| 3   | `shape`              | Rows × columns              |              |
| 4   | `size`               | Number of observations      |              |
| 5   | Indexing             | Access particular region    |              |
| 6   | Slicing              | Select regions              |              |
| 7   | `sum()`              | Total vehicles              |              |
| 8   | `mean()`             | Average traffic             |              |
| 9   | `min()` / `max()`    | Minimum/maximum traffic     |              |
| 10  | `std()`              | Traffic variation           |              |
| 11  | `axis`               | Row/column aggregation      |              |
| 12  | Boolean conditions   | Identify traffic conditions |              |
| 13  | Masking              | Filter traffic data         |              |
| 14  | `&`                  | AND condition               |              |
| 15  | `                    | `                           | OR condition |
| 16  | `~`                  | NOT condition               |              |
| 17  | Fancy indexing       | Select specific rows        |              |
| 18  | `argmax()`           | Most congested region       |              |
| 19  | `argsort()`          | Ranking regions             |              |
| 20  | `where()`            | Traffic classification      |              |
| 21  | Combining masks      | Complex filtering           |              |

3. DATASET

| Region | Vehicles | Avg Speed | Cars | Buses | Trucks | Two-Wheelers |
| ------ | -------: | --------: | ---: | ----: | -----: | -----------: |
| 101    |      850 |        42 |  400 |    80 |     70 |          300 |
| 102    |     1250 |        28 |  600 |   120 |    100 |          430 |
| 103    |      650 |        48 |  300 |    50 |     40 |          260 |
| 104    |     1450 |        22 |  700 |   150 |    120 |          480 |
| 105    |      920 |        35 |  450 |    90 |     60 |          320 |
| 106    |     1180 |        30 |  570 |   110 |     90 |          410 |
| 107    |      540 |        52 |  250 |    40 |     30 |          220 |
| 108    |     1600 |        20 |  800 |   180 |    140 |          480 |
| 109    |      980 |        38 |  480 |    85 |     65 |          350 |
| 110    |     1720 |        18 |  850 |   200 |    160 |          510 |
| 111    |      720 |        45 |  350 |    60 |     45 |          265 |
| 112    |     1320 |        25 |  650 |   130 |    110 |          430 |
| 113    |      880 |        40 |  420 |    75 |     55 |          330 |
| 114    |     1500 |        21 |  750 |   160 |    130 |          460 |
| 115    |     1100 |        32 |  530 |   100 |     80 |          390 |

45. Complete Question Set for Students

Now that the concepts are covered, you can give students these questions.

Part A — Array Creation & Properties

    Import NumPy.
    Create the traffic dataset.
    Display the complete array.
    Find the number of dimensions.
    Find the shape.
    Find the total number of elements.
    Find the data type.

Part B — Indexing & Slicing

    Display the first region.
    Display the first region's vehicle count.
    Display the 10th region's average speed.
    Display the last region.
    Extract all region IDs.
    Extract all vehicle counts.
    Extract all average speeds.
    Display the first five regions.
    Display the last five regions.

Part C — Aggregations

    Find total vehicles.
    Find average traffic volume.
    Find minimum traffic.
    Find maximum traffic.
    Find median traffic.
    Find standard deviation.
    Find total cars.
    Find total buses.
    Find total trucks.
    Find total two-wheelers.
    Calculate column-wise averages.

Part D — Masking

    Find regions with more than 1,000 vehicles.
    Find regions with average speed below 30 km/h.
    Find regions with more than 1,200 vehicles.
    Count high-density regions.
    Find IDs of high-density regions.
    Find regions with more than 100 trucks.
    Find regions with more than 400 two-wheelers.

Part E — Boolean Operations

    Find regions with vehicles > 1,000 AND speed < 30.
    Find regions with vehicles > 1,500 OR speed < 20.
    Find regions with vehicles > 1,200 AND trucks > 100.
    Find regions where two-wheelers > cars.
    Find regions that are NOT high-density.
    Find severely congested regions using three conditions.

Part F — Fancy Indexing

    Select regions at positions [1, 4, 9, 13].
    Select only columns [0, 1, 2].
    Select specific regions and specific columns together.
    Find the top 5 traffic regions using argsort().
    Find the most congested region using argmax().
    Find the least busy region using argmin().

Part G — Advanced Analysis

    Classify regions as Low, Medium and High traffic.
    Calculate percentage of high-density regions.
    Calculate average speed of high-density regions.
    Calculate average traffic of congested regions.
    Calculate car percentage for every region.
    Calculate bus percentage.
    Calculate two-wheeler percentage.
    Calculate a congestion score.
    Find the region with the highest congestion score.

