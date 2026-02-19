# Developer Certificate of Origin

Version 1.1

```
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

## How to Sign

### Option 1 — Sign off each commit (recommended)

Add the `-s` flag to your commit command:

```bash
git commit -s -m "your commit message"
```

This appends the following line to your commit message:

```
Signed-off-by: Your Name <your-email@example.com>
```

Make sure the name and email match your GitHub account.

### Option 2 — Retroactively sign off commits

If you forgot to sign off on previous commits in your branch:

```bash
git rebase --signoff HEAD~<number-of-commits>
git push --force-with-lease
```

### Option 3 — Sign via PR comment

If the DCO bot flags your pull request, add the following comment on the PR:

```
I have read the DCO document and I hereby sign the DCO.
```

The bot will record your agreement and mark the check as passed.

## Why We Require the DCO

The DCO is a lightweight way for contributors to certify that they wrote
or otherwise have the right to submit the code they are contributing to
the project. It does not require a separate legal agreement — just a
sign-off on each commit.

For more information, see [developercertificate.org](https://developercertificate.org/).
