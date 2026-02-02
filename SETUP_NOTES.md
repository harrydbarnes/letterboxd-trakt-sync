# Setup Notes

## Configuration
A `config.yml` file has been created in the local environment with the provided credentials.

**IMPORTANT:**
- The `letterboxd_username` has been updated to `harrydevereux`.
- `config.yml` is **not** committed to the repository for security reasons (it contains secrets).
- A `config.yml.example` file has been added to the repository as a template.

## Execution
The sync script was successfully executed in the environment.
To run it again, use:
```bash
python -m letterboxd_trakt.main
```
Note: You must run it as a module (`python -m letterboxd_trakt.main`) to avoid import errors.

## Dependencies
Dependencies were installed from `requirements.txt`.
