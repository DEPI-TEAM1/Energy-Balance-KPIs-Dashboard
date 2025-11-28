 
Contents
Contents	1
1. Project Planning & Management	3
1.1. Project Proposal	3
1.1.1. Overview of the project	3
1.1.2. Objectives	3
1.1.3. Scope	3
1.2. Project Plan	4
1.2.1 Timeline (Gantt chart)	4
1.2.2. Milestones	4
1.2.3. Deliverables:	4
1.2.4. Resource allocation:	4
1.3. Task Assignment & Roles	4
1.4. Risk Assessment & Mitigation Plan	5
1.5. KPIs (Key Performance Indicators)	6
2. Lecturer Review	7
2.1. Feedback & Evaluation	7
2.2. Suggested Improvements	7
3. Requirements Gathering	8
3.1. Stakeholder Analysis	8
3.1.1. Stakeholders:	8
3.1.2. Needs:	8
3.1.3. User Stories & Use Cases	8
3.1.4. Functional Requirements	9
4. System Analysis & Design	9
4.1. Problem Statement & Objectives	9
4.2. Database Design & Data Modeling	10
4.2.1. System Behavior	10
4.2.2. Relationship Diagram	10
4.2.3. Query Tables:	10
4.2.4. Measures	11
4.2.5. Functional Requirements	11
4.3. KPIs (Key Performance Indicators)	12
4.4. Data Flow Description	13
4.4.1. Processes	13
4.4.2. Data Flows	13
5. Implementation (Source Code & Execution)	13
5.1. Source Code	13
5.2. Version Control & Collaboration	13
6. Testing & Quality Assurance	14
6.1. Data Validation (Test Cases):	14
6.2. Bug Reports:	14
7. Final Presentation & Reports	15
7.1. User Manual:	15
7.2. Technical Documentation:	16
7.3. Project Presentation:	16
7.4. Video Demonstration:	16
7.5 Deployment & Execution	16
8. Insights and Recommendations concluded from data strategic analysis of Egypt's Energy System (1971-2018)	17
8.1. Exponential Growth in Energy Demand Creates Sustained Pressure on Resources and Infrastructure.	17
8.2. The Transportation Sector Emerges as the New Primary Driver of Energy Consumption Growth, Overtaking Industry.	18
8.3. Overall Energy System Efficiency Shows a Long-Term Decline.	18
8.4. The Economy Has Not Decoupled Economic Growth from Energy Consumption.	19
8.5. A Strategic Shift in the Energy Mix: From Oil Dominance to Heavy Reliance on Natural Gas	19
8.6. The Contribution of Renewable Energy Has Remained Marginal for Decades	20
8.7. Dominance of Petroleum Products in Final Consumption Reveals the Economy's Main Artery and its Vulnerability	20
8.8. The Success Story of "Electrification and Gasification" Reshaped Demand but Exposed the Efficiency Challenge	20
9. Egypt Energy Balance 2023 Insights	21
10. Conclusions and Recommendations	24
11. Appendices	24
Appendix A: Sample Power BI Screenshots	25
Appendix B: Data Tables Overview	28
Appendix C: DAX Calculations Summary	30

 
1. Project Planning & Management
1.1. Project Proposal
1.1.1. Overview of the project
According to the United Nations Division, an energy balance is "an accounting framework for compiling and synthesizing data on all energy products entering and present in a given country and its national territories during a specific reference period". 
Energy balance analysis is crucial for evaluating national performance, policy alignment, and sustainability. For Egypt, understanding the balance between energy production and consumption enables better decision-making and supports strategic, economic, and environmental planning.
1.1.2. Objectives
This project aims to perform an in-depth data analysis of Egypt's energy balance (1971–2018), integrating robust analytical methods with sector-specific indicators to evaluate energy performance and sustainability progress.
1.1.3. Scope
1. Assess Egypt’s status in relation to national and international commitments.  
2. Support the achievement of sustainable energy targets.  
3. Enhance national energy security.  
4. Encourage diversification of energy sources.  
5. Promote energy efficiency and optimal resource utilization.  
6. Generate actionable insights for decision-makers.
1.2. Project Plan
1.2.1 Timeline (Gantt chart)


1.2.2. Milestones
- Data Collection & Cleaning  
- ETL 
- Relationship Modeling  
- DAX Measures Calculation 
- Data Visualization and Dashboard design.
1.2.3. Deliverables:
Dynamic, interactive and attractive dashboard that tell the story of Egyptian Energy data balance in insightful way showing the major KPIs in a way that allow stakeholders to take valuable decisions and potentiate political plans for future
1.2.4. Resource allocation:
Approximately 10–15% of the total project timeline to ensure the system's sustainability and regulatory compliance. 40% of work package assigned primarily to the Power BI Analyst for technical mapping and DAX measures to validate business logic, such as defining specific KPIs for energy Efficiency and renewable energy targets. 30 % of work was for visualizing the energy data in interactive a strategic view in addition to adding a sanky diagram an additional visualization tool for the most recent energy balance data 2023. Finally, 15% of work was for Documentation, presenting the project in different platforms such as git-hub.
1.3. Task Assignment & Roles 
	Our team consists of 6 members with different skills. 
	Tasks were assigned to every person to match his field of excellence:
Role	Team Member	Responsibilities
Project Manager	Nancy	Project coordination, task distribution, communication with stakeholders, progress tracking.
Data Cleaning and completing	Mona Nancy	Handling dataset inconsistencies, preparing cleaned data for analysis.
		
