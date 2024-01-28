PySpark and Faker generate a DataFrame with random records. CustomProvider extends Faker for data generation. The notebook contains two functions: generate_random_df and generate_random_df_large_data.
generate_random_df utilizes a custom schema to create a PySpark DataFrame, achieving high speed for data generation. However, it may encounter RAM limitations beyond a few million records, making it suitable for generating hundreds of thousands of records depending on the data.
On the other hand, generate_random_df_large_data is not constrained by RAM limitations but is noticeably slower.
