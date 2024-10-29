# Open Source Pledge Accounts

This repository contains the accounts/bookkeeping for the Open Source Pledge.

## Team Members

Team members, along with their hourly rate, are listed in [team.csv](./team.csv).

Only administrators can add team members to this list. If you'd like to claim expenses for your work on the Pledge,
[open an issue][new-issue].

Once added, team members can change their own hourly rate at any time, for example by making a pull request, or
otherwise by opening an issue.

## Accounts (Bookkeeping)

The accounts are kept using [beancount] and stored in [accounts.beancount](./accounts.beancount).

## Submitting Expenses

To submit expenses, [open an issue][new-issue], apply the “expense” label to it, and attach an invoice.

Labour costs should be based on an hourly rate. Hours spent should be tracked using one invoice line item per task. The
tasks do not have to be extremely granular, but it is good to know approximately which costs are associated with which
work.

Invoices can also contain reimbursement requests for reasonable expenses made on behalf of the Pledge (eg printing
stickers).

## Budgets

As our budget is quite minimal, it is currently listed here:

| Item                                          | Budgeted Amount  |
| -------------                                 | ---------------  |
| Physical promotional materials (stickers etc) | 5% of our budget |

[beancount]: https://beancount.github.io/
[new-issue]: https://github.com/opensourcepledge/finances/issues/new