ETL	Esraa	Data extraction, transformation, and loading; ensuring data consistency and validity.
Relationship building and determining KPIs	Nancy	Relationship building and determining KPIs
Measures & Calculation	Mostafa	DAX measures, KPI implementation.
Dashboard & Visualization Developer	Mostafa, Esraa, Nancy, Mona	Building Power BI dashboards.
Documentation Lead	Hassan Nancy Mona	Preparing project documentation.
Presentation Designer	Alaa	Designing final slides and visualization for stakeholders.

1.4. Risk Assessment & Mitigation Plan

No.	Risk/ Challenge	Mitigation Plan
1	All the team members except one (Nancy) have different background not related to the energy sectors.	Intensive meetings and awareness sessions were made in the beginning of the project for all the team members about the energy analysis.
2	Some irrational data due to poor data entry in some years and energy items.	Data correction through insightful analysis of general data
3	Energy Data Confidentiality issue	o	Data obtained from open sources online 
IEA – International Energy Agency 
and world bank for the period 1971-2018.
o	2023 Energy data from Central Agency for Public Mobilization and Statistics (CAPMAS)
o	2019-2021 Energy data weren’t used and not recommended due to COVID-19 pandemic

4	The format and alignment of data weren’t suitable for analysis	Creative solutions by using knowledge gained through DEPI initiative in ETL and DAX measures for dealing with this hard data.

1.5. KPIs (Key Performance Indicators) 

KPI	Description
Response Time	
User adoption rate	
First time in Egypt: Energy Balance Dash Board	This is the first time in Egypt and in the Egyptian Government to have an interactive, friendly use,  real data Energy Balance Dash board which shows all the following energy statistics and KPIs:
Electricity in Residential	It measures electricity consumed by households
Energy Intensity 	It measures the energy efficiency of the economy by calculating the ratio of TPES to GDP. 
RE Share in Electricity Generation 	It calculates the percentage of renewable energy in the total energy generation. 
RE Electricity Generation 	 It measures the production of electricity using renewable energy sources.
Sector Analysis	It measures energy consumption patterns across different sectors
TPES	Total Primary Energy Supply.
It's a measure of the total energy available for consumption
Transformation consumption	It measures the energy lost or consumed during the process of converting energy from one form to another, like converting crude oil to fuels or coal to electricity
TFC 	Total Final Consumption that measures the energy consumed by end-users like households, industry, transport, etc., after transformation and distribution losses.
Electricity Transmission and Distribution Losses	 It refers to energy losses that occur when electricity is transmitted and distributed from power plants to end-users.
Electrification (% of electricity use in FEC) 	It shows the share of electricity in total final energy consumption

2. Lecturer Review
2.1. Feedback & Evaluation

Component	Weight	Criteria & Observations	Score
Data Preparation & Modeling (ETL)	25%	Evaluation of Power Query transformations, data cleaning, and the efficiency of the data model (Star Schema). Usage of DAX measures for complex calculations (e.g., YoY growth in renewable capacity).	25 / 25
Visualization & UI/UX	25%	Clarity of charts, effective use of space, color consistency, and navigation features. Does the dashboard allow for intuitive drill-down into specific Governorates or Energy Types?	25 / 25
Analytical Depth & Insights	30%	Ability to derive meaningful conclusions from the Egypt Energy data. Does the analysis identify trends in consumption vs. production, or grid efficiency issues?	30 / 30
Documentation & Presentation	20%	Quality of the written report, resource allocation planning, and the verbal defense of the project. Clarity of the Data Dictionary.	20 / 20
TOTAL	100%		100 / 100

2.2. Suggested Improvements 
Environmental measures such as Carbon emissions index can be added.
3. Requirements Gathering
3.1. Stakeholder Analysis
3.1.1. Stakeholders:
Egyptian presidency, The Egyptian Cabinet (Presidency of the Council of Ministers), ministry of electricity and renewable energy, Ministry of Petroleum and mineral resources, Ministry of Communications and Information Technology.
3.1.2. Needs:
•	Renewable Energy Expansion: Identify opportunities for solar, wind, and hydroelectric power growth to increase renewable energy capacity.
•	Energy Efficiency: Understand energy consumption patterns to reduce waste, optimize energy distribution, and promote energy-efficient technologies.
•	Fuel Subsidy Reform: Inform pricing strategies and mitigate the impact on vulnerable populations.
•	Investment Attraction: Showcase Egypt's energy potential to attract investments in renewable energy projects.
•	Sustainable Development: Achieve sustainable development goals, including reducing greenhouse gas emissions and promoting economic growth while protecting the environment.
•	Energy Policy and Planning: Inform energy policy and planning to ensure a sustainable energy mix.
•	Resource Allocation: Optimize energy resource allocation to maximize efficiency and productivity.
•	Energy Security and Sustainability: Enhance energy security and sustainability to ensure a reliable energy supply.
•	Economic Growth: Drive economic growth through renewable energy investments.
•	Public Health and Environmental Protection: Improve public health and environmental protection by reducing pollution and promoting clean energy.
3.1.3. User Stories & Use Cases 
•	Stakeholders can interact with analysis and visualization of Egypt Energy Balance through:
3.1.3.1. Energy Production and Consumption Analysis
•	Monitor Egypt's energy production and consumption patterns, identifying areas for improvement and opportunities for renewable energy growth.
•	Analyze the dashboard to inform policy decisions, such as optimizing energy subsidies and promoting energy efficiency.

3.1.3.2. Renewable Energy Expansion

