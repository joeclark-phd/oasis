Oasis Business Rules & ER Diagram
==============

Business Overview
----------------------

This document describes the requirements for a database for a car insurance companies like State Farm, Progressive, Essurance. It includes polices, policies transactions, coverage's types, etc.

Business rules
-----------------

- 1:  A customer can have zero or more policies;
- 2:  A vehicle must be owned by one and only one customer;
- 3:  Every vehicle must have one and only one model;
- 4:  A policy transaction must have a customer, a employee and a vehicle;
- 5:  A person must have a SSN, address and name;
- 6:  A customer must have a phone;
- 7:  A employee have only one job title;
- 8:  A person can have zero or more cars;
- 9:  A person can be a employee or exclusive a customer;
- 10: Every employee have a job title;
- 11: Only insurance broker can create a policy;
- 12: A policy can have one or more types of coverage;
- 13: The attribute SSN is unique;
- 14:  A model must have a brand;
- 15: The insurance broker can create zero or more policies;
- 16: A person can make zero or more transactions;



ER Diagram
--------------

![ER diagram](http://s24.postimg.org/ndn9yf79h/ermodel_2.jpg)
