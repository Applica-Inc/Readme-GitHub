### Layout para la tabla de member de todos los clientes
#
# Member Schema 					

| Field Name    | Type     | Len | Index | Description         | Comment             |
|---------------|:--------:|:---:|:-----:|:--------------------|:--------------------|
|MemberId       | Varchar  | 13  |  Yes  | Member Number       | Key                 |
|FirstName      | Varchar  | 30  |       | First Name          |                     |
|MiddleName     | Varchar  |  1  |       | Middle Name         |                     |
|LastName       | Varchar  | 30  |       | Last Name           |                     |
|BirthDay       | DateTime |  8  |       | BirthDay            |                     |
|Dependent      | Varchar  |  2  |       | Dependent           |                     |
|Company        | Varchar  | 10  |       | Company             | MMM, SSS, MCS, etc. |
|Address1       | Varchar  |100  |       | Location Address    |                     |
|Address2       | Varchar  |100  |       | Location Address    |                     |
|City           | Varchar  | 20  |       | Location City       |                     |
|State          | Varchar  |  2  |       | Location State      |                     |
|ZipCode        | Varchar  |  5  |       | Location Zip Code   |                     |
|ZipPlus4       | Varchar  |  4  |       | Location Zip Plus 4 |                     |
|DateUpDate     | DateTime |  8  |       | Record Update       | In Applica          |
|DateInsert     | DateTime |  8  |       | Record creation date|                     |
|FileName       | Varchar  |200  |       | File Name           |                     |

| Record Len    |
|:-------------:|
| 538