•	Track progress towards Egypt's renewable energy targets, identifying areas for investment and development.
•	Evaluate the effectiveness of initiatives like the African Global Hydrogen Summit, aimed at maximizing the green industrial revolution in Africa.
3.1.3.3. Energy Security and Sustainability
-	Assess Egypt's energy security, identifying potential risks and opportunities for diversification.
-	Inform decisions on energy infrastructure development, ensuring a reliable and sustainable energy supply.
3.1.3.4. International Cooperation and Investment
•	Showcase Egypt's energy potential, attracting investments in renewable energy projects and promoting international cooperation.
•	Help Egypt's leaders evaluate the impact of partnerships, such as the agreement with France to enhance energy sustainability and provide clean energy solutions.
3.1.4. Functional Requirements 
3.1.4.1. Data Visualization:
Interactive charts & graphs to display energy production & consumption patterns
Maps to show energy infrastructure and resource distribution
3.1.4.2. Energy Production Analysis:
Tracking of energy production from various sources (renewable, fossil fuels, etc.)
3.1.4.3. Energy Consumption Analysis:
Breakdown of energy consumption by sector (industrial, residential, etc.)
Identification of peak demand periods and trends
3.1.4.4. Energy Efficiency Analysis:
Assessment of energy efficiency measures 
Identification of areas for energy efficiency improvement
3.1.4.5. Reporting and Export:
Generation of reports and summaries for stakeholders
Export of data and reports in various formats (PDF, XLS, etc.)
4. System Analysis & Design
4.1. Problem Statement & Objectives 
 No Visualization tool or dash board has been done before for Egypt Energy Balance data analysis.

4.2. Database Design & Data Modeling
A Fact table is the energy sources and other tables are dimension tables and measures.
4.2.1. System Behavior
The dash board consists of: home page, over view, A Sankey diagram for Egypt energy balance and flow of energy year 2023, Primary energy Supply Analysis page, Final energy Consumption analysis page and sector analysis page.
A navigation is done through clickable buttons in each page.
4.2.2. Relationship Diagram


4.2.3. Query Tables:


4.2.4. Measures
















4.2.5. Functional Requirements
1. Data Visualization:
    - Interactive charts & graphs to display energy production & consumption patterns
    - Maps to show energy infrastructure and resource distribution
2. Energy Production Analysis:
    - Tracking of energy production from various sources (renewable, fossil fuels, etc.)
3. Energy Consumption Analysis:
    - Breakdown of energy consumption by sector (industrial, residential, etc.)
    - Identification of peak demand periods and trends
4. Energy Efficiency Analysis:
    - Assessment of energy efficiency measures and their impact
    - Identification of areas for energy efficiency improvement
5. Scenario Planning:
    - What-if analysis for different energy scenarios (e.g., increased renewable energy adoption)
6. Reporting and Export:
    - Generation of reports and summaries for stakeholders
    - Export of data and reports in various formats (PDF, XLS, etc.)
4.3. KPIs (Key Performance Indicators)
Examples include:  
- Import Dependency Ratio  
- Energy Mix Diversity Index  
- Electricity Generation Diversity  
- Energy Intensity  
- Renewable Share in Generation  
- Transmission and Distribution Losses  
KPI 	Description 
Import Dependency Ratio 	This ratio calculates the proportion of energy consumed that is imported. It can be expressed as a percentage of the total energy consumption.
Energy Mix Diversity Index 	 This index, typically between 0 and 1, measures how varied a country's energy sources are in its energy mix
Electricity Generation Diversity	This index measures the variety of energy sources in the electricity generation mix. It can be measured using the Herfindahl-Hirschman Index (HHI), which quantifies the concentration of generation sources. 
Electricity in Residential	It measures electricity consumed by households
Energy Intensity 	It measures the energy efficiency of the economy by calculating the ratio of TPES to GDP. 
RE Share in FEC 	It measures the share of Renewable Energy in the Final Energy Consumption
RE Share in Electricity Generation 	It calculates the percentage of renewable energy in the total energy generation. 
RE Electricity Generation 	 It measures the production of electricity using renewable energy sources.
Sector Analysis	It measures energy consumption patterns across different sectors
TPES	Total Primary Energy Supply.
It's a measure of the total energy available for consumption
Transformation consumption	It measures the energy lost or consumed during the process of converting energy from one form to another, like converting crude oil to fuels or coal to electricity
TFC 	Total Final Consumption that measures the energy consumed by end-users like households, industry, transport, etc., after transformation and distribution losses.
Total EE Savings 	 It refers to the overall reduction in energy consumption achieved through energy efficiency measures
Total EE Improvement	It refers to the overall enhancement in energy efficiency achieved through various measures
Electricity Transmission and Distribution Losses	 It refers to energy losses that occur when electricity is transmitted and distributed from power plants to end-users.
Electrification (% of electricity use in FEC) 	It shows the share of electricity in total final energy consumption

4.4. Data Flow Description
 The system follows a standard ETL (Extract, Transform, Load) pipeline to process Egypt's energy data effectively, ensuring data integrity from source to visualization.
