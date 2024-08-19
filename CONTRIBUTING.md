# Welcome to the dpmintern documentation contributing guidelines
Here we outline how to best contribute to our documentation effort.

*A word of warning*: This contribution guide only applies to the documentation, and not to any other dpmintern projects, for a guide to contribution on those projects, consult each and every project's contribution guidelines. DO NOT REFER TO THIS.

## Including third party documentation (Pull requests *and* commits)
When including someone else's documentation, either because they're not involved in the community anynore or for, realistically, any other reason, keep in mind these things:

- The commit adding such documentation *must* be made under the original author's name, this can be done through the following command.
```bash
git commit --author "ThisOtherGuy <email.if.known@whatever.com>"
```

- If the documentation was written by multiple people, [specify that in the commit message](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-with-multiple-authors#creating-co-authored-commits-on-the-command-line).

- All must follow the [guidelines for writing](#general-guidelines-for-writing), below.


## Asking for documentation inclusion or edit (Issues)

- Always specify whether the documentation has been written/co-authored by a third party

- Write a short argument for why you believe the inclusion of your documentation to our effort would be a net positive

- Follow the [guidelines for writing](#general-guidelines-for-writing) below.

## General guidelines for writing

- It needs to look decent in markdown. Read through the file and adapt it into [GitHub Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)

- never upload logos or any other copyright material without necessary copyright disclaimers. (We suggest adding a <filename>-disclaimer.txt for every copyright file.) Overall, try not to upload copyright files.

- Write everything in [UTF-8](https://en.wikipedia.org/wiki/UTF-8)

- Per the above, when specifying hex values, please report the hexadecimal representation and not the matching [ASCII](https://en.wikipedia.org/wiki/ASCII) character.

- When mentioning or referring to information already available on [our cognate community wiki](https://thedenpamen.wiki.gg/wiki/The_Denpa_Men_Wiki), it is preferrable to include links to that, rather than duplicating information here.

