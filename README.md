# Welcome to the foundry repo!

## What is foundry?
In the past, DevOps oversaw the deployment pipeline from GitHub to Travis CI to Raspberry Pi boards.
This is the archive of DevOps tools.

## Contributing to foundry
Note: You don't have to fork!
Instead, make your own branch in the repo once you join the organization.

### Setting up PieCentral
```sh
$ cd "<directory of your choice>"
$ git clone https://github.com/pioneers/foundry.git
$ cd foundry
```

### Creating a Branch
Follow the naming convention `<feature>`.
```sh
$ git checkout master  # Switch to default `master` branch
$ git checkout -b "<feature>"  # Create and switch to feature branch
$ git push -u origin "<feature>"
```

### Adding new code to master
Make sure any local changes to your code is pushed to your branch.

```sh
$ git add "<file1>" "<file2>"
$ git commit -m "<description>"
$ git push  # Pushes to `origin/<feature>` because of `-u` flag earlier
```

Open a pull request to `master`. Code will be reviewed by PMs.

Code will be squashed and merged onto master.
(Choose "Squash and Merge" instead of "Create a merge commit".)
Make sure when merging your pull request you include a useful commit header and message.
