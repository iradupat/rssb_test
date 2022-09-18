# RSSB TEST Back-end 1

## REQUIREMENTS

### Build a REST API-based backend system that does this:

    ○ Add endpoint to receive a file of 50,000 users. (Excel file generated on your end).
    
    ○ Each record of the file has dummy Names, NID, phone number, gender,email.
    
    ○ Validate each record, (as sometimes NID is not valid, phone number is incorrect, etc,) and be keep validation failure.

    ○ Do not store the uploaded list on a disk-based storage.
    
    ○ Add a new endpoint to display the uploaded list with its validation failure for each record. (This endpoint will be used by the front-end to display paginated results).

    ○ Add endpoint to be called in other to commit the list uploaded in a SQL database

    ○ All these endpoints need to be accessible only via a JWT Token-based authentication.