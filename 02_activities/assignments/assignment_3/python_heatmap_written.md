    > What software did you use to create your data visualization?

    For the first visualization, I created a heatmap using Python's seaborn. The dataset I chose is the Career College Key Performance Indicators from the Ontario Data Catalogue (https://data.ontario.ca/dataset/private-career-colleges-pcc-key-performance-indicators/resource/799f29b1-1031-4e14-b3bf-01ee811e9129). This dataset offers insights into post-secondary education outcomes in Ontario. I decided to create a heatmap to visualize the satisfaction rates of each program by both graduate students and employers. 

    > Who is your intended audience? 
    
    The intended audience incldues secondary school students that are exploring different career pathways, as well as guidance counselors or college administrators. 
    
    > What information or message are you trying to convey with your visualization? 
    
    For secondary school students, this heatmap provides insight into which program types report higher graduate satisfaction, suggesting an overall positive student experience, and which programs have a higher employer satisfaction rates, suggesting post-graduation success and job readiness. Simiarly, this heatmap provides the same information for guidance counselors or college administrators that may be supporting students in making these decisions.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    When making the heatmap, I considered clarity, comparability, and visual hierarchy. THe sequential colour palette helps viewers intuitively understand higher versus lower satisfaction values. I also added annotations within each cell so viewers can see precise values directly on the plot. I rotated the x-axis labels to improve readability. Lastly, I bolded the title and axes labels and increased the size of the title to improve readability.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    By creating the plot using Python and documenting every step by commenting the code, I ensured that my data visualization is reproducible. 
    
    > How did you ensure that your data visualization is accessible?  

    To ensure my heatmap is accessible, I used a colourblind-friendly colour pallette. The numbers are also directly on the plot for those who cannot understand the colour gradient as easily. I also adjusted the spacing between the plot and the title to avoid clutter. 
    
    > Who are the individuals and communities who might be impacted by your visualization?  

    Secondary school students that are exploring post-secondary options would be impacted. Post-secondary institutions may also be impacted as public satisfaction data may influence popularity of their programs, which in turn would affect program evaluations and funding opportunities. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    I focused on making a key piece of information available (graduate and employer satisfaction rates by program type). This helped narrow down the variables I needed for my visualization. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    I first explored the dataset to see which variables the dataset had and the different variable types. Since the percentages were saved as strings, I converted them to numeirc values. I renamed variables and long names for PROGRAM TYPE to improve the visual appearance of the plot. I also removed rows with missing values.  