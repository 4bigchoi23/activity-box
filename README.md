<p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/10660468/54498934-19415980-48e3-11e9-8f17-1e91a475befe.png">
  <h3 align="center">activity-box</h3>
  <p align="center">⚡️📌 Update a pinned gist to contain the latest activity of a user</p>
</p>

---

## Setup

### Prep work

1. Create a new public GitHub Gist (https://gist.github.com/)
2. Create a token with the `gist` scope and copy it. (https://github.com/settings/tokens/new)

### Project setup

1. Fork this repo
2. Log into CircleCI with your GitHub (https://circleci.com/vcs-authorize/)
3. Click on "Add Projects" on the sidebar
4. Set up a project with the newly created fork
5. Go to Project Settings > Environment Variables
6. Add the following environment variables:

- **GIST_ID:** The ID portion from your gist url `https://gist.github.com/matchai/`**`6d5f84419863089a167387da62dd7081`**.
- **GITHUB_TOKEN:** The GitHub token generated above.
- **GITHUB_USERNAME:** The username handle of the GitHub account.

---

_Inspire by [matchai/bird-box](https://github.com/matchai/bird-box)_