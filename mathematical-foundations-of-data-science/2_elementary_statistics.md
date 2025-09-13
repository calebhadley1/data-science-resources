# [Elementary Statistics For Math 1401 at The University of West Georgia](https://alg.manifoldapp.org/system/actioncallout/0/5/3/053a1575-131e-4626-904c-884ca823cde2/attachment/e20ed4251d26feb80dc432bd0497cb68.pdf#page=[3])
- This book covers foundations concepts of Statistics.

## Overview, Data and Uncertainty
- Chapter 1.1
    - This chapter provides defintions for key concepts such as:
        - Population
        - Sample
        - Variable
        - Data
        - Descriptive Statistics vs Inferential Statistics
        - Census
        - Parameter
        - Quan/Qualitative
        - Observational/Designed experiments
        - Placebo/Treatments
        - Sampling strategies (Random, Representative, Clustering/Stratified, Systematic, and Convenience)

    - Chapter 1.1 Excersise Sols:
        - Identify the population, sample, parameters, and statistics for the following situation.
        A textbook company wants to know the average price of homeschool science textbooks
        in the United States. They obtain a list of 15 science books and compute the average
        price of the 15 books is $52.
            - Population: All homeschool Science Textbooks in the US
            - Sample: 15 Science Books
            - Parameters: Population average price of all the books
            - Stats: Average of 15 books = 52$

        - A teenager put the following information on his myspace page. What are the variables,
        what are their values, which variables are qualitative, which are quantitative? Name:
        Sean Higgins, Ht: 5ft.10in., Wt: 185 lbs., Eyes: Green, Hair: Red, Page-hits: 142
            - Variables: name, height, weight, eye_color, hair_color, page_hits
            - Values: sean 5ft10, 185, green, red, 142
            - Qualitative: nam, eye and hair color
            - Quantitative: height, weight, page hits

        - Use systematic sampling to select 7 people out of a group of 6700. State the place
        numbers of the selected sample.
            - One such systematic method is to take the sample size & divide by 7 rounding down, we will call it n, split the sample into groups of n, take the mth person in each group of n

        - Does the following describe an experiment or just an observational study? Explain
        why. Sarah was on a field trip for her science class. At the beach, she saw a sand castle
        with 2 crabs crawling inside it. She timed the crabs to see how long they took to find
        their way out.
            - Observational because Sarah is not involved in what the crabs are doing. She did not impose treatments or try to control anything

        - Which type of sampling best fits the following? Explain why. DJ Paulie D is looking
        for some songs to be the background beats for his new mix. He sorts his ipod collection
        into four categories: Rap, Instrumental, Dance, and Alternative. Then he randomly
        picks 5 songs from each category and listens to the beats.
            - Music genre stratified samples. It is not clustering because in clustering groups are created and entire group is used

        - What is a census? The US government does a census every ten years. Why don’t they
        do one every year? Is the US census an actual census? Why or why not?
            - Census is a recording of data about the entire population
            - Every 10 years because it is very rigorous and requires a ton of resourcing
            - Nah because the entire population does not participate. US Census does some changes to the data as a result to make it represntative

        - Which sampling methods tend to have bias? Explain how they have bias.
            - Convenience sampling since it results in similar sample points (i.e. people you are close to may have similar location, age etc)
            - Stratified is usually the best
            - Systematic does not allow most of the combinations to be picked
            - Cluster can be biased if people in the same cluster have similar charactristics
            - Simple is not biased methodology wise, but the sample could be biased

        - Why do experimenters use placebos? How do they use them?
            - Double blind with placebos prevents any bias from the conductor of the experiment or the participator.

        - Which samples are representative of their populations, which are not? Explain why.
            (a) A marketing firm wants to know how much time teenagers spend on youtube.
            They post ads to take their survey on the top ten youtube videos.
            (b) A large company wants to know how far their employees drive to work. They pick
            employees from several cities, several different job levels, and a mix of young and
            older employees.
            - (a): Nope, only people watching top ten youtube videos participate. What about teenagers who watch no youtube videos?
            - (b): Nice

## Sampling and Descriptive Statistics
- Chapter 1.2
    - Distributions
        - What values the variable takes on and how often
    - Classes (Data is often grouped according to these)
        - Categories or groupings
        - Numerical data is grouped in consecutive intervals (e.g. 0 - 0.99, 1.0 - 1.99)
        - Class midpoint
        - Class boundaries (# halfway between upper and lower limits of class. For the example above it would be like 0.995)
        - Class width
            - The difference between consecutive
            lower limits, or consecutive upper limits, or consecutive midpoints, or consecutive boundaries
        - Guidelines for creating classes
            1. Small number of classes to be effective, but enough to show differences.
            2.  Each observation must belong to only one class, the classes MUST NOT overlap.
            3. Whenever feasible, classes should have same width.
        - “…compute the Frequency of each class, which is the number of observations that
        fall into a class (count). A listing of all classes of the data and their frequencies is called a
        Frequency distribution”
        - “When data sets are different sizes, it is hard to compare them. A good way to compare
        is to compute Relative Frequency, which is the ratio of the frequency of a class to the
        total number of observations. A listing of all classes and their relative frequencies is called a
        Relative Frequency distribution. Most distributions show frequencies as well as relative
        frequencies.”
        - Cumulative frequencies (running tally)
    - Histograms (quant data)
        - Frequency vs relative frequency hist
    - Pie chart
    - Bar chart (qual data/categories)
        - Pareto chart = ordered bar chart by freq
    - Things to note when reading graphs:
        - Center: where is the middle of the graph, and the highest point.
        - Spread: how are the parts of the graph spread out from each other?
        - Shape: what shape does the graph have? Bell shape, straight across (uniform), repeatedly up and down, random?
        - Symmetry: graph can be split in half with two mirror image parts, almost equal
        amount on both sides of the peak. Uniform graphs (level straight across) are also
        technically symmetric.
        - Skewness A graph that extends more out to left side of the peak (high point) is called
        Left-skewed. A graph that extends more out to right side of the peak (high point) is
        called Right-skewed.
        21
        - Outliers: are data values (small parts of the graph) that are far from the other data
        (parts).
    - Time series graphs

- Chapter 1.3
    - Notations
    - Sigma X = the sum of elements in X
    - Descriptive measures - mean, med, max, etc
        - Measures of Center
            - Sample mean (x bar)
            - Population mean (mu)
            - Median
            - Mode
            - These stats are sensitive to extreme values
            - left skewed datasets the mean is less than median
            - Using Frequency distribution to calculate mean
            - Weighted mean
        - Measures of Variation
            - “Measures of Variation (or measures of spread) are descriptive measures that indicate how much variation is in the data or how spread out the data values are from each other.”
            - Min, max, range, std
            - std of sample = s
            - variance of sample = s^2
            - std of population = omega
            - variance of pop = omega^2
            - We can compare the std of two similar datasets
            - When they are not similar, we use Coefficient of Variation

- Chapter 1.4
    - Measures of Relative Standing (measures that describe how particular data values compare to each other)
    - Z Scores
        - The number of standard deviations that a given
        value is above or below its mean
        - Usual values are z-scores from −2 to +2.
        - Z = X - mean(x) / std
    - Percentiles
        - Quartiles (every 25th percentile), Q1, Q2, Q3. Q2 = P50
        - Methods for calculating percentiles
    - Boxplots