# Salesforce REST API Integration Demo (Cat Fact API)

This simple project shows how to integrate Salesforce with a public REST API using:
- Named Credentials
- Apex Callouts
- Autolaunched Flow
- Quick Action Button

💡 The API used: [https://catfact.ninja](https://catfact.ninja)

🧩 Built for my YouTube tutorial: [Integration with Salesforce](https://youtube.com/@Integrationwithsalesforce)

## Components
- `CatFactService.cls`: Apex class for API call
- `Flow_CatFact_Update`: Flow to update Contact with result
- Custom Field: `Cat_Fact__c` on Contact

## How to Use
1. Add the Named Credential `CatFact_API`
2. Deploy the Apex class and Flow
3. Add a Quick Action button on Contact
4. Click to fetch a random cat fact!
