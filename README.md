# Python_CustomerAnalytics

A common problem when creating models to generate business value from data is that the datasets can be so large that it can take days for the model to generate predictions. Ensuring that your dataset is stored as efficiently as possible is crucial for allowing these models to run on a more reasonable timescale without having to reduce the size of the dataset.

The Head Data Scientist at Training Data Ltd. has asked you to create a DataFrame called ds_jobs_transformed that stores the data in customer_train.csv much more efficiently. Specifically, they have set the following requirements:
- Columns containing categories with only two factors must be stored as Booleans (bool).
- Columns containing integers only must be stored as 32-bit integers (int32).
- Columns containing floats must be stored as 16-bit floats (float16).
- Columns containing nominal categorical data must be stored as the category data type.
- Columns containing ordinal categorical data must be stored as ordered categories, and not mapped to numerical values, with an order that reflects the natural order of the column.
- The DataFrame should be filtered to only contain students with 10 or more years of experience at companies with at least 1000 employees, as their recruiter base is suited to more experienced professionals at enterprise companies.
