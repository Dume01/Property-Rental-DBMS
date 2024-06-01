# Property Rental Agency (PRA) Database Project

This project is based on the specifications provided in the DBS Project Specs (1).pdf file for the CSF 212 (Database Systems) course during the 2nd Semester of 2022-23. The project focuses on ER/EER Modeling, Relational schema design and refinement (Normalization), implementing the database (creating tables with constraints and inserting initial data necessary), and writing SQL/PL-SQL code for data entry, updates, generating reports, manipulation, and enforcing certain complex constraints or rules.

## Project Description

The Property Rental Agency (PRA) scenario involves an agency that facilitates mediating between Owners of properties and Tenants across multiple cities in India. Both Owners and Tenants are treated as users of the system. There is a super user (DBA) who can add, delete, and modify other users. Managers can add, modify, and delete properties, as well as add details about which property is rented to which tenant. Some users can play both owner and tenant roles, meaning they can give their property for rent and seek another property from others for rent.

Properties can be residential (independent houses or flats) or commercial (shops or warehouses). Each property has a unique ID and an owner. Users have Aadhaar IDs, names, ages, addresses (including door number, street, city, state, and PIN code), and multiple phone numbers. All users have login credentials.

Owners can register properties they want to give for rent. Once a property is rented to a tenant, details like the rented property, tenant, rent per month, start date, end date, yearly rent hike percentage, agency commission, and other necessary information are captured. Properties may not have tenants if they are not rented, and the rental history for each property is maintained.

Properties are entered into the system with details such as property ID, owner, availability dates, rent per month, annual rent hike percentage, total area, plinth area, number of bedrooms (for residential properties), number of floors, year of construction, locality, address, and other facilities.

## Functionality

The project includes the following functionality:

1. Adding users to the database by the DBA with necessary privileges.
2. Allowing the DBA and Managers to add, delete, and update property records.
3. Allowing owners to add, delete, and update their property records only.
4. Allowing the Admin and Managers to add property-rent details after a property is rented by a tenant.
5. Generating a report on the rent history of a property.
6. Checking the list of available properties for rent within a given city, locality, or price range.
7. Checking the status of a property based on the property ID by all users.
8. Tenants can only look for available properties for rent and cannot insert, delete, or modify any data in any table.
