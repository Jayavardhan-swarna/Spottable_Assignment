# Spottable_Assignment
For this assignment, you’ll be provided with a dataset of companies as a list of JSON objects. Each object holds relevant data for a company. The fields are described below:

tags: the domains company operates in

companyName: synonyms of the company

domainName: extracted from the company website’s URL.

companyDesc: a short description of the company's operations

fundingList: details regarding the company’s funding rounds

crunchbase_url: URL to the company’s Crunchbase page

employeeNumber: number of employees in the company at the time data was extracted

foundedDate: date the company was founded on

companyWebsite: URL to company’s website

domain_groups: listing out possible groups the company may belong to. (this is our internal classification, may not be accurate)

TYPE: another internal classification (for product, and service-based companies), may not be accurate

You’ll be required to
given a company name (similar to ones present in companyName), return the close competitors of the company, using any of the fields (or combination of fields) from the dataset. For example, competitors of Swiggy would be Zomato, FoodPanda, DoorDash, etc. Since all of them operate in similar domains and offer similar services.

Given a domain (any one of the domains in ‘tags’ field), present the companies with the fastest, and the slowest growth (hint: it may be based on the fundingList, foundedDate, etc)
