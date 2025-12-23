What Happens Under the Hood When You Fork or Clone?

Fork:

GitHub creates a new repository under your account

The full commit history is copied

A relationship with the original repository is maintained (upstream)

Clone:

Git downloads all Git objects (commits, trees, blobs)

A local .git directory is created

A remote called origin is automatically configured

Source:
https://git-scm.com/book/en/v2/Git-Internals-Plumbing-and-Porcelain
