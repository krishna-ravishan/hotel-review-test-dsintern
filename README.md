# hotel-review-test-dsintern

## Insight No.1
The most number of locations that has occured is United States of America. It's frequency count is 4804. The top 10 locations accordingly are USA, New York (3 times - Duplicate Values in the form of New York, New York NY & NY), California, San Jose, Florida, Canada, United Kingdom, Orlando. Since USA is mode we can replace the null values in locations feature using Mode Imputation.

## Insight No.2
There are a total of 6393 total Not Null values in Review, 6448 Not null values in date and a total of 1711 null values in Location column. Since we're mainly concerned with the reviews for the hotel we can drop those rows with null values. After dropping we have a total of 6393 total Not Null values in Review, 6393 Not null values in date and a total of 1711 null values in Location column.

## Insight No.3
The date exist in multiple formats and is not in proper datetime format. So we're to preprocess it and convert it into an approriate format using to_datetime method. 

## Insight No.4
The number of Review counts by year are as follows: 2018 has 2572 Reviews and 2019 has 3821 Reviews.

## Insight No.5
Kindly find the word cloud indicating the most used words in the review excluding stopwords.

![download (2)](https://github.com/krishna-ravishan/hotel-review-test-dsintern/assets/126204661/b408c98a-0480-4307-81c7-023ae7ba231c)


