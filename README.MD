#Welcome to Geographr
This repository contains data and analysis scripts related to geographic data in Wales
##Contents
welsh_greenspace.csv: Dataset containing the greenspace information for Welsh counties, data was collected from [Fields in Trust] (https://fieldsintrust.org) , on their GSI index map, based upon the Ordinance Survey's data for greenspaces around the UK. This index is updated annually, during late May/early June. They have omitted some forms of greenspaces, such as private greenspaces (private gardens, golf courses, allotments ect.) and also have removed overlaps in data such as playgrounds inside parks, removing the smaller in favour of the latter as to not accidentally count a space twice. This also applies for sports complex that are next to eachother, such as a tennis court next to a squash court or that can double as either. 
### Acronym Explanations

* **GSI (Green Space Index)**: A measure created by Fields in Trust to quantify publicly accessible park and green space provision.
* **PPP (Provisions per Person)**: A metric indicating the amount of greenspace available per person in a given area. This was revised by Fields in Trust in 2015 to be for every 1000 people, there should be approx. 2.4 ha of acessible land. The land is measured in sqm.
* **N10**: Population not within a 10 minute walk of a greenspace.
* **NUTS1 (Nomenclature of Territorial Units for Statistics level 1)**: A geocode standard for referencing the subdivisions of countries for statistical purposes in the European Union.
* **POP (Population Projection 2024 )**: Projected number of people in an area in 2024.
* **MIN (Does this area meet the minimum requirement for PPP)**: A binary indicator where 0 indicates 'No' and 1 indicates 'Yes'.
#### Contributer: Zara-Morgan Oluwole 
