# Christopher Chan-Nui's resume

This is my resume to be rendered by the [rendercv package](https://pypi.org/project/rendercv/).

## Build

    poetry shell
    poe build

Output will appear in rendercv_output directory

## Release

    scripts/tag <- tag release
    scripts/release <- release to github

Pass a 'poetry version' version part to bump if you wish to increment the version number