4.4.1. Processes 
1.	Data Ingestion: Fetching raw energy data (Production & Consumption) from external sources (e.g., World Bank, BP Statistical Review) covering the period 1971-2018.
2.	Data Preprocessing: Validating the raw data, handling missing values (Nulls), and correcting format inconsistencies.
3.	Data Transformation: Aggregating data by fuel type (Gas, Oil, Hydro…) and converting units to KTOE to ensure comparability.
4.	Analysis & Modeling: Applying statistical methods to identify trends, correlations, and calculating KPIs (Key Performance Indicators).
5.	Visualization & Reporting: Generating interactive charts and dashboards for the final user presentation.
4.4.2. Data Flows 
Raw Data: Flows from Process 1 (Ingestion) to Process 2.0 (Preprocessing).
Cleaned Data: Flows from Process 2 (Preprocessing) to Process 3.0 (Transformation).
Structured Dataset: Flows from Process 3 (Transformation) to Process 4.0 (Analysis).
Insights & Metrics: Flows from Process 4 (Analysis) to Process 5.0 (Visualization).
Final Dashboard: Flows from Process 5 to the User/Stakeholder.
5. Implementation (Source Code & Execution)
5.1. Source Code
•	Tools: Microsoft Excel (for data storage) & Power BI Desktop.
•	Power Query Editor: Used for ETL (Extract, Transform, Load) processes:
•	Cleaning data: Removing blank rows and fixing headers in Excel sheets.
•	Unpivoting columns: To transform year columns into rows for better analysis.
•	Changing Data Types: Ensuring "Year" is a Whole Number and "Consumption" is Decimal Number.
5.2. Version Control & Collaboration
1.	DAX Formulas (Data Analysis Expressions): Writing measures for calculations, for example:
- Conversion of thermal power generation％ = 
ABS (DIVIDE ([Electricity Generated], [Total inputs for power generation]))

- Conversion Rate (%) =∣Electricity Generated Total Inputs for Power Generation Conversion Rate (%) =Total Inputs for Power Generation Electricity Generated

- Electricity in Residential = CALCULATE (SUM ('fEnergy sources and balance'[Value]),
    'fEnergy sources and balance'[Energy Balance Items] = "Residential",
    'fEnergy sources and balance'[Energy Product] = "Electricity")
Note: (All Measures & Calculation in Appendix C)
2. Version Control & Collaboration:
File Management: Energy Balance - Final.pbix
3. Deployment & Execution:
•	File Type: The project is delivered as a Power BI file (.pbix) and a PDF export.
•	Execution:
•	Open Energy_Egypt_Analysis.pbix using Power BI Desktop.
•	Dependencies: Requires Power BI Desktop installed to view the interactive version.
6. Testing & Quality Assurance
6.1. Data Validation (Test Cases):
•	Source vs. Output Check: Comparing the "Grand Total" in Power BI visuals against the "Sum" in the raw Excel sheets to ensure no data was lost during import.
•	Slicer Testing: Verifying that when the "Year 2018" slicer is selected, all charts update to show only 2018 data (As an Example).
•	Relationship Testing: Ensuring the "Dates" table is correctly linked to the "Energy Data" table (One-to-Many relationship), so charts display correct time trends.
6.2. Bug Reports:
•	Issue: Charts were summing up "Years" (treating Year as a number to be added).
•	Resolution: Changed "Year" summarization setting to "Don't Summarize" in Power BI.
•	Issue: Excel sheets had different names for "Gas" (e.g., "Nat Gas" and "Natural Gas").
•	Resolution: Standardized names in Excel using Find & Replace before importing.
7. Final Presentation & Reports
7.1. User Manual:
•	Interactivity Guide: How to use "Slicers" to filter by Energy Type (Oil, Gas, Hydro).
•	Drill-Down: Instructions on how to click on a specific data point to see more details.
•	Tooltip Explanation: Implementation (Technical Description)







Feature: Advanced Visualization Techniques (Report Page Tooltips)
Description:  To enhance data granularity without compromising the dashboard's clean design, I implemented Report Page Tooltips. instead of standard text tooltips. I designed a separate, hidden report page containing a bar chart representing 'Energy Consumption by Sector' (Industry, Transport, Residential). 
This page was linked to the main 'TFC by Year' visual. Power BI's internal logic automatically filters the tooltip based on the specific data point (Year) the user interacts with, creating a seamless drill-down experience."
User Manual: Implementation (Technical Description)
Action: Sectoral Mix Analysis
Instruction:
By hovering over the 'Sector Share %' line chart, users can trigger a comparative breakdown. The pop-up window displays a stacked chart that reveals how different sectors consume energy. For example, users can instantly see what percentage of 'Non-Renewable' energy is consumed by the Industry sector versus the Residential sector for the selected time period.

7.2. Technical Documentation:
•	Data Model Schema: A screenshot of the "Model View" in Power BI showing tables (Fact Tables & Dimension Tables) and the lines connecting them. (Appendix A)
•	Measures List: A list of key DAX formulas used (e.g., Average Consumption, Max Production).(Appendix C)
7.3. Project Presentation:
•	Storytelling: A slide deck (PPT) summarizing the major shift in Egypt’s energy mix (Trend Analysis).
•	Visuals: High-quality screenshots from the Power BI dashboard showing the most critical insights. (Appendix B)
7.4. Video Demonstration:
7.5 Deployment & Execution
README File – Includes:
Installation steps
	•	System requirements (hardware/software dependencies)
	•	Configuration instructions
	•	Execution guide (running the project locally or accessing a deployed version)
	•	Executable Files & Deployment Link –
	•	Compiled software or packaged application (e.g., .exe, .jar, .apk).
	

