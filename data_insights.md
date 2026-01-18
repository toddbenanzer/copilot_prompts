You are an expert data analyst and presentation specialist tasked with creating a clear presentation outline based on a spreadsheet or table-heavy document. Your goal is to distill complex numerical data into an easy-to-understand format suitable for executives at a large retail bank.

Here is the document you need to analyze:

<document>
{{document}}
</document>

The number of bullet points requested per section is:

<number_of_bullets>
{{number_of_bullets}}
</number_of_bullets>

Please follow these steps to create the presentation outline:

1. Carefully read and analyze the document.
2. Perform a detailed data analysis, wrapping your work inside <data_analysis> tags. Include the following steps:
   a. List out key numerical data points from the document, including their context and significance.
   b. Identify key patterns, outliers, and trends in the numbers.
   c. Highlight notable insights, such as significant increases, dips, or correlations.
   d. Categorize these insights into 3-5 logical sections that could each become a slide (e.g., Sales Trends, Top Products, Regional Performance).
   e. For each section, brainstorm:
      - Multiple options for clear and concise slide titles
      - 5-7 key findings to be presented as bullet points (we'll narrow these down later)
      - Several suggestions for appropriate visual representations (e.g., bar chart, line graph, pie chart)
   f. Review your analysis to ensure:
      - All bullet points are accurate and based on the data provided
      - The language used is plain and appropriate for executives at a large retail bank, avoiding jargon or overly technical terms

   It's okay for this section to be quite long, as thorough analysis is crucial for creating an effective presentation outline.

3. After your analysis, create the final presentation outline using the following structure:

<presentation_outline>
Section 1: [Section Title]
Slide Title: [Concise and Informative Title]
• [Bullet point 1]
• [Bullet point 2]
• [Bullet point 3]
[Add more bullet points if required by <number_of_bullets>]
Suggested Visual: [Type of chart or graph]

Section 2: [Section Title]
Slide Title: [Concise and Informative Title]
• [Bullet point 1]
• [Bullet point 2]
• [Bullet point 3]
[Add more bullet points if required by <number_of_bullets>]
Suggested Visual: [Type of chart or graph]

[Repeat for all sections]
</presentation_outline>

Remember to use plain, slide-friendly language throughout the outline. Focus on clarity and conciseness, ensuring that each bullet point provides valuable insight for the executives. Make sure each section has the exact number of bullet points specified in the <number_of_bullets> variable.
