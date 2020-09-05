**You might have noticed that GPL-3.0 License is not being displayed
on the right just below Readme where it should be displayed. You
might therefore think that this package fails miserably at its very
job because the LICENSE file that it puts into the repository is
what is supposed to cause the notice to appear. The fact that this
does not appear to happen even for the repository of this package
itself is concerning but don't worry; it is actually [Github/licensee](https://github.com/licensee/licensee)
that is triping over the name of this package. Unless your package's
name also begins with license- it in all likelihood won't be affected.
See [licensee/#457](https://github.com/licensee/licensee/issues/457).**

---

[![Build Status](https://travis-ci.com/jcs-elpa/license-templates.svg?branch=master)](https://travis-ci.com/jcs-elpa/license-templates)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# license-templates
> Create LICENSE using GitHub API.

An Emacs package for creating LICENSE file using GitHub API.

* https://developer.github.com/v3/licenses/

## Usage

You can call below command to create a new license file.

```
M-x license-templates-new-file
```

Or you can call below command to insert the license content to current buffer.

```
M-x license-templates-insert
```

## Contribution

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