8. Insights and Recommendations concluded from data strategic analysis of Egypt's Energy System (1971-2018)
8.1. Exponential Growth in Energy Demand Creates Sustained Pressure on Resources and Infrastructure.
•	Observation: The (TPES and TFC by Year) and (Electricity Generated... by Year) charts show continuous and steep growth in Total Primary Energy Supply, Total Final Consumption, and electricity generation over the past five decades.
•	Context: This massive growth is directly correlated with Egypt's rapid population growth, urbanization, and industrial economic development during this period.
•	Implication & Recommendation:
•	Implication: This relentless growth puts immense pressure on the energy infrastructure (power plants, grids) and requires massive, continuous investment just to keep pace with demand, posing a challenge to national energy security.
•	Recommendation: The national energy strategy must evolve from merely "meeting demand" to actively "managing demand." It is critical to implement robust energy efficiency and conservation policies across all sectors to moderate the demand growth rate and make it more sustainable.
 8.2. The Transportation Sector Emerges as the New Primary Driver of Energy Consumption Growth, Overtaking Industry.
•	Observation: The chart (Industry Share%, Residential share% and Transportation share% by Year) reveals a major structural shift in consumption patterns. While the industrial sector's share was historically dominant, the transportation sector's share has been steadily rising since the 1990s, eventually surpassing industry to become the largest consuming sector.
•	Context: This shift reflects a significant increase in private vehicle ownership, a reliance on road transport for freight, and the lack of sufficient and efficient mass transit alternatives nationwide.
•	Implication & Recommendation:
•	Implication: The transportation sector is now the single greatest challenge to achieving energy sustainability and reducing emissions, given its near-total dependence on petroleum products.
•	Recommendation: An urgent and targeted strategy for the transportation sector is required, focusing on developing public transport networks (e.g., metro, electric trains), incentivizing the shift to electric vehicles (EVs), and improving vehicle fuel efficiency standards.
8.3. Overall Energy System Efficiency Shows a Long-Term Decline.
•	Observation: The (TFC/TPES by Year) chart, which shows the ratio of final energy consumed to the primary energy supplied, displays a general downward trend over the decades. The ratio was higher in the 1970s and 80s and has been declining since, meaning the gap between the energy produced and the energy that reaches the end-user is widening.
•	Context: The primary driver for this decline is the increasing share of electricity in the final consumption mix. The process of converting fossil fuels to electricity in thermal power plants involves significant inherent energy losses. As electricity's share grows, the system's overall efficiency drops.
•	Implication & Recommendation:
•	Implication: Egypt is wasting a growing percentage of its primary energy resources in conversion and transmission processes. This represents a major economic and environmental loss.
•	Recommendation: A concentrated effort must be made to boost the efficiency of the power generation sector (using modern technologies) and reduce losses in the distribution grid (the `Rate of distribution loss of electricity` chart shows that losses are high and volatile).
 8.4. The Economy Has Not Decoupled Economic Growth from Energy Consumption.
•	Observation: The (Sum of TFC/GDP %) chart, which measures the energy intensity of the economy, does not show a clear and sustained long-term decline. After some fluctuations, the curve appears to have flattened or is declining very slowly in recent years.
•	Context: This means that every unit of GDP requires an amount of energy that has not significantly decreased over time. In contrast, advanced economies typically show a clear drop in this indicator as they shift towards technology and service-based industries.
•	Implication & Recommendation:
•	Implication: This tight coupling makes future economic growth very energy-intensive and costly, limiting the ability to achieve environmentally sustainable growth.
•	Recommendation: National policies must be implemented to actively "decouple" economic growth from energy consumption by promoting knowledge-based and service industries and enforcing strict energy efficiency codes for new buildings and factories.
8.5. A Strategic Shift in the Energy Mix: From Oil Dominance to Heavy Reliance on Natural Gas
•	Observation: The TPES by Year and Energy Product chart clearly illustrates a fundamental transformation in the primary energy mix. While crude oil was the dominant source until the late 1990s, natural gas began to grow exponentially, becoming Egypt's largest single source of energy since the early 2000s.
•	Context: This was not a random shift, but the result of a strategic state policy following major discoveries of natural gas fields in the Mediterranean Sea. This gas was directed to fuel new power plants and expand the distribution network to homes and factories.
•	Implication & Recommendation:
•	Implication: While this transition successfully reduced reliance on imported oil and enhanced energy security, it created a new form of dependency on a single fossil fuel (natural gas), leaving the economy exposed to long-term production and price risks.
•	Recommendation: The next strategic energy transition must be from reliance on natural gas to true diversification towards renewable sources. Egypt should not wait for gas resources to deplete before initiating this critical shift.
8.6. The Contribution of Renewable Energy Has Remained Marginal for Decades
•	Observation: Despite the overall massive growth in energy supply, the TPES by Year and Energy Product Type donut and area charts show that the contribution of renewables has remained consistently low, accounting for only about 5% of the Total Primary Energy Supply.
•	Context: Historically, political and investment focus was centered on exploiting discovered fossil fuel resources (first oil, then gas). Large-scale renewable energy projects only began to gain significant momentum in the very last few years of the period covered by this analysis.
•	Implication & Recommendation:
•	Implication: This represents a massive missed opportunity over several decades to leverage Egypt's rich natural resources (sun and wind) to achieve environmental and economic sustainability, and to create jobs in the green economy.
•	Recommendation: More ambitious and binding renewable energy targets must be set, supported by strong investment incentives and streamlined regulations to accelerate project implementation and grid integration.
8.7. Dominance of Petroleum Products in Final Consumption Reveals the Economy's Main Artery and its Vulnerability
•	Observation: The TFC by Energy Product donut chart shows that petroleum products (gasoline, diesel, etc.) account for the largest share of final energy consumption, at over 56%.
•	Context: This dominance is directly tied to the transportation sector's leading role in energy consumption (cars, trucks, buses), in addition to other uses in industry and agriculture.
•	Implication & Recommendation:
•	Implication: This heavy dependence on petroleum products makes the cost of transport and goods in the Egyptian economy extremely sensitive to global oil price fluctuations. It is also the primary source of urban air pollution.
•	Recommendation: More than anything else, this statistic underscores the urgent need to diversify energy sources within the transportation sector. Investing in transport electrification (EVs) and expanding electric mass transit networks is not just an environmental luxury; it is a strategic economic imperative.
8.8. The Success Story of "Electrification and Gasification" Reshaped Demand but Exposed the Efficiency Challenge
•	Observation: The TFC by Year and Energy Product area chart displays massive growth in the final consumption of electricity and natural gas since the 1980s. Together, they now represent a very significant share of final consumption (approx. 18.4% each).
•	Context: This reflects successful government policies to expand the national electricity grid and to connect homes and factories to the natural gas network as an alternative to LPG cylinders and heavy fuel oil.
•	Implication & Recommendation:
•	Implication: While this has improved the quality of life and supported industrial growth, it is also the direct cause of the declining overall system efficiency (the TFC/TPES ratio). We are now consuming more "secondary energy" (electricity), which involves significant primary energy losses during generation.
•	Recommendation: Since the shift towards electricity and gas is irreversible and beneficial for the end-user, the focus must now shift to making that electricity and gas supply more sustainable. This means generating electricity from renewable sources and boosting the efficiency of power plants.
9. Egypt Energy Balance 2023 Insights
The 2022/2023 energy balance reveals an economy heavily anchored in Natural Gas (53%) and Petroleum (41%). While energy intensity is improving (indicating better efficiency per unit of GDP), the power sector remains the primary driver of gas demand, with significant conversion losses inherent to thermal generation.
•	Renewable Energy Share: Fossil fuels still dominate Egypt's electricity generation, at 88% in 2023. Hydropower contributed 7%, and wind and solar accounted for 5%. The total installed capacity of renewable energy reached 7.7 GW across all types (wind, solar, and hydro).
•	Consumption Trends: Primary energy consumption in Egypt showed a slight decline of 1% in 2023, following a 6% decline in 2022.
1. Energy Supply Analysis: The Dominance of Gas
Egypt's total primary energy supply (TES) for the fiscal year was 92,057 thousand tons of oil equivalent (ktoe). The mix highlights a rigid dependence on fossil fuels:
•	Natural Gas: 53% of total supply.
•	Crude Oil & Petroleum Products: 41% of total supply.
•	Other Sources: Coal, Coke, and Renewables (Hydro, Wind, Solar) combined make up only roughly 6%.
The "Energy Balance Sankey 2023" confirms that natural gas is the backbone of the system, feeding both the massive power generation sector and industrial feedstocks.
2. Sectoral Consumption: Transport vs. Industry
Total Final Energy Consumption (FEC) stood at 58,646 ktoe. The consumption behavior varies starkly by sector:


