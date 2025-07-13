# Viz 1

![alt text](image.png)


For each visualization, describe and justify:

What software did you use to create your data visualization?

I used Python with the Pandas and Matplotlib libraries to prepare and visualize the data. 

Who is your intended audience?

The intended audience includes transportation planners and municipal officials  who are interested in understanding the temporal patterns of parking violations. 

What information or message are you trying to convey with your visualization?

The goal is to identify the times of day when the most common parking violations occur. This supports evidence-based decisions around resource allocation, signage updates, or education campaigns.

What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?

I applied the following design principles based on course materials:

Appropriate chart type: A line plot was chosen to clearly show trends over a  time variable.

Color distinction: Each violation type is plotted in a distinct color with labels.

Gridlines and axis ticks: These were added and evenly spaced to guide the eye through the 24-hour scale.

Responsive layout: tight_layout() was used to avoid crowding and improve readability.

How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?

All steps — from loading raw data, filtering, cleaning, transforming, to plotting — were done in Python with clear, commented code. The data was retrieved from the City of Toronto Open Data Portal, and all logic is  repeatable. If someone reruns the code with an updated file from the same source, the results will update in the same way.

How did you ensure that your data visualization is accessible?

To enhance accessibility: I used color and shape redundancy to support users with color vision deficiencies. Axis labels, legends, and titles are explicitly provided with plain language.
The visualization relies on standard chart forms familiar to most audiences.

Who are the individuals and communities who might be impacted by your visualization?

This visualization could inform: Drivers and residents who may be unaware of high-risk hours for parking violations. City enforcement teams optimizing patrols.

How did you choose which features of your chosen dataset to include or exclude from your visualization?

From the full dataset, I selected: time_of_infraction (converted to hour) and infraction_description (to group types of violations).
These two fields enabled me to answer the question: "When are the most common types of parking tickets issued?" 

What ‘underwater labour’ contributed to your final data visualization product?

Understanding the data schema.

Data cleaning: padding time strings, removing nulls, extracting hour values.

Grouping: transforming long-format data into a usable format.

Troubleshooting issues with downloading large zipped CSVs from an open data API.