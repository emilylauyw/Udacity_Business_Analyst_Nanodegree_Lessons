# 02 - Data Wrangling

## Preparing Data

### 1. Understanding Data
- What are the various types of data?
- Why is formatting important?

#### Sources of Data
1. Transactional: like what's recorded at the supermarket for every purchase.
2. Devices: captured from devices we use like our TV, cable boxes, or cellphones
3. Collected: data like weather, census, or flight data.

Challenge: how you can use all the data available to make your analyses as rich and powerful as possible

#### Categories of Data
1. Structured
Structured data are data with a high degree of organization. They are typically organized into columns and rows like in a spreadsheet. Sometimes columns are also called fields and rows are referred to as records and these terms may end up being used interchangeably throughout the course. Each column represents a variable and each row represents a record of data. Structured data is often stored in databases or files such as spreadsheets and it is usually easily accessible and most importantly, it’s easy to use.

2. Unstructured
Unstructured data can have no structure to it at all. Since the data isn’t organized into a typical columns and rows format, it can be time-consuming to work with as you have to pull what you want out of it. Some examples of this type of data are a resume, a tweet or a contract document.

3. Semi-Structure
Semi-structured data is data that has some structure to it but still requires some work to put it into a structured format of columns and rows. This could be a computer system log file that requires parsing and manipulating to put into a format that makes the data easier to analyze.

#### Data Soruces
1. Computer files: created from applications like MS Excel or Access, from predictive software like SAS or SPSS.
2. Databases
3. Web-based sources

#### Importance of Data Types
1. Doing calculations across multiple fields: assumes that we're working with numeric fields so both of the fields need to be number types.
2. Blending data sets: field or fields we're joining on to be the same data type

#### Common Field Types
1. Strings: are any combination of characters, alpha-numeric including symbols. Some examples can be an address field, a state code, an open-ended survey response or a product description.

2. Numeric: are numbers which can be whole numbers such as integers or numbers with decimal places. Some examples are sales in dollars, population in a trade area around a store or the age of a person.

3. Date/Time: can contain a specific date or a combination of both date and time. This data can be really handy for calculating the number of minutes between a caller reporting a problem and its resolution.

4. Boolean: sometimes also called a Logical type and is a conditional flag representing either true or false.

5. Special Objects: can be objects such as images, maps, report objects, and sound files to name a few examples.

### 2. Data Issues
- Problems we may encounter when working with data
- Dirty data, missing values, outliers

#### Dirty Data
Data that contains some kind of errors in them, or are in a format that's unfriendly or unusable.

Example:
- Not parsed correctly: last name and first name appear all in one field instead of multiple fields.
- Extra Characters: extra characters in data fields that make it difficult to use the data readily.
- Misspelled Entries: typos which can easily happen when typing data in manually.
- Duplicate Data Records: happen because of multiple data entries for the same information.
- Incorrect Data: like dates that are from January 1, 1900. This can happen when a user is working with a system that requires a value but none is available at the time.
- Unexpected Pattern: data that does not fit with the expected pattern. Example not email addresses are in the proper format that ends with ".com".


####




### 3. Data Formatting
- Format our data so it is useful
- Data is often not in the format we need


### 4. Data Blending
- Blend data together from disparate datasets