Sector	Share of Consumption	Primary Energy Source
Transport	38% (Highest)	Almost exclusively Petroleum Products.
Industry	27%	Mixed (Gas, Electricity, Petroleum).
Residential	21%	Heavily reliant on Electricity and Natural Gas.
Others	14%	Includes Trade, Services, Agriculture.
3. Power Systems & Electricity Generation
For a power systems engineer, the conversion and loss data in this report is critical. The electricity sector is the primary "sink" for natural gas supply.
•	Generation Mix: 59% of Egypt's total natural gas supply is consumed solely for electric power generation.
•	Grid Performance:
o	Transmission & Distribution (T&D) Losses: 3,521 ktoe.
o	Comparing T&D losses (3,521) to final consumption (14,281), the grid losses represent a significant percentage of delivered energy, highlighting an area for potential infrastructure optimization.
4. Industrial Utilization: Energy vs. Feedstock
The industrial sector consumed 13,269 ktoe of Natural Gas. However, not all of this is burned for power:
•	Fertilizers: This specific sub-sector consumed 37% of industrial natural gas.
5. Energy Intensity Trends (Efficiency)
A positive trend is observed in the "Energy Intensity" indicators, which measure energy used per unit of GDP.
•	Total Supply Intensity: Dropped from 14 (2015/16) to 11 (2022/23).
•	Final Consumption Intensity: Dropped from 9 (2015/16) to 7 (2022/23).
Insight: Egypt is generating more economic value (GDP) for every unit of energy consumed, indicating a gradual decoupling of economic growth from energy consumption.
The 2022/2023 energy balance reveals an economy heavily anchored in Natural Gas (53%) and Petroleum (41%). While energy intensity is improving (indicating better efficiency per unit of GDP), the power sector remains the primary driver of gas demand, with significant conversion losses inherent to thermal generation.
•	Renewable Energy Share: Fossil fuels still dominate Egypt's electricity generation, at 88% in 2023. Hydropower contributed 7%, and wind and solar accounted for 5%. The total installed capacity of renewable energy reached 7.7 GW across all types (wind, solar, and hydro).
•	Consumption Trends: Primary energy consumption in Egypt showed a slight decline of 1% in 2023, following a 6% decline in 2022.
1. Energy Supply Analysis: The Dominance of Gas
Egypt's total primary energy supply (TES) for the fiscal year was 92,057 thousand tons of oil equivalent (ktoe). The mix highlights a rigid dependence on fossil fuels:
•	Natural Gas: 53% of total supply.
•	Crude Oil & Petroleum Products: 41% of total supply.
•	Other Sources: Coal, Coke, and Renewables (Hydro, Wind, Solar) combined make up only roughly 6%.
The "Energy Balance Sankey 2023" confirms that natural gas is the backbone of the system, feeding both the massive power generation sector and industrial feedstocks.
2. Sectoral Consumption: Transport vs. Industry
Total Final Energy Consumption (FEC) stood at 58,646 ktoe. The consumption behavior varies starkly by sector:
Sector	Share of Consumption	Primary Energy Source
Transport	38% (Highest)	Almost exclusively Petroleum Products.
Industry	27%	Mixed (Gas, Electricity, Petroleum).
Residential	21%	Heavily reliant on Electricity and Natural Gas.
Others	14%	Includes Trade, Services, Agriculture.
3. Power Systems & Electricity Generation
For a power systems engineer, the conversion and loss data in this report is critical. The electricity sector is the primary "sink" for natural gas supply.
•	Generation Mix: 59% of Egypt's total natural gas supply is consumed solely for electric power generation.
•	Grid Performance:
o	Transmission & Distribution (T&D) Losses: 3,521 ktoe.
o	Comparing T&D losses (3,521) to final consumption (14,281), the grid losses represent a significant percentage of delivered energy, highlighting an area for potential infrastructure optimization.
4. Industrial Utilization: Energy vs. Feedstock
The industrial sector consumed 13,269 ktoe of Natural Gas. However, not all of this is burned for power:
•	Fertilizers: This specific sub-sector consumed 37% of industrial natural gas.
5. Energy Intensity Trends (Efficiency)
A positive trend is observed in the "Energy Intensity" indicators, which measure energy used per unit of GDP.
•	Total Supply Intensity: Dropped from 14 (2015/16) to 11 (2022/23).
•	Final Consumption Intensity: Dropped from 9 (2015/16) to 7 (2022/23).
Insight: Egypt is generating more economic value (GDP) for every unit of energy consumed, indicating a gradual decoupling of economic growth from energy consumption.
10. Conclusions and Recommendations
The Egypt Energy Balance Project (1971–2018) provided a data-driven overview of national energy dynamics, supported the identification of key inefficiencies, enabled insights for sustainability and policy improvements, laid the foundation for advanced forecasting models and real-time dashboards supporting Egypt Vision 2030.
The dashboard tells a clear story: Egypt faces a dual challenge of massive, unabated growth in energy demand and a long-term decline in its overall energy system efficiency. The transportation sector has emerged as the new key driver of this consumption. To ensure a secure and sustainable energy future, the strategy must pivot from focusing solely on increasing supply to a more balanced approach that includes aggressive demand-side management, radical efficiency improvements, and a structural transformation of the transportation sector.
11. Appendices
- Appendix A: Sample Power BI Screenshots  
- Appendix B: Data Tables Overview  
- Appendix C: DAX Calculations Summary  














