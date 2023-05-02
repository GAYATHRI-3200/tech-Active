# tech-Active

Task Description:

1. Create an API to generate OAuth access-token.

Conditions:
a) Expires after 3 minutes and needs to be re-generated.

2. Create an API to insert User-details.

Conditions:
a) Params: f_name, l_name, email_id (Unique), phone_number, address. Also, store the created_date.
b) Access-token should be sent through Request-Headers.
c) API should be limited to 5 calls per minute.

3. Create an API to list Users.

Conditions:
a) Access-token should be sent through Request-Headers.
b) Should have pagination, sorting filters (based on created_date). Pagination should contain, next-url/prev-url.
c) Should be limited to 5 calls pers minute.

Frontend -

1. A sample form to add user-details, with validations using JS(none can be empty).
2. A table list with the users, with pagination used from API along with sorting filters (ASC/DESC).

- Jquery/JS based arrow key navigation to each list. (highlight the first row on page-load, should be moveable up/down using arrow-keys)

Please note:
Appropriate Error messages to the user should be prompted in UI.
If error is of access-token expiry, a new token should be created and used again.
