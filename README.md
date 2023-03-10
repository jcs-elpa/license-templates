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

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![JCS-ELPA](https://raw.githubusercontent.com/jcs-emacs/badges/master/elpa/v/license-templates.svg)](https://jcs-emacs.github.io/jcs-elpa/#/license-templates)
[![MELPA](https://melpa.org/packages/license-templates-badge.svg)](https://melpa.org/#/license-templates)
[![MELPA Stable](https://stable.melpa.org/packages/license-templates-badge.svg)](https://stable.melpa.org/#/license-templates)

# license-templates
> Create LICENSE using GitHub API.

[![CI](https://github.com/jcs-elpa/license-templates/actions/workflows/test.yml/badge.svg)](https://github.com/jcs-elpa/license-templates/actions/workflows/test.yml)

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

## Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Elisp styleguide](https://img.shields.io/badge/elisp-style%20guide-purple)](https://github.com/bbatsov/emacs-lisp-style-guide)
[![Donate on paypal](https://img.shields.io/badge/paypal-donate-1?logo=paypal&color=blue)](https://www.paypal.me/jcs090218)
[![Become a patron](https://img.shields.io/badge/patreon-become%20a%20patron-orange.svg?logo=patreon)](https://www.patreon.com/jcs090218)

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
