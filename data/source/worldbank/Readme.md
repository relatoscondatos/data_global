Data sources from the World Bank [https://data.worldbank.org/](https://data.worldbank.org/)

## PPP conversion factor, GDP (LCU per international $) - ID: PA.NUS.PPP
Path: API_PA.NUS.PPP_DS2_en_csv_v2_2788598  

Purchasing power parity (PPP) conversion factor is a spatial price deflator and currency converter that controls for price level differences between countries, thereby allowing volume comparisons of gross domestic product (GDP) and its expenditure components. This conversion factor is for GDP.

### Source: 
International Comparison Program, World Bank | World Development Indicators database, World Bank | Eurostat-OECD PPP Programme.
### License:  
CC BY-4.0 
### Development Relevance: 
PPP can be used to convert national accounts data, like GDP and its expenditure components, into a common currency, while also eliminating the effect of price level differences between countries. They can also be used to derive price level indexes (PLIs), the ratio of a country’s PPP to its market exchange rate, to directly compare price levels across countries. PPPs and the PLIs and real (or PPP-adjusted) expenditures to which they give rise allow for many use-cases, but they are particularly valuable for empirical work involving comparisons of per capita consumption or levels of GDP (or other GDP aggregates) across countries and for the measurement of global poverty and global income inequality. The breadth and depth of ICP data allows its use-cases to cover other areas of economics, including empirical analyses of economic growth, productivity and trade, and even beyond, for instance, to help track global targets such as the UN Sustainable Development Goals related to health, education, energy and emissions and labor. Other applications of ICP data include their use in the construction of indexes, for example cost-of-living measures. Uses-cases can even be extended into the policymaking domain at all levels (global, regional and national) given the increased importance of cross-country benchmarking, among other possibilities. Recommended uses of PPPs include: To make spatial comparisons of GDP and its expenditure components | To make spatial comparisons of price levels | To group countries by their per capita volume indexes and price level indexes Recommended uses of PPPs with limitations include: To analyze changes over time in relative GDP per capita and relative prices | To analyze price convergence | To make spatial comparisons of the cost of living | To use PPPs calculated for GDP and its expenditure components as deflators for other values.
### Limitations and Exceptions: 
Global PPP estimates provided by ICP are produced by the ICP Global Office and regional implementing agencies, based on data supplied by participating countries, and in accordance with the methodology recommended by the ICP Technical Advisory Group and approved by the ICP Governing Board. As such, these results are not produced by participating countries as part of their national official statistics. PPPs are not recommended use: As a precise measure to establish strict rankings of countries | As a means of constructing national growth rates | As a measure to generate output and productivity comparisons by industry | As an indicator of the undervaluation or overvaluation of currencies | As an equilibrium exchange rate.
### Long Definition: 
Purchasing power parity (PPP) conversion factor is a spatial price deflator and currency converter that controls for price level differences between countries, thereby allowing volume comparisons of gross domestic product (GDP) and its expenditure components. This conversion factor is for GDP.
### Periodicity: 
Annual
### Statistical Concept and Methodology: 
PPPs are both currency conversion factors and spatial price indexes. PPPs convert different currencies to a common currency and, in the process of conversion, equalize their purchasing power by controlling differences in price levels between countries. Typically, higher income countries have higher price levels, while lower income countries have lower price levels (Balassa-Samuelson effect). Market exchange rate-based cross-country comparisons of GDP at its expenditure components reflect both differences in economic outputs (volumes) and prices. Given the differences in price levels, the size of higher income countries is inflated, while the size of lower income countries is depressed in the comparison. PPP-based cross-country comparisons of GDP at its expenditure components only reflect differences in economic outputs (volume), as PPPs control for price level differences between the countries. Hence, the comparison reflects the real size of the countries. The International Comparison Program (ICP) estimates PPPs for the world’s countries. The ICP is conducted as a global partnership of countries, multilateral agencies, and academia. The most recent 2021 ICP comparison covered 176 countries, including 47 Eurostat-OECD countries. For countries that have not participated in ICP comparisons, the PPP are imputed based on a regression model. ICP estimated PPPs cover years from 2011 to 2021. WDI extrapolates 2011 PPPs for years earlier years, and 2021 PPPs for later years. Description of WDI extrapolation approach is available here: datahelpdesk.worldbank.org/knowledgebase/articles/665452-how-do-you-extrapolate-the-ppp-conversion-factors For the member countries of Eurostat-OECD PPP Programme, PPP conversion factors are periodically updated based on the organizations’ databases. For Eurostat-OECD PPP Programme, please refer to the following websites. (oecd.org/sdd/prices-ppp/) (ec.europa.eu/eurostat/web/purchasing-power-parities/overview) For more information on the ICP and PPPs, please refer to the ICP website at worldbank.org/en/programs/icp.

## Price level ratio of PPP conversion factor (GDP) to market exchange rate - ID: PA.NUS.PPPC.RF
Path: API_PA.NUS.PPPC.RF_DS2_en_csv_v2_1665754

Price level ratio is the ratio of a purchasing power parity (PPP) conversion factor to an exchange rate. It provides a measure of the differences in price levels between countries by indicating the number of units of the common currency needed to buy the same volume of the aggregation level in each country. At the level of GDP, they provide a measure of the differences in the general price levels of countries.

### Source: 
International Comparison Program, World Bank | World Development Indicators database, World Bank | Eurostat-OECD PPP Programme.
### License:  
CC BY-4.0 
### Long Definition: 
Price level ratio is the ratio of a purchasing power parity (PPP) conversion factor to an exchange rate. It provides a measure of the differences in price levels between countries by indicating the number of units of the common currency needed to buy the same volume of the aggregation level in each country. At the level of GDP, they provide a measure of the differences in the general price levels of countries.
### Periodicity: 
Annual
### Statistical Concept and Methodology: 
For more information on underlying GDP in current international dollar, please refer to the metadata for "GDP, PPP (current international $)" [NY.GDP.MKTP.PP.CD]. For more information on market exchange reate, please refer to the metadata for "DEC alternative conversion factor (LCU per US$)" [PA.NUS.ATLS]. For the concept and methodology of PPP, please refer to the International Comparison Program (ICP)’s website (worldbank.org/en/programs/icp).


## GDP (current US$) - ID: NY.GDP.MKTP.CD  
Path: API_NY.GDP.MKTP.CD_DS2_en_csv_v2_2002465  

GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in current U.S. dollars. Dollar figures for GDP are converted from domestic currencies using single year official exchange rates. For a few countries where the official exchange rate does not reflect the rate effectively applied to actual foreign exchange transactions, an alternative conversion factor is used.

### Source: 
World Bank national accounts data, and OECD National Accounts data files.
### License:  
CC BY-4.0 
### Aggregation Method: 
Gap-filled total


### Limitations and Exceptions: 
Gross domestic product (GDP), though widely tracked, may not always be the most relevant summary of aggregated economic performance for all economies, especially when production occurs at the expense of consuming capital stock. While GDP estimates based on the production approach are generally more reliable than estimates compiled from the income or expenditure side, different countries use different definitions, methods, and reporting standards. World Bank staff review the quality of national accounts data and sometimes make adjustments to improve consistency with international guidelines. Nevertheless, significant discrepancies remain between international standards and actual practice. Many statistical offices, especially those in developing countries, face severe limitations in the resources, time, training, and budgets required to produce reliable and comprehensive series of national accounts statistics. Among the difficulties faced by compilers of national accounts is the extent of unreported economic activity in the informal or secondary economy. In developing countries a large share of agricultural output is either not exchanged (because it is consumed within the household) or not exchanged for money.
### Long Definition: 
GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in current U.S. dollars. Dollar figures for GDP are converted from domestic currencies using single year official exchange rates. For a few countries where the official exchange rate does not reflect the rate effectively applied to actual foreign exchange transactions, an alternative conversion factor is used.
### Periodicity: 
Annual  
### Statistical Concept and Methodology: 
Gross domestic product (GDP) represents the sum of value added by all its producers. Value added is the value of the gross output of producers less the value of intermediate goods and services consumed in production, before accounting for consumption of fixed capital in production. The United Nations System of National Accounts calls for value added to be valued at either basic prices (excluding net taxes on products) or producer prices (including net taxes on products paid by producers but excluding sales or value added taxes). Both valuations exclude transport charges that are invoiced separately by producers. Total GDP is measured at purchaser prices. Value added by industry is normally measured at basic prices.

## GDP (current LCU) - ID: NY.GDP.MKTP.CN  
Path: API_NY.GDP.MKTP.CN_DS2_en_csv_v2_2001080  

GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in current local currency.


### Source: 
World Bank national accounts data, and OECD National Accounts data files.
### License:  
CC BY-4.0 
### Long Definition: 
GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in current local currency.
### Periodicity: 
Annual

## GDP growth (annual %) - ID: NY.GDP.MKTP.KD.ZG
Path. API_NY.GDP.MKTP.KD.ZG_DS2_en_csv_v2_2788350  

GDP growth (annual %)
Annual percentage growth rate of GDP at market prices based on constant local currency. Aggregates are based on constant 2015 prices, expressed in U.S. dollars. GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources.


## Source: 
World Bank national accounts data, and OECD National Accounts data files.
## License:  
CC BY-4.0 
## Aggregation Method: 
Weighted average
## Development Relevance: 
An economy's growth is measured by the change in the volume of its output or in the real incomes of its residents. The 2008 United Nations System of National Accounts (2008 SNA) offers three plausible indicators for calculating growth: the volume of gross domestic product (GDP), real gross domestic income, and real gross national income. The volume of GDP is the sum of value added, measured at constant prices, by households, government, and industries operating in the economy. GDP accounts for all domestic production, regardless of whether the income accrues to domestic or foreign institutions.
## Limitations and Exceptions: 
Each industry's contribution to growth in the economy's output is measured by growth in the industry's value added. In principle, value added in constant prices can be estimated by measuring the quantity of goods and services produced in a period, valuing them at an agreed set of base year prices, and subtracting the cost of intermediate inputs, also in constant prices. This double-deflation method requires detailed information on the structure of prices of inputs and outputs. In many industries, however, value added is extrapolated from the base year using single volume indexes of outputs or, less commonly, inputs. Particularly in the services industries, including most of government, value added in constant prices is often imputed from labor inputs, such as real wages or number of employees. In the absence of well defined measures of output, measuring the growth of services remains difficult. Moreover, technical progress can lead to improvements in production processes and in the quality of goods and services that, if not properly accounted for, can distort measures of value added and thus of growth. When inputs are used to estimate output, as for nonmarket services, unmeasured technical progress leads to underestimates of the volume of output. Similarly, unmeasured improvements in quality lead to underestimates of the value of output and value added. The result can be underestimates of growth and productivity improvement and overestimates of inflation. Informal economic activities pose a particular measurement problem, especially in developing countries, where much economic activity is unrecorded. A complete picture of the economy requires estimating household outputs produced for home use, sales in informal markets, barter exchanges, and illicit or deliberately unreported activities. The consistency and completeness of such estimates depend on the skill and methods of the compiling statisticians. Rebasing of national accounts can alter the measured growth rate of an economy and lead to breaks in series that affect the consistency of data over time. When countries rebase their national accounts, they update the weights assigned to various components to better reflect current patterns of production or uses of output. The new base year should represent normal operation of the economy - it should be a year without major shocks or distortions. Some developing countries have not rebased their national accounts for many years. Using an old base year can be misleading because implicit price and volume weights become progressively less relevant and useful. To obtain comparable series of constant price data for computing aggregates, the World Bank rescales GDP and value added by industrial origin to a common reference year. Because rescaling changes the implicit weights used in forming regional and income group aggregates, aggregate growth rates are not comparable with those from earlier editions with different base years. Rescaling may result in a discrepancy between the rescaled GDP and the sum of the rescaled components. To avoid distortions in the growth rates, the discrepancy is left unallocated. As a result, the weighted average of the growth rates of the components generally does not equal the GDP growth rate.
## Long Definition: 
Annual percentage growth rate of GDP at market prices based on constant local currency. Aggregates are based on constant 2015 prices, expressed in U.S. dollars. GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources.
## Periodicity: 
Annual
## Statistical Concept and Methodology: 
Gross domestic product (GDP) represents the sum of value added by all its producers. Value added is the value of the gross output of producers less the value of intermediate goods and services consumed in production, before accounting for consumption of fixed capital in production. The United Nations System of National Accounts calls for value added to be valued at either basic prices (excluding net taxes on products) or producer prices (including net taxes on products paid by producers but excluding sales or value added taxes). Both valuations exclude transport charges that are invoiced separately by producers. Total GDP is measured at purchaser prices. Value added by industry is normally measured at basic prices. When value added is measured at producer prices. Growth rates of GDP and its components are calculated using the least squares method and constant price data in the local currency. Constant price in U.S. dollar series are used to calculate regional and income group growth rates. Local currency series are converted to constant U.S. dollars using an exchange rate in the common reference year.

## GDP (constant LCU) - ID: NY.GDP.MKTP.KN
Path: API_NY.GDP.MKTP.KN_DS2_en_csv_v2_2001151  

GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant local currency.


### Source: 
World Bank national accounts data, and OECD National Accounts data files.
### License:  
CC BY-4.0   
### BasePeriod: 
varies by country  

### Long Definition: 
GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant local currency.  
### Periodicity: 
Annual  

## GDP per capita (current US$) - ID: NY.GDP.PCAP.CD

Path: API_NY.GDP.PCAP.CD_DS2_en_csv_v2_1887433

GDP per capita is gross domestic product divided by midyear population. GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in current U.S. dollars.

### Source: 
World Bank national accounts data, and OECD National Accounts data files.
### License:  
CC BY-4.0 
### Aggregation Method: 
Weighted average
### Long Definition: 
GDP per capita is gross domestic product divided by midyear population. GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in current U.S. dollars.
### Periodicity: 
Annual
### Statistical Concept and Methodology: 
For more information, see the metadata for current U.S. dollar GDP (NY.GDP.MKTP.CD) and total population (SP.POP.TOTL).

## GDP per capita (constant LCU) - ID: NY.GDP.PCAP.KN
Path API_NY.GDP.PCAP.KN_DS2_en_csv_v2_2788412

GDP per capita is gross domestic product divided by midyear population. GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant local currency.


### Source: 
World Bank national accounts data, and OECD National Accounts data files.
### License:  
CC BY-4.0 
### BasePeriod: 
varies by country
### Long Definition: 
GDP per capita is gross domestic product divided by midyear population. GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant local currency.
### Periodicity: 
Annual

## GDP per capita, PPP (current international $) - ID: NY.GDP.PCAP.PP.CD
Path: API_NY.GDP.PCAP.PP.CD_DS2_en_csv_v2_1887125

This indicator provides per capita values for gross domestic product (GDP) expressed in current international dollars converted by purchasing power parity (PPP) conversion factor. GDP is the sum of gross value added by all resident producers in the country plus any product taxes and minus any subsidies not included in the value of the products. conversion factor is a spatial price deflator and currency converter that controls for price level differences between countries. Total population is a mid-year population based on the de facto definition of population, which counts all residents regardless of legal status or citizenship.


### Source: 
International Comparison Program, World Bank | World Development Indicators database, World Bank | Eurostat-OECD PPP Programme.
### License:  
CC BY-4.0 
### Aggregation Method: 
Weighted average
### Long Definition: 
This indicator provides per capita values for gross domestic product (GDP) expressed in current international dollars converted by purchasing power parity (PPP) conversion factor. GDP is the sum of gross value added by all resident producers in the country plus any product taxes and minus any subsidies not included in the value of the products. conversion factor is a spatial price deflator and currency converter that controls for price level differences between countries. Total population is a mid-year population based on the de facto definition of population, which counts all residents regardless of legal status or citizenship.
### Periodicity: 
Annual
### Statistical Concept and Methodology: 
Typically, higher income countries have higher price levels, while lower income countries have lower price levels (Balassa-Samuelson effect). Market exchange rate-based cross-country comparisons of GDP at its expenditure components reflect both differences in economic outputs (volumes) and prices. Given the differences in price levels, the size of higher income countries is inflated, while the size of lower income countries is depressed in the comparison. PPP-based cross-country comparisons of GDP at its expenditure components only reflect differences in economic outputs (volume), as PPPs control for price level differences between the countries. Hence, the comparison reflects the real size of the countries. For more information on underlying GDP in current international dollar, please refer to the metadata for "GDP, PPP (current international $)" [NY.GDP.MKTP.PP.CD]. For more information on underlying population, please refer to the metadata for "total population” [SP.POP.TOTL]. For the concept and methodology of PPP, please refer to the International Comparison Program (ICP)’s website (worldbank.org/en/programs/icp).

## GDP per capita, PPP (constant 2021 international $) - ID: NY.GDP.PCAP.PP.KD
Path: API_NY.GDP.PCAP.PP.KD_DS2_en_csv_v2_1588678

GDP per capita based on purchasing power parity (PPP). PPP GDP is gross domestic product converted to international dollars using purchasing power parity rates. An international dollar has the same purchasing power over GDP as the U.S. dollar has in the United States. GDP at purchaser's prices is the sum of gross value added by all resident producers in the country plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant 2021 international dollars.

### Source: 
International Comparison Program, World Bank | World Development Indicators database, World Bank | Eurostat-OECD PPP Programme.
### License:  
CC BY-4.0 
### Aggregation Method: 
Weighted average
### BasePeriod: 
2021
### Long Definition: 
GDP per capita based on purchasing power parity (PPP). PPP GDP is gross domestic product converted to international dollars using purchasing power parity rates. An international dollar has the same purchasing power over GDP as the U.S. dollar has in the United States. GDP at purchaser's prices is the sum of gross value added by all resident producers in the country plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant 2021 international dollars.
### Periodicity: 
Annual
### Statistical Concept and Methodology: 
For the concept and methodology of PPP, please refer to the International Comparison Program (ICP)’s website (worldbank.org/en/programs/icp).

## GDP per capita (current LCU) - ID: NY.GDP.PCAP.CN
Path: API_NY.GDP.PCAP.CN_DS2_en_csv_v2_2789032

GDP per capita is gross domestic product divided by midyear population. GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in current local currency.

### Source: 
World Bank national accounts data, and OECD National Accounts data files.
### License:  
CC BY-4.0 
### Long Definition: 
GDP per capita is gross domestic product divided by midyear population. GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in current local currency.
### Periodicity: 
Annual

## GDP (constant 2015 US$) - ID: NY.GDP.MKTP.KD
Path: API_NY.GDP.MKTP.KD_DS2_en_csv_v2_2788945

GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant 2015 prices, expressed in U.S. dollars. Dollar figures for GDP are converted from domestic currencies using 2015 official exchange rates. For a few countries where the official exchange rate does not reflect the rate effectively applied to actual foreign exchange transactions, an alternative conversion factor is used.


### Source: 
World Bank national accounts data, and OECD National Accounts data files.
### License:  
CC BY-4.0 
### Aggregation Method: 
Gap-filled total
### Development Relevance: 
An economy's growth is measured by the change in the volume of its output or in the real incomes of its residents. The 2008 United Nations System of National Accounts (2008 SNA) offers three plausible indicators for calculating growth: the volume of gross domestic product (GDP), real gross domestic income, and real gross national income. The volume of GDP is the sum of value added, measured at constant prices, by households, government, and industries operating in the economy. GDP accounts for all domestic production, regardless of whether the income accrues to domestic or foreign institutions.
### BasePeriod: 
2015
### Limitations and Exceptions: 
Each industry's contribution to growth in the economy's output is measured by growth in the industry's value added. In principle, value added in constant prices can be estimated by measuring the quantity of goods and services produced in a period, valuing them at an agreed set of base year prices, and subtracting the cost of intermediate inputs, also in constant prices. This double-deflation method requires detailed information on the structure of prices of inputs and outputs. In many industries, however, value added is extrapolated from the base year using single volume indexes of outputs or, less commonly, inputs. Particularly in the services industries, including most of government, value added in constant prices is often imputed from labor inputs, such as real wages or number of employees. In the absence of well defined measures of output, measuring the growth of services remains difficult. Moreover, technical progress can lead to improvements in production processes and in the quality of goods and services that, if not properly accounted for, can distort measures of value added and thus of growth. When inputs are used to estimate output, as for nonmarket services, unmeasured technical progress leads to underestimates of the volume of output. Similarly, unmeasured improvements in quality lead to underestimates of the value of output and value added. The result can be underestimates of growth and productivity improvement and overestimates of inflation. Informal economic activities pose a particular measurement problem, especially in developing countries, where much economic activity is unrecorded. A complete picture of the economy requires estimating household outputs produced for home use, sales in informal markets, barter exchanges, and illicit or deliberately unreported activities. The consistency and completeness of such estimates depend on the skill and methods of the compiling statisticians. Rebasing of national accounts can alter the measured growth rate of an economy and lead to breaks in series that affect the consistency of data over time. When countries rebase their national accounts, they update the weights assigned to various components to better reflect current patterns of production or uses of output. The new base year should represent normal operation of the economy - it should be a year without major shocks or distortions. Some developing countries have not rebased their national accounts for many years. Using an old base year can be misleading because implicit price and volume weights become progressively less relevant and useful. To obtain comparable series of constant price data for computing aggregates, the World Bank rescales GDP and value added by industrial origin to a common reference year. Because rescaling changes the implicit weights used in forming regional and income group aggregates, aggregate growth rates are not comparable with those from earlier editions with different base years. Rescaling may result in a discrepancy between the rescaled GDP and the sum of the rescaled components. To avoid distortions in the growth rates, the discrepancy is left unallocated. As a result, the weighted average of the growth rates of the components generally does not equal the GDP growth rate.
### Long Definition: 
GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant 2015 prices, expressed in U.S. dollars. Dollar figures for GDP are converted from domestic currencies using 2015 official exchange rates. For a few countries where the official exchange rate does not reflect the rate effectively applied to actual foreign exchange transactions, an alternative conversion factor is used.
### Periodicity: 
Annual
### Statistical Concept and Methodology: 
Gross domestic product (GDP) represents the sum of value added by all its producers. Value added is the value of the gross output of producers less the value of intermediate goods and services consumed in production, before accounting for consumption of fixed capital in production. The United Nations System of National Accounts calls for value added to be valued at either basic prices (excluding net taxes on products) or producer prices (including net taxes on products paid by producers but excluding sales or value added taxes). Both valuations exclude transport charges that are invoiced separately by producers. Total GDP is measured at purchaser prices. Value added by industry is normally measured at basic prices. When value added is measured at producer prices. Growth rates of GDP and its components are calculated using the least squares method and constant price data in the local currency. Constant price U.S. dollar series are used to calculate regional and income group growth rates. Local currency series are converted to constant U.S. dollars using an exchange rate in the common reference year.

