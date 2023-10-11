# Submodules

For submodules in projects you want to make sure that you have a .gitmodules file properly pointing it's url to the repository you want as a submodule.

Example:
```bash
[submodule "google_test"]
	path = google_test
	url = ../google_test.git
```
