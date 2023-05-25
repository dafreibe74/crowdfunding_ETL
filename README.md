# crowdfunding_ETL

Group Member: Dave Freiberg, Irena Mehic, Yanqiu Yang

### Overview

1.Cleaned up the csv file: parsed out unnecessary/duplicated data, converted data into required format 

2.Built up the ERD relationship between each database.

3.Create the Crowdfunding Database and Import each CSV file into its corresponding SQL table.

### Resources

BootCamp Instructions: [click here](https://courses.bootcampspot.com/courses/3252/assignments/51268?module_item_id=925270)

Python, Pandas, and either Python dictionary methods

SQL(Postgres, PgAdmin)

QuckDB: [click here](http://www.quickdatabasediagrams.com/)

### ERD Relationship Preview

```
![ERD](https://github.com/dafreibe74/crowdfunding_ETL/blob/main/crowdfunding%20ERD.png)
```

### Working Progress:

#### DAY 1 

1. Upload Repo and ready to clone.
2. Data Cleaning:

* Dave: `category + subcategory`
* Irena: `campaign`
* Yanqiu: `contacts`
* Together: checking each part & the `Crowdfunding Database`

3. On Tuesday night, check out each other's progress

#### DAY 2

1. Combine our code together in to `ETL_Mini_Project_DFreiberg_IMehic_YYang.ipynb`
2. All the cleaned data files are in `Resources folder`
3. Using QuickDB to create schema of all the tables saved in `Resources folder`
4. Create `crowdfunding_db via PgAdmin `
5. Final check to verify that each table has the correct data by running a `SELECT` statement for each.
