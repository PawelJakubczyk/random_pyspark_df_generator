# random_pyspark_df_generator
PySpark and Faker generate a DataFrame with random records. CustomProvider extends Faker for data generation. generate_random_df uses a custom schema to create a PySpark DataFrame, achieving speed for a million records in 2 minutes, but faces RAM limitations beyond a few million records.
