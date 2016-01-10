###Dataset For IndiaSpend's Patents Articles, Jan 2016###

If all you want is the data, [complete_data_set.csv](complete_data_set.csv) is the file to download. (The rest of the files are just the csv's used to generate the graphics for the copy.)

Most of the column labels in [complete_data_set.csv](complete_data_set.csv) are self-explanatory, but some of them are my own, so thought I'd explain them in case it gets a little confusing. 

**years_gap_bw_app_grant** stands for the no. of years between the application date of a patent and the date it was finally granted.

**applicant_Indian column** has TRUE/FALSE values based on whether the search string "*nationality: IN*" is found in the respective cell of the **applicant_unparsed** column. This is how I found whether an inventor is Indian or not. 

**inventor.address.1st** has the addresses of the inventors who got first mention in the respective cell of the **inventor.address.actual column**, in case there's more than one inventor. This column's useful for finding out which CSIR & DRDO labs were responsible for most of their parent organisation's patents.

**applicant.name.1st** has the name of the inventor who gets first mention in the respective cell of the **applicant.name.actual** column. This column was used to find out which organisation had the most patents granted to Indian inventors. 

(**Disclaimer**: The information here is being provided in the interest of transparency. It cannot be treated as official IndiaSpend content.)





 



