# FMu
Dataset of Funding Applications for the Chilean Ministry of Culture&#39;s Music Grant (Fondos de la Música) (2012-2023).

It consists of 28040 entries (one per fund application) and 24 variables:
- 'ID': unique identifier of the application (produced by Animupa)
- 'Año': year of the application
- 'Clasificación Animupa': musical genre classification, done by Animupa's data team according to the information given in three other variables (namely 'Línea', 'Modalidad', and 'Submodalidad',)
- 'Clasificación gpt-4o': musical genre classification by AI model Chat GPT-4o through OpenAI's API, using the application's title ('Nombre proyecto')
- 'Música de arte': whether the application has been classified as art music by either Animupa's data team or Chat GPT-4o
- 'Nombre proyecto': title describing the project
- 'Seleccionado': whether the application was selected or not
- 'Monto solicitado': amount request by the applicant
- 'Monto adjudicado': amount effectively granted, if the project was selected
- 'Ajuste presupesto': difference between requested amount and granted amount 
- 'Tipo de persona': whether the applicant is a physical person or a legal entity
- 'Tipo de entidad jurídica': type of legal entity if applies
- 'Región del proyecto': region of the application
- 'Folio': identifier of the application, attributed by the Chilean ministry of Culture
- 'Línea': Category of the application
- 'Modalidad': 1st level sub-category of the application
- 'Submodalidad': 2nd level sub-category of the application
- 'Elegibilidad': whether the application was regarded as eligible by the jury
- 'Nota del proyecto': grade attributed to the application by the jury
- 'Monto total del proyecto': estimation of the total amount needed for the project
- 'Total aportes': amount brought by the applicant
- 'Gastos de honorarios': professional fees
- 'Gastos de operación': operational fees
- 'Gastos de inversión': investment fees 

## Source

The data was produced by the Chilean ministry of Culture, and structured by Animupa's data team for better analysis and data visualization. It was obtained through the Chilean public transparency law.

## Licence

This dataset and associated code in the repository are distributed under the CC BY-NC 4.0 license.
