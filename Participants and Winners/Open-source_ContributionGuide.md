Judges Remarks: 

Durwasa Chakraborty: I really hope many of the participants keep at it.  Gsoc should be the great next step: pick, start contributing to their repos now, talk to the maintainers, and your proposal will be far stronger when applications open. Happy to help anyone who wants to give it a shot.


- ## **Open-source contribution guide**
	- **Find a project**
		- Browse beginner-friendly labels such as `good first issue`, `beginner`, or `help wanted` on GitHub.
		- Pick a project whose language and tech stack you know or want to learn; check its README and setup instructions.
		- Check recent commits, releases, issue responses, and community channels to see whether it is maintained and welcoming contributors.
		- Review open issues, contribution guidelines, code of conduct, and the project's AI-use policy before delving into contributing.
		- Confirm you can install dependencies and run the project and its tests before working on it :)
	- **Choose an issue**
		- Check that it is still relevant and has no assignee, no linked pull request, or active fork/branch already working on it.
		- Read the discussion and verify the issue is in scope; ask a concise question or request assignment to the maintainer if the project asks you to.
		- No suitable issue? Run the project, explore, and report a reproducible bug or propose a focused improvement before starting work.
	- **Work on the issue**
		- Read the README, contribution guide, related code, and tests; understand the expected behavior before editing.
		- Reproduce the issue first when possible. Make the smallest focused change and add or update tests and documentation as needed.
		- Run the documented checks (tests, lint, formatting, build) and review your diff for unrelated edits, secrets, and generated files.




        .
	- **Git and pull-request steps**
		- Fork the repository, then clone your fork: `git clone <your-fork-url>`.
		- Enter the project: `cd <repo>`; add the original repository as upstream: `git remote add upstream <original-url>`.
		- Create a branch: `git switch -c fix/short-description`.
		- Make changes; inspect them with `git status` and `git diff`.
		- Stage and commit: `git add <files>` then `git commit -m "Fix: short description"`.
		- Sync if needed: `git fetch upstream` and update your branch from the project's default branch according to its contribution instructions.
		- Push your branch: `git push -u origin <branch>`; open a PR against the correct upstream branch.
		- Link the issue in the PR (for example, `Fixes #123`), summarize the change, list tests run, and respond politely to review feedback.


        ---

	- **Things to do after the hackathon**
		- Check whether the project expects a cleanup PR; remove `README-MachZero`.
		- Open a focused PR, link the relevant issue, and leave one clear comment with context; don't submit duplicate PRs.
		- Keep the repository usable: update setup/docs if needed and remove temporary files, credentials, and unused dependencies, environment you've ran it through.

        ---

## **> Beginner Contributor Do's and Dont's**
**Do**
- Follow the project's AI policy; disclose AI assistance when required and verify every suggestion, test, and license.
- Read project instructions before asking questions; provide useful details, logs, steps to reproduce, and your environment.
- Be patient and respectful—maintainers are often volunteers with limited time. Thank reviewers and accept that a PR may be declined :)
- Keep communication and commits focused; ask before taking on large or ambiguous work.

**Don't**
- Don't ignore review feedback, force unrelated changes into a PR, or claim work you didn't do.
- Don't post repeated pings, demand reviews, or open issues for questions already answered in the docs.
- Don't include secrets, personal data, unlicensed code, or AI-generated changes you cannot explain.(!!)



    - ## **Some beginner resources**
		- GitHub Issues search: https://github.com/issues (filter by labels such as `good first issue`).
		- Good First Issue: https://goodfirstissue.dev/ ; Up For Grabs: https://up-for-grabs.net/ ; CodeTriage: https://www.codetriage.com/.
		- First Contributions: https://firstcontributions.github.io/ ; Open Source Guides: https://opensource.guide/how-to-contribute/.
		- GitHub docs: https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project.
		- https://kernelnewbies.org/KernelJanitors
		


Good Luck! May the source be with you :)

