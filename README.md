# [Octet Game Server](https://octet-yg.org) 



Repository for downloading Octet's binary releases, issues and localization improvements. 



## Binaries

Octet releases are available in [Releases](https://github.com/Winterr1337/octet-bin/releases/tag/Release). Please be sure to check out the documentation, as it explains in detail the process of installing, configuring and using Octet.


## Issues

If you encounter any error or bug while using Octet, or you want to submit a suggestion, first search the issues to see if it has already been reported. Be sure to search for closed issues.

If not reported, submit a new issue with the following details:

 - a short title;
- a detailed description of the problem, along with output from the console and logs on [gist](https://gist.github.com/).
- steps to reproduce the issue
- host system information (System, Java Version, MySQL Version if the problem is related to database operations).

Include console output & logs in a [gist](https://gist.github.com/) and link to them to your report.



## Contributing

For the moment, you can participate in the project by improving the localization of CLI, system messages and episodes.



## How to contribute

1. Fork this repository. This will create a copy of the project under your account that you can freely modify.

2. Clone the forked repository to your local machine using Git. This will allow you to make changes to the files directly on your computer.

3. Create a new branch:

`git switch -c octet-langfix`

The name can be anything you want.

4. Octet's language files can be located in the *lang* folder, Episode language files are located in *episode* folder. Each folder inside the *episode* folder is named after an Episode's ID. Navigate to this folder in your local repository. the `.properties` file contain the `key=value` strings. That's where you can make your changes.

5. After translating, it's recommended to test your translations in the newest Octet release to everything works correctly.

6. Push your changes to GitHub:

`git add .` - adds changed files to the staging area
`git commit -m "message"` - commits changes. Replace *message* with a short description of your changes.

`git push -u origin octet-langfix` - Pushes your changes. Replace *octet-langfix* with your actual branch name.


7. Submit your pull request

If you go to your forked repository on GitHub, you'll see a Compare & pull request button. Once clicked, you will be able to create a pull request that will be added to this repository after review.
