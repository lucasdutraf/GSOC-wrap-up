# First Steps for Contributing with Django

## Triage Tickets

Triage tickets are the way that a big open source community use to report bugs and review submitted code, it might be a awesome place to check some issues for a good head start!
**[Triage Tickets](./django-triage-tickets.md)**

## Looking for accepted tickets

It might be good to take a look to some tickets that need documentation or test to be approved by the community, so if you are willing to take some of those as your responsability, you might pay attention to syntax, versions and **if all tests are passing!** A good advice is to try other databases than SQLite (Django's standard). Leave comments and feedback!

## Keep old patches up to date

Pay attention to the time between your patch being submitted and its revision, **the codebase might have changed**!

## Submitting patches

1. Minor changes such as typos must not be tracked by a Trac Ticket, this patch can be directly submitted by a GitHub pull request.
2. **[Claiming tickets](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/submitting-patches/)**
    1. As Django have hundreds of contributors around the world the communication needs to be as effective as possible, so for avoiding duplicates if you have some issue that you have interest working with, assign yourself.
    2. Once you've claimed a ticket, you have the responsibilty to work in it in a reasonable time
    3. If you are having some troubles with your issue, comment it to keep the maintainers updated.
3. **PATCH STYLE**
    1. A good patch should also include a [regression test](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/unit-tests/) to make sure that your bug won't ever happen again
    2. When your work is ready, make sure to open a pull request
    3. Make sure that your patch fulfills [patch review requirements](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/submitting-patches/#patch-review-checklist).