Appendix A: Sample Power BI Screenshots

Dashboard Home Page

Sankey Diagram












Appendix B: Data Tables Overview  





 
















Appendix C: DAX Calculations Summary  

1. Conversion of thermal power generation (%)
DAX Formula:
Conversion of thermal power generation％ = 
ABS (DIVIDE ([Electricity Generated], [Total inputs for power generation]))
Description:
Conversion of thermal power generation (%)
This measure calculates the efficiency of thermal power plants in converting fuel or energy inputs into electricity. It is computed as the absolute value of the ratio between the total electricity generated and the total energy inputs used for power generation.
Formula:
Conversion Rate (%)=∣Electricity GeneratedTotal Inputs for Power Generation Conversion Rate (%)=Total Inputs for Power GenerationElectricity Generated
Where:
•	Electricity Generated: Total electricity output produced by the power plants.
•	Total inputs for power generation: Sum of all energy sources (inputs) consumed for electricity production.
Note: The ABS function ensures the value is always positive.
2. Electricity in Residential
DAX Formula:
Electricity in Residential = CALCULATE(    SUM('fEnergy sources and balance'[Value]),
    'fEnergy sources and balance'[Energy Balance Items] = "Residential",
    'fEnergy sources and balance'[Energy Product] = "Electricity"
)
Description :
Electricity in Residential
This measure represents the total amount of electricity consumed by the residential sector. It is calculated by summing values from the energy balance table where the energy balance item is 'Residential' and the energy product is 'Electricity'.


Formula (DAX):
Electricity in Residential = 
Electrification rate % = ABS (DIVIDE (CALCULATE (SUM ('fEnergy sources and balance'[Value]),'fEnergy sources and balance'[Energy Product] ="Electricity”, fEnergy sources and balance'[Energy Balance Items]
IN {“Non-specified (industry)",
"Rail",
"Residential",
"Commercial and Public Services",
"Agriculture/Forestry"}),
[TFC]))

•	'Value': The quantity of energy consumed (e.g., MWh, GWh).
•	'Energy Balance Items': Breakdown by sector (filtered for 'Residential').
•	'Energy Product': Type of energy (filtered for 'Electricity').

