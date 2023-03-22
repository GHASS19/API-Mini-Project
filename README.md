# API-Mini-Project

![image](https://user-images.githubusercontent.com/86930309/227035074-1aa284fe-b863-4293-82e8-03e0bba95a8a.png)

## For this mini project, we will focus on equities data from the Frankfurt Stock Exhange (FSE). We'll try and analyze the stock prices of a company called Carl Zeiss Meditec, which manufactures tools for eye examinations, as well as medical lasers for laser eye surgery.

![image](https://user-images.githubusercontent.com/86930309/226737990-9fc5e371-c70a-4b6b-ad44-4c88800fb44c.png)

## These are your tasks for this mini project:

## 1. Collect data from the Franfurt Stock Exchange, for the ticker AFX_X, for the whole year 2017 (keep in mind that the date format is YYYY-MM-DD).

<Response [200]>
Success status response code indicates that the request has succeeded.

## 2. Convert the returned JSON object into a Python dictionary.

print(type(json_data))
<class 'dict'>

## 3. Calculate what the highest and lowest opening prices were for the stock in this period.

In 2017 the highest price was 53.11 and lowest price was 34.0

## 4. What was the largest change in any one day (based on High and Low price)?

The largest change in any one day for 2017 was 2.81

## 5. What was the largest change between any two days (based on Closing Price)?

The largest change between any two days is 2.56

## 6. What was the average daily trading volume during this year?

The average daily trading volume in 2017 is 89124.34
