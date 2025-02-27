## COVID-19-Medical-Waste-Dataset

This dataset provides comprehensive data for understanding medical waste generation and disposal management during the COVID-19 pandemic in China. It integrates several key data sources, including COVID-19 case data, large-scale nucleic acid testing data, city-level medical waste generation data, and city-level medical waste disposal capacity data. These datasets enable detailed analysis of the dynamics of medical waste generation and disposal, especially in response to the pandemic and associated public health measures.
The dataset is divided into the following four main sections:

#1. COVID-19 Data
This section includes daily data on COVID-19 infections and close contacts, covering a period of 871 days from January 11, 2020, to May 31, 2022. The data was sourced from daily updates released by the National Health Commission (NHC) of China, which provides pandemic information at the national, provincial, and city levels.
While the NHC’s reports are generally detailed and comprehensive, the data is primarily presented in text-only formats, making it challenging to extract and format the data for analysis. Significant effort was dedicated to data extraction, conversion, and validation to ensure accuracy and usability.

#2. Large-Scale Nucleic Acid Testing Data
This section contains data on large-scale nucleic acid testing conducted across various cities, with daily queries based on cities reporting new confirmed COVID-19 cases. The data collection period spans from May 14, 2020 (the first test conducted in Wuhan) to April 30, 2022. Over 1,100 instances of nucleic acid testing were recorded.
Most of the data was obtained from publicly available sources, and missing data was estimated based on other testing rounds or the resident population of the same cities. 

#3. City-level Medical Waste Generation Data
This section provides city-level data on medical waste generation during the COVID-19 pandemic. As comprehensive city-level medical waste generation data was not readily available, we collected detailed data for approximately 330 cities from 2019 to 2021. The primary source for the annual medical waste production data is the Solid Waste Pollution Prevention and Control Information Bulletin (2019-2021) for each city.

#4. City-level Medical Waste Disposal Capacity Data
This section contains detailed data on the city-level conventional and emergency disposal capacities for medical waste. The disposal capacity data was primarily sourced from the Solid Waste Pollution Prevention and Control Information Bulletin (2019-2021) for each city, supplemented by data on hazardous waste operating licenses issued by municipalities and provinces.
Additionally, data on potential daily emergency disposal capacity was gathered, including information on hazardous waste incineration and municipal solid waste incineration facilities. The dataset covers over 2,000 incinerators, focusing on those equipped with grate furnaces suitable for emergency medical waste disposal. This data is essential for understanding the ability of cities to manage medical waste, especially in emergency scenarios, and can inform strategies for optimizing waste disposal during future pandemics or public health emergencies.

#Data Structure
The data is primarily organized in time-series format, with separate files for each dataset. Key components include:
-COVID-19 Data: The data includes confirmed cases, suspected cases, serious cases, cured cases, deaths, and close contacts. This data is categorized at the national, provincial, and city levels to comprehensively analyze the pandemic’s trends. The data is structured in a time-series format to ensure an accurate reflection of the pandemic dynamics at different time points.
-Large-Scale Nucleic Acid Testing Data: The nucleic acid testing data includes daily records of testing instances across cities, with detailed fields for start and end dates, city and province, coverage area (such as citywide, key areas, or specific populations), number of people tested, and source URLs.
-City-level Medical Waste Generation Data: For medical waste generation, we collected annual average medical waste generation data for cities from 2019 to 2021.
-City-level Medical Waste Disposal Capacity Data: The data includes disposal capacity for 2019, 2020, and 2021, as well as hazardous waste incineration and municipal solid waste incineration capacities for each city. By compiling data from over 2,000 incineration facilities, we focused on grate furnace incineration facilities suitable for emergency medical waste disposal, ensuring the comprehensiveness and accuracy of the disposal capacity data.

#Use Cases
This dataset is designed to support research, policy development, and operational decision-making related to medical waste management during pandemics. Key use cases include:
-Medical Waste Management: Identifying gaps in disposal capacity and formulating optimization strategies for efficient medical waste treatment and disposal during public health emergencies.
-Epidemiological Research: Analyzing the correlation between the progression of the pandemic and medical waste generation, helping to better understand the impact of COVID-19 on waste production across different regions.
-Public Health Policy: Informing the development of effective public health policies and guidelines for managing medical waste during pandemics and other public health crises.
-Urban Planning and Infrastructure Development: Assisting city planners in forecasting medical waste generation trends, determining appropriate disposal infrastructure, and enhancing the preparedness of waste management systems for future pandemics.
This dataset can provide valuable insights for cities, public health authorities, and waste management organizations to optimize their strategies for medical waste disposal, ensuring better preparedness and response during future public health emergencies.


