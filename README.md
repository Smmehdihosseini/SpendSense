# SpendSense

### Financial Manager and Assistant

- Digitalize receipts
- Keep track of payments
- Get periodical statistics
- Get nutricious tips (Further Updates > 2)
- Analyze price of products in different stores (Further Updates > 3)
- Recommendation for best prices over all markets (Further Updates > 3)
- Synchronization with local markets (Further Updates > 3)

### Functional Requirements
- Receipt Image > Standard Payment Details
- Data Storage, Handling and Processing
- Accesible for multiple users


### Diagram

1 - Input (Receipt Image, File or Text From User)
1* - User Settings
2 - Converting all types of formats into JSON structured data.
3 - Check the processed info by user for validation
4 - Store the related information into the database for each user respectively.


### Technical Requirements

- Image Optical Character Recognition (OCR) Model: Converting user receipts to JSON-based format.
- Data Storage: Storing all the information into a secure database (MongoDB)