3. Electrification rate %
Electrification rate % = ABS (DIVIDE(CALCULATE(SUM('fEnergy sources and balance'[Value]),'fEnergy sources and balance'[Energy Product] ="Electricity”, fEnergy sources and balance'[Energy Balance Items]
IN { "Non-specified (industry)",
"Rail",
"Residential",
"Commercial and Public Services",
"Agriculture/Forestry"}),
[TFC]))
Description:
This measure calculates the share of electricity in total final energy consumption for key sectors. It sums up electricity consumption for the selected sectors and divides it by the Total Final Consumption (TFC).
3. Electricity Generated
Electricity Generated = CALCULATE(
SUM('fEnergy sources and balance'[Value]),
'fEnergy sources and balance'[Energy Product] = "Electricity”, fEnergy sources and balance'[Energy Balance Items] = "Transformation Electricity Output")
Description:
Total electricity produced and sent out from power generation facilities.


4. Industry Share%
Industry Share% = DIVIDE ([Total Industry Sector], [TFC])
Description:
The ratio of the industry's total energy consumption to total final consumption (TFC), representing the industry's share in overall energy use.
5. Natural gas Consumption
Natural gas Consumption = CALCULATE (SUM ('fEnergy sources and balance'[Value]), 
    'fEnergy sources and balance'[Energy Product] IN {"Gas"})
Description:
Total natural gas consumed across all sectors.
5. Rate of distribution loss of electricity %
ABS (DIVIDE (CALCULATE (SUM ('fEnergy sources and balance'[Value]),'fEnergy sources and balance'[Energy Balance Items] = "Distribution Losses”, fEnergy sources and balance'[Energy Product] = "Electricity"),
CALCULATE (SUM ('fEnergy sources and balance'[Value]),'fEnergy sources and balance'[Energy Product] ="Electricity”, fEnergy sources and balance'[Energy Balance Items]
IN {
"non-specified (industry)",
"Rail",
"Residential",
"Commercial and Public Services",
"Agriculture/Forestry"
}
)
))
Description:
Percentage of electricity lost during distribution, calculated as the share of distribution losses from the total electricity supplied to users.
7. Residential Electricity %
Residential Electricity % = 
DIVIDE(    CALCULATE(SUM(...), ... = "Residential", ... = "Electricity"), 
    CALCULATE(SUM(...), ... = "Residential")
)
Description:
Share of electricity in total residential energy consumption.
7. Residential rate of traditional Biomass and waste %
Residential rate of traditional Biomass and waste % = 
ABS (DIVIDE (
    CALCULATE (SUM(...), ... = "Residential", ... = "Combust. Renew. & Waste"),
    [Total in Residential]
))
Description:
Percentage share of traditional biomass and waste in the total residential energy consumption.
9. Residential share%
Residential share% = DIVIDE ([Total in Residential], [TFC])
Description:
Share of total energy consumption attributed to the residential sector.
10. TFC (Total Final Consumption)
TFC = 
ABS(CALCULATE(TFC = ABS(CALCULATE(
SUM('fEnergy sources and balance'[Value]),
'fEnergy sources and balance'[Energy Balance Items] IN {
"Iron and steel",
"Chemical and Petrochemical",
"Non-ferrous metals",
"Non-metallic minerals",
"Transport Equipment",
"Machinery",
"Mining and Quarrying",
"Food and Tobacco",
"Paper, Pulp and Printing",
"Wood and Wood Products",
"Construction",
"Textile and Leather",
"Non-specified (industry)",
"World aviation bunkers",
"Domestic aviation",
"Road",
"Rail",
"Pipeline transport",
"World marine bunkers",
"Domestic navigation",
"Non-specified (transport)",
"Residential",
"Commercial and Public Services",
"Agriculture/Forestry",
"Fishing",
"Non-specified (other)",
"Industry Sector",
"in Transport",
"in Other Sectors"
}
))
Description:
Sum of all final energy consumed by different sectors (industry, transport, residential, etc.).
11. TFC/TPES
TFC/TPES = DIVIDE([TFC], [TPES])
Description:
Shows the proportion of total final energy consumed (TFC) out of the total primary energy supply (TPES).
12. Total in Residential
Total in Residential = CALCULATE (
    SUM ('fEnergy sources and balance'[Value]), 
    'fEnergy sources and balance'[Energy Balance Items] = "Residential"
)
Description:
Total energy consumed by the residential sector.
13. Total Industry Sector
Total Industry Sector = CALCULATE (
SUM ('fEnergy sources and balance'[Value]),
FILTER (
'fEnergy sources and balance',
'fEnergy sources and balance'[Energy Balance Items] IN {
"Iron and steel",
"Chemical and Petrochemical",
"Non-ferrous metals",
"Non-metallic minerals",
"Transport Equipment",
"Machinery",
"Mining and Quarrying",
"Food and Tobacco",
"Paper, Pulp and Printing",
"Wood and Wood Products",
"Construction",
"Textile and Leather",
"non-specified (industry)"
}
)
)
Description:
Total energy consumed in all industry-related segments.
14. Total inputs for power generation
Total inputs for power generation = ABS (CALCULATE (
    SUM ('fEnergy sources and balance'[Value]),
    'fEnergy sources and balance'[Energy Product] IN {"Petroleum Products", "Gas", "Hydro Geotherm. Solar etc."},
    'fEnergy sources and balance'[Energy Balance Items] = "Transformation Electricity Output"
))
Description:
The sum of all energy sources used as input for electricity generation.
15. Total rate of traditional Biomass and waste %
Total rate of traditional Biomass and waste % = ABS (DIVIDE (CALCULATE (SUM ('fEnergy sources and balance'[Value]),'fEnergy sources and balance'[Energy Balance Items] = "Residential”, fEnergy sources and balance'[Energy Product] ="Combust. Renew. & Waste"), [TFC]))
Description:
Share of traditional biomass and waste in total final energy consumption (TFC).
16. TPES (Total Primary Energy Supply)
TPES = ABS (CALCULATE (

    SUM ('fEnergy sources and balance'[Value]), 
    'fEnergy sources and balance'[Energy Balance Items] IN {“Production", "Imports", "Exports", "International marine bunkers", "International aviation bunkers", "Stock changes”}
))
Description:
Total amount of energy available in the country, i.e., primary energy supply including production, imports



# Energy-Balance-KPIs-Dashboard
