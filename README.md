# ETL-Customer-and-product-data

My Observations: 1-CDWAE-assessement:
● The file seem to contain names of customers
● The names seem to be coming from different countries as some had non ascii characters this will be normalized using unidecode
● Some Names had numbers and punctuation marks
● The letters of some names were mixed up maybe due to typo error, eg, ‘J’ for ‘I’ and ‘Y’ for ‘B’, etc. This typos error are not cut across all data points and may have happened across sequence of characters per data point in some instances
● Some names were all in capital letter, while some had capital letters in between
● The phone numbers are in different formats. Some phone numbers / mobile numbers were either longer or shorter than the ideal length for each specific country hence invalid
● Some names have the same number as phone number and mobile number which could mean that users mixed up or duplicated phone and mobile numbers.
● Most names had no mobile numbers
● Some users had same names but different ids hence were not considered duplicates
2-CDWAE-assessement:
● The JSON object seems to contain information about a medical scan such as the date and time, the type of probe used, and the institution where the scan took place.
● The also contains information about the device used to perform the scan, such as the screen height and width, and the number of pixels per millimeter.
● The file tends to represent one unique scan/capture
● Each Json object/string represents a data point of the scan/capture


ETL-ed customer data from different countries, with different phone number formats, different languages, non ascii characters, numbers and punctuation marks in between names, typo errors and duplicated data
ETL-ed Json type product data from a digital Xray machine into a structured  format.
