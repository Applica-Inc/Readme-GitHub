### Layout para la tabla de provider de todos los clientes
#
# Provider Schema 					

| Field Name    | Type     | Len | Index | Description         | Comment   |
|---------------|:--------:|:---:|:-----:|:--------------------|:----------|
|Key            | Varchar  | 20  |       | Npi + PayeeNpi      |           |
|ProviderId     | Varchar  | 10  |       | ID in MMM           | Only MMM  |
|Npi            | Varchar  | 10  | Yes   | Npi Number          |           |
|PayeeNpi       | Varchar  | 10  |       | Federal tax id      |           |
|TaxonomyCode   | Varchar  | 10  |       | Taxonomy Code       |           |
|FirstName      | Varchar  | 30  |       | Provider Name       |           |
|MiddleName     | Varchar  |  1  |       | Middle Name         |           |
|LastName       | Varchar  | 30  |       | Last Name           |           |
|Address1       | Varchar  |100  |       | Location Address    |           |
|Address2       | Varchar  |100  |       | Location Address    |           |
|City           | Varchar  | 20  |       | Location City       |           |
|State          | Varchar  |  2  |       | Location State      |           |
|ZipCode        | Varchar  |  5  |       | Location Zip Code   |           |
|ZipPlus4       | Varchar  |  4  |       | Location Zip Plus 4 |           |
|MailingAddress1| Varchar  |100  |       | Postal Address1     |           |
|MailingAddress2| Varchar  |100  |       | Postal Address2     |           |
|MailingCity    | Varchar  | 20  |       | Postal City         |           |
|MailingState   | Varchar  |  2  |       | Postal State        |           |
|MailingZipCode | Varchar  |  5  |       | Postal ZipCode      |           |
|MailingZipPlus4| Varchar  |  4  |       | Postal Zip Plus 4   |           |
|DateUpDate     | DateTime |  8  |       | Record Update       | In Applica|
|DateInsert     | DateTime |  8  |       | Record creation date|           |
|FileName       | Varchar  | 200 |       | File Name           |           |

| Record Len  |
|:-----------:|
|    799      |
