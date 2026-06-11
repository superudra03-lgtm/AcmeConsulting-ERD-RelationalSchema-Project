Acme Consulting (AC Inc) is a consulting company. The company is in need of an operational database to facilitate the transition to data-informed decision-making paradigm and manage the business more effectively and efficiently. The company’s employees are composed of consultants, supervisors, and project managers. 

The operational database will keep track of the following: 

• For each consultant: a unique identifier, consultant name (composed of first name, middle initial, last name), start date with the company, the number of years with the company, skills that the consultant has (one or multiple skills); 

• For each project manager: a unique identifier, project manager name (composed of first name, middle initial, last name), start date with the company, the number of years with the company, PMP Certified (Yes/No) 

• For each customer: a unique custid, well as the customer’s name composed of the customer’s first, middle initial, and last name, and a phone number; 

• For each supervisor: a unique identifier, name (composed of first name, middle initial, last name), start date with the company, the number of years with the company, number of supervised contracts, and (if supervisor owns AC Inc. stock) number of stocks owned. (Not every supervisor owns AC Inc. stock.) 

• For each contract: a contract id, contract start date, estimated contract length (in days), estimated contract end date, actual contract end date, and actual contract length (in days). Two or more contracts can have the same contract id, but all contracts for the same customer will have different contract ids. 

• Each contract is managed by exactly one project manager. A project manager manages one contract or no contracts at all. 

• Each contract has at least five consultants assigned to it. A consultant is assigned to one contract. 

• A customer has at least one contract but may have many. Each contract is associated with one customer. 

• Each contract is supervised by exactly one supervisor. Each supervisor must supervise at least one contract but can supervise many contracts. 

• Each supervisor has one or more consultants assigned as administrative helpers. A consultant can be assigned as an administrative helper to between zero and many supervisors. We keep track of how many hours per week a particular consultant is working as an administrative helper for a particular supervisor. 

Deliverable 1: Developing an Entity-Relationship-Diagram for the business requirements defined above using ERDPlus. 

Deliverable 2: Develop a Relational Schema for the ERD (the conceptual data model) you developed in Deliverable 1 using ERDPlus. 
