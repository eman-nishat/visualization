    > What software did you use to create your data visualization?

    For the second visualization, I created a barchart using R's ggplot2. The dataset I chose is the Career College Key Performance Indicators from the Ontario Data Catalogue (https://data.ontario.ca/dataset/private-career-colleges-pcc-key-performance-indicators/resource/799f29b1-1031-4e14-b3bf-01ee811e9129). This dataset offers insights into post-secondary education outcomes in Ontario. I decided to create a barchart to visualize the graduation rate of each college in Ontario.

    > Who is your intended audience? 
    
    The intended audience incldues secondary school students that are exploring different colleges, as well as policy makers and funding agencies. 
    
    > What information or message are you trying to convey with your visualization? 
    
    This barchart provides insight into colleges that have the higest and lowest graduation rates in Ontario. It can guide students to narrow down their choice of college to where they will most likely be successful. It will also help policy makers and funding agencies investigate why or why not certain colleges have higher/lower graduation rates, and what resources may need to  be re/allocated between colleges to ensure success for all students. 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    I chose a vertical bar chart to allow for a straightforward comparison of graduation rates across colleges. The x-axis labels were rotated 90 degrees to accommodate long college names and improve readability, and a clear title and axis labels were added to provide context. The bars were colored in green for barcharts showing colleges with high graduate rate and tomato red to subtly indicate low performance of colleges with low graduate rates. I also adjusted the plot aesthetics and font sizes to improve readability.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    I created the plot using R and documented every step by commenting the code. 
    
    > How did you ensure that your data visualization is accessible?  
    
    I used high-contrast fill colors for the bars, removed any visual clutter by keeping a minimal plot, and ensured the font sizes are legible and the labels are clear and descriptive.    

    > Who are the individuals and communities who might be impacted by your visualization?  

    Colleges would be impacted as this visualization would affect their enrollment and funding.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    For barcharts showing colleges with the top graduate rates, I removed those with 100% graduate rate and for those showing bottom graduate rates, I removed those with 0%. This is because I wanted the plots to be descriptive, to not overwhelm the user, and to spotlight those most in need of attention.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    I renamed columns/variable names for ease when coding, removed percent signs, converted strings to numeric values. Since some colleges had multiple entries/rows due to different programs, I grouped the data by college and calculated average graduation rates across programs, which required careful handling of duplicate entries.