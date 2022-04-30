### Created by
- Galang Setia Nugroho
- Hasballah Askar
- Khalishah Fiddina
- Muhammad Ilham Hakiqi
- Tifani Amalina
- Donny Tambunan

# Data Manipulation with Python

Real-world data is messy. That’s why libraries like pandas are so valuable. Using pandas you can take the pain out of data manipulation by extracting, filtering, and transforming data in DataFrames, clearing a path for quick and reliable data analysis. If you want to improve your data wrangling skills this is the track for you. You’ll learn how to prepare real-world data for analysis and grow your expertise as you work with multiple DataFrames using pandas. You’ll also gain hands-on experience of how to combine, merge, and create visualizations. At the end of the track, you'll apply your new-found data manipulation skills to analyze the impact of weather and gender on police behavior. Start this track and discover how pandas can save you time manipulating data.

### Pandas has two object, i.e. **Series** and **DataFrame**. 
1. **Series** is a one-dimensional labeled data structure. It's like a column but with no name. The axis labels are collectively called index.
2. **Implicit Index** is the default index. But we can define a different index, it’s called **Explicit Index** i.e.  the defined index. Defining an index, the number of indexes must be equal to the number of data. Although we have defined an Explicit Index, we can still call data by using its Implicit Index.
If there is the same implicit index and explicit index, it will depend only on the explicit index when it’s being called. If the specified index doesn’t exist (in explicit index), it will return ‘KeyError’ exception.
If there is the same implicit index and explicit index, there will be inconsistency. And to overcome it, use loc and iloc methods. **loc** is used to call explicit index meanwhile implicit index is called using **iloc**.
3. **DataFrame** is generally the most commonly used pandas object. It’s a 2-dimensional labeled data structure with rows and columns. It’s a collection of series with at least 1 series.
