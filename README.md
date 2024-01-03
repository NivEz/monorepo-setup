# Monorepo Setup
Simple monorepo setup for Node.js projects with `yarn workspaces`, `prettier` and `pre-commit` hook.

* Simply clone the repo and change the name and author in the `package.json`:
```
git clone https://github.com/NivEz/monorepo-setup.git <prject name>
```

* To initialize new `git` simply delete the `.git` hidden folder and use the command `git init`.

* To install the dependencies just use the command `yarn`.

* You can edit / delete this `README.md` file.


### Adding a workspace:
1. Create a new directory named packages.
2. Inside packages create another directory for your wanted workspace.
3. Use `yarn init` or `yarn init -y` to initialize yarn.
4. Inside the `package.json` of the new package you can change the `name` field to your desired workspace name. 