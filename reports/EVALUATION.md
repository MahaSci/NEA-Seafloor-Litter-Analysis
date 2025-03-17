# Evaluation Report: North East Atlantic Seafloor Litter Analysis

## Project Summary

This project aimed to conduct an in-depth analysis of marine litter in the North East Atlantic region using data from CEFAS, supplemented with Global Fishing Watch data. The primary objectives were to classify pollution, analyse composition trends, identify hotspots, assess environmental impact, and raise public awareness.

## Asessment of environmental impact of marine litter on biodiversity
The project's assessment of environmental impact, particularly regarding marine biodiversity, revealed a strong correlation with high plastic litter concentrations. Areas exhibiting elevated plastic pollution also indicated potential risks to marine ecosystems. While direct biodiversity data was not within the primary dataset, the overlay of fishing activity from Global Fishing Watch provided an indirect indicator. High plastic areas coinciding with intense fishing activity suggest increased potential for entanglement and ingestion of plastics by marine life, thus highlighting a potential negative impact on biodiversity. Further research incorporating ecological surveys and species-specific data would be necessary to fully quantify these effects.

## Evaluation of Learning Process

### Reflection on Progress and Challenges

Throughout this project, I encountered several challenges that significantly contributed to my learning and adaptation. Initially, I struggled with data cleaning and preprocessing, particularly handling missing values and inconsistent date formats. The DataFrame not updating issue was a fundamental lesson in understanding how Pandas handles data manipulation.

The imputation function challenge was a significant learning curve. I initially overlooked the importance of reassigning the DataFrame after imputation, which led to persistent missing values. Using ChatGPT to summarise the long output from the imputation function was an innovative approach that showcased the potential of AI tools in data analysis.

Recognising gaps in my knowledge, especially in statistical analysis and advanced data visualisation, was crucial. I addressed these gaps by looking up online resources, exploring documentation, and seeking feedback. 

Specifically, I learned about:

* **Statistical Analysis:** Understanding the nuances of t-tests, Mann-Whitney U tests, and correlation methods like Cramér's V.
* **Data Visualisation:** Mastering interactive maps, heatmaps, and advanced plotting techniques using Plotly.
* **Geospatial analysis:** Recognising this as an area for future development.
* **Correlation analysis:** Learning to select the best method for different data types.

### Strategies Used to Overcome Challenges

* **Documentation and Online Resources:** I relied heavily on Pandas, NumPy, and Plotly documentation, as well as online tutorials and the learning material from the bootcamp.
* **Debugging and Testing:** I implemented systematic debugging techniques to identify and resolve issues such as print statements.
* **Seeking Feedback:** I actively sought feedback from peers and instructors, which helped refine my approach and understanding.
* **AI Assistance:** Leveraging tools like ChatGPT to summarise complex outputs and gain insights.

### Code Adaptation and Bug Resolution

The date parsing error was a clear example of adapting code to overcome challenges. By adding `dayfirst=True` to the `pd.to_datetime()` function, as suggested by the error message, I resolved the issue. This experience highlighted the importance of understanding error messages and using them to guide debugging.

The inconsistent spatial data accuracy issues were recognised as unfixed bugs. While workarounds were implemented, comprehensive solutions were not achieved due to time constraints. This experience underscored the importance of thorough data validation and the limitations of available resources.

### Feedback and Improvements

To improve the usability of my dashboard, I consulted with my cousin, an interaction designer. She suggested implementing an 'F' shaped layout, which she explained is a standard design principle for accommodating the left-to-right reading flow of English-speaking users.

## Development Roadmap

Based on my project experience, I plan to focus on the following new skills and tools:

* **Advanced Statistical Methods:** Deepen my understanding of time series analysis, spatial statistics, and other advanced statistical techniques.
* **Machine Learning:** Explore machine learning algorithms for automated litter type identification and predictive modelling.
* **Geospatial Analysis:** Learn to use GeoPandas and other geospatial libraries for more complex spatial analysis.
* **Advanced Data Visualisation:** Master D3.js and other advanced visualisation tools for creating interactive and dynamic dashboards.
* **Deployment:** Learn how to deploy dashboards as web applications for wider accessibility.
* **Environmental Impact Assessment:** Learn how to combine ecological data with pollution data to assess the environmental impact of marine litter.
* **Source Tracking Methods:** Research and learn about methods to track the source of marine litter.

## Evaluation of Project Objectives

* **Classification of Pollution:** Achieved through detailed categorisation of litter types and visualisation of composition trends.
* **Analysis of Composition Trends:** Successfully tracked temporal changes in litter composition using line charts and moving average plots.
* **Identification of Hotspots:** Effectively located pollution concentrations using heatmaps and scatter plots.
* **Assessment of Environmental Impact:** Initial steps taken by overlaying fishing activity data, but further research is needed.
* **Public Awareness:** Addressed through -
## Overall Evaluation

This project provided a valuable learning experience and successfully achieved its primary objectives. The challenges faced and the strategies used to overcome them have significantly contributed to my growth as a data analyst. The project has laid a strong foundation for future developments and continuous learning.