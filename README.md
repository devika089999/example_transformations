# example_transformations

Pyspark_ Transformations 

SparkSession/SparkContext – Created using SparkSession.builder.
Load & Preview – Used read.csv() with .show() or .count() to inspect.
Clean – Applied dropDuplicates(), dropna(), and filter(quantity > 0).
Enrich – Used withColumn() to add order_value, year, month, day.
Country Revenue – Grouped by country, aggregated total sales.
Top Customer – Used window function row_number() by country.
Region Join – Joined with country_region.csv, grouped by region.
Monthly Category Pivot – Used groupBy() + pivot() on month/category.
Price Band – Used when() with multiple conditions and groupBy().
Partition Tuning – Used .rdd.getNumPartitions() + repartition().
Cache vs Recompute – Cached intermediate DataFrame and timed .count().