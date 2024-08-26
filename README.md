# Fire-Analysis: The Growing Threat of Wildfires and Their Costs

## Project Collaborators:

* [Theresa F.](https://github.com/TheresaFregoso)
* [Scott J.](https://github.com/UtahPando)
* [Sabrina L.](https://github.com/LegallyNotBlonde)
___

## Short Project Overview 

* We started with the original data in PDF format, with each year in a separate file. 
* Using code, we extracted this data into Excel, parsed the relevant pages, and transformed it into key metrics using Pandas libraries. 
* We then created an SQL schema to store the data and used JavaScript to build HTML pages with interactive dashboards. 
* Pandas was also used for various visualizations. Due to our group's limited size and time constraints, we divided the project into smaller tasks, allowing us to work in parallel. 
* This approach has lead to multiple code files in this repository.

### Purpose

* This project is for educational purposes only. 
* We analyzed the frequency of these fires, the damage they cause, and whether some counties experience more fires than others, highlighting regions at higher risk.
* Additionally, we explored whether the number and impact of fires have consistently increased over the years or if they have fluctuated.

___

### Key Findings and Charts
* We identified key metrics characterizing fires and included them in our presentation.
* Below are some of the graphs.

#### *Please find more details in the separate presentation included in this repo.*

___

### Ethical Consideration 
In our fire analysis project, we are fully aware of the **importance of protecting personally identifiable information (PII)**. However, the resource files we used contained only general statistics, so PII was not an issue in this case. Despite this, we remained vigilant in upholding other ethical considerations throughout our process. We worked hard to ensure that our data and insights were presented accurately, avoiding any bias or misleading conclusions, especially in sensitive areas like financial losses and human fatalities. We were also mindful of **potential algorithmic biases** that could affect the fairness and accuracy of our findings, **particularly with automated processes**. By being transparent about our data sources and the limitations of our analysis, we aimed to maintain trust and uphold the integrity of our work.
___

### Conclusion
The number of fires fluctuate year by year and there is no consistent growth.
However, on average fire burn during 13 days a month with astronomical financial losses.

### Key Takeaway for Viewers
This project, while independent and exploratory, offers valuable insights:
    * **County-Level Risk Assessment:** Access localized fire statistics and risk assessments here. You can check information about your county [HERE](LINK TO BE ADDED).
    * **Economic Impact:** In **2017**, California's fires cost over **$12 billion**. From **2008-2022, total damages exceeded $24 billion**, excluding human and environmental costs, and costs of containing fires.
    * Yearly Statistics can be found *[HERE](https://example.com/yearly-statistics).*
    * **Policy Implications:** Preventative measures, though costly, could be more cost-effective than the devastating damages from wildfires.
    * **Real Estate Considerations:** When buying property in California, consider fire risks alongside other factors like earthquakes, as they significantly impact insurance costs.
___

### Methodologies and Programming Languages Used
* Pandas libraries
* Python (including but not limited to Flask)
* SQL 
* JavaScript

___

### Repo Structure
* **[Resources folder](https://github.com/LegallyNotBlonde/Fire-Analysis/tree/main/Resources)** contains original, raw data sets
* **[Outputs](https://github.com/LegallyNotBlonde/Fire-Analysis/tree/main/Outputs)** includes transformed data and tables
* **[Charts](https://github.com/LegallyNotBlonde/Fire-Analysis/tree/main/Charts)** folder contains various visualization displays
* **Files with codes** have **self-explanatory names** and are available in the [main body of the repo](https://github.com/LegallyNotBlonde/Fire-Analysis)
* **[Presentation](https://docs.google.com/presentation/d/18218T6EQrjeQu0vUXJoN1WikxMXPLT6Y-v4c-PHHHL0/edit#slide=id.p)** with more information about the projects and all necessary charts.
* ### *[Link to the interactive visualization](http://127.0.0.1:5500/index.html)*

___

### Resourses 
* [California State Geoportal](https://gis.data.ca.gov/)
* [Youtube Link](https://www.youtube.com/watch?v=VEtICDT_ZmI) to display fire siren created by [Kermit the sound](https://www.youtube.com/@kermitthesound389)
* AdobeStock - Image for the title presentation page
___

### Data Limitations
* Our data focuses on fires 300+ acres, as smaller fires were underreported. 
* Some fires spanned multiple counties; we tracked them by origin for accurate impact assessment. 
* Financial losses cover basic property and content damage, excluding suppression costs, business interruptions, and insurance hikes.


*This project is licensed under the GNU General Public License v3.0. For more details, please refer to the 'LICENSE' file.*