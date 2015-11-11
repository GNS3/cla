Sign the CLA
=============

This page is the step-by-step guide to signing the GNS3 Contributors License. It's easy and pretty painless!

1. First and foremost, read [the current version of the
   CLA](cla.md).

2. Make an account on [GitHub](https://github.com/) if you don't already
   have one.

3. File a pull request on this repository as [outlined below](#filing-the-pull-request).

4. Wait for a GNS3 team member to merge your pull request. You may start
   opening pull requests for the repository you're contributing to but we will
   only be able to merge your contributions after your signed CLA is merged.

* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *

Filing the Pull Request
-----------------------

If you don't yet know how to file a pull request, read [GitHub's
document about it](https://help.github.com/articles/using-pull-requests).

Make your pull request be the addition of a single file to the
[contributors](contributors) directory of this project. Name the file
with the same name as your GitHub userid, with `.md` appended to the
end. For example, for the user `noplay`, the full path to the file
would be `contributors/noplay.md`.

Put the following in the file:

```
[date]

I hereby agree to the terms of the GNS3 Contributors License, version 2.0, with MD5 checksum
c476e0df05875f9795fd218d770f14eb.

I furthermore declare that I am authorized and able to make this
agreement and sign this declaration.

Signed,

[your name]
https://github.com/[your github userid]
```

Replace the bracketed text as follows:

* `[date]` with today's date, in the unambiguous numeric form `YYYY-MM-DD`.
* `[your name]` with your name.
* `[your github userid]` with your GitHub userid.

You can confirm the MD5 checksum of the CLA by running the md5 program over `cla.md`:

```
md5 cla.md
MD5 (cla.md) = c476e0df05875f9795fd218d770f14eb
```

If the output is different from above, do not sign the CLA and let us know.

That's it!
