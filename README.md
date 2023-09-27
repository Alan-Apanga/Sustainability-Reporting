# Understanding CO2 Emissions by Scope
As defined by the GHG Protocol corporate standard ([Link](https://ghgprotocol.org/sites/default/files/standards_supporting/FAQ.pdf)), greenhouse gas emissions are categorized into three distinct scopes:

**Scope 1**: These are direct emissions released into the atmosphere due to the company's own activities, including those stemming from its facilities such as manufacturing plants and warehouses, as well as company-owned vehicles.

**Scope 2**: Indirect emissions result from the generation of purchased energy, which includes electricity and gas procurement.

**Scope 3** Encompassing all other indirect emissions outside of Scope 2, these emissions occur throughout the company's value chain. They encompass elements like Transportation, Waste of Operations, and Business Travels.

In this GitHub project, our primary focus centers on calculating Scope 3 emissions related to downstream transportation.

# Assessing the Environmental Impact of the Transportation Network
CO2 Emissions Computation Using Emissions Factors
In accordance with the guidelines from the French Environmental Agency Ademe (Link), we employ the following formula to estimate CO2 emissions stemming from transportation:

- **E_Co2** = W_goods * D * F_mode
Where:

- **E_CO2**: Represents emissions in kilograms of CO2 equivalent (kgCO2eq).
- **W_goods**: Signifies the weight of goods in tons (Ton).
- **D**: Corresponds to the distance from your warehouse to the final destination in kilometers (km).
- **F_mode**: Denotes the emissions factor for each transportation mode in terms of kilograms of CO2 equivalent per ton-kilometer (kgCO2eq/t.km)
