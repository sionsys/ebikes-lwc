## Security

Please report any security issue to [security@salesforce.com](mailto:security@salesforce.com)
as soon as it is discovered. This library limits its runtime dependencies in
order to reduce the total cost of ownership as much as can be, but all consumers
should remain vigilant and have their security stakeholders review all third-party
products (3PP) like this one and their dependencies.



## Project Implementation Security Analysis ### FLS and CRUD Enforcement - **Object**: `Product__c` - **Field**: `Year__c` - **Pattern**: Field-Level Security (FLS) has been enforced via the standard project Permission Set. - **LWC Binding**: Lightning Web Components `productCard` and `productFilter`) utilize standar