## Contributing to this repo

### Add your update to UPDATES.md

1. Clone this repository:

	```bash
	git clone <repo-url>
	cd <repo-directory>
	```

2. Create a separate branch for your change:

	```bash
	git switch -c add-your-team-update
	```

3. Open the repository's `UPDATES.md` file and add your team's update there. Follow the existing format in the list and do not edit unrelated content.

4. Stage and commit the change:

	```bash
	git add UPDATE.md
	git commit -m "Added update on Team##_TeamName"
	```

5. Push your branch:

	```bash
	git push -u origin add-your-team-update
	```

6. Open a pull request from your branch to the repository's main branch. Include a short description of the change and submit it for review.
