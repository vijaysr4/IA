# IA

The quotation files are shared and received via mail platform. In order to 
processes these quotations, one must first extract these files from the 
received mail by fetching the mail address. The following issues to 
addressed.
- Addressing the issue of different response quotation file format.
- Automated mail scrapping.
- User friendly interaction.
The quotation response from each company will be in excel format. Prior 
the data from these excel was manually entered in companies ERP portal. 
For the automation process, the excel format should be changed to a 
computationally feasible format (.csv extension). 
The process of getting the response file will be parsed through the website 
and further, it should be changed to a .csv extension. In between, there are 
the following issues to be addressed.
- Excel cells have commas in them. While converting to a .csv extension the 
cells will get split with respect to commas.
- Merged cells in the excel, while converting the .csv extension will result in 
ambiguity.
- Whitespaces columns in processed CSV. It will be difficult while process 
and extract information from the CSV.
- The issue in reusing the quotation template as a generalized format.
- Changing specific cell values in excel directly for changing address

The above problems should be addressed cautiously before processing the 
quotations.
After the processing the quotation to required .csv format, the following 
issues to addressed in order to process the final csv.

- Extracting the main table from csv.
- Computing the amount for quoted products.
- Creating new final csv with consolidated quotations.
