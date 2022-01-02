# H-M-Analysis

Link to the website: https://www2.hm.com/en_us/women/products/view-all.html

In the exploratory data analysis project, I have scraped the offical website of H&M to derive insights on Women's clothing (category: All) for the following fields:
1. Item name
2. Discounted Price (In my entire analysis I have considered this field as the selling price)
3. Original Price

Note: I have just scraped one-third of the available data on this page(i.e. I scraped 1079 products out of total around 3000 availbe on the website)

This is an exploratory data analysis to derive primary conclusions based on the data.
The PowerBI visualization is a sample of how I would visualize this data.
I have also used Python (Jupyter Notebook) to conduct this exploratory Data Analysis.

Note: Depending on the availability of data, even more insights can be derived


Results of this Analysis of this Dataset:

Assumption: The discounted price (as shown on the H&M's website) is the final selling price
1. Maximum selling Price was for Padded Leather Shopper and the price was 254.15 USD
2. Minimum selling Price was for a range of items mainly Crop Tops and Cotton Tshirts and the Price was 5.09 USD
3. The Average selling Price for all the Products is 27.42 USD (Note: Outliers, which were not eliminated, considerably affect this result)
4. Wordcloud shows us that the data mainly contains items with "Turtleneck", "Blouse","Sweater". Further information on sales will help us on predicting the regional/global fashion trends
5. The Maximum Discount was offered to the following Product: Padded Leather Shopper and the discount was 44.84 USD
6. The Minimum Discount was offered for a range of items mainly Crop Tops and Cotton Tshirts and discount was 0.90 USD
7. Average Discount for the Products was 4.84 USD
8. Assuming all of these 1096 items got sold, it will bring in the revenue of 30056 USD
