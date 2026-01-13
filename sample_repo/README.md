### API / Usage
Based on the provided DIFF, it appears that multiple API routes have been modified. However, without the specific details of the patches, I will provide a general outline of how the API section could be updated. 

Given the files modified, it seems the changes are related to authentication and layout management. Here's an example of how the API section might look, assuming new endpoints or modifications to existing ones have been made:

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/auth`  | POST   | JWT login   |
| `/login` | POST   | User login  |
| `/recover-password` | POST | Recover password request |
| `/reset-password` | POST | Reset password |
| `/signup` | POST | User registration |
| `/settings` | GET/POST | User settings management |
| `/items` | GET/POST | Item management |
| `/admin` | GET/POST | Admin dashboard |

Please note, the actual endpoints, methods, and descriptions should be updated based on the specific changes made in the patches. This example is a placeholder based on the file names provided in the DIFF.

For a complete and accurate update, the specific changes in each patch file should be reviewed and reflected in the API documentation. 

### Example Use Cases

- **Login**: To login, send a `POST` request to `/login` with the user's credentials.
- **Reset Password**: To reset a password, first send a `POST` request to `/recover-password` with the user's email, then follow the instructions sent to reset the password via `/reset-password`.

### Important

- Ensure all endpoints are correctly documented with their respective HTTP methods and descriptions.
- If any authentication tokens or specific headers are required for certain endpoints, this should be clearly documented.
- Consider adding examples of request and response bodies for each endpoint to enhance clarity.