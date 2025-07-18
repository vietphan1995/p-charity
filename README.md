# p-charity

# Introduction

[https://github.com/vietphan1995/p-charity](https://github.com/vietphan1995/p-charity)

p-charity is an application software help you host charity budget, contributors can spend amount to this budget and receivers can get amount this budget. Every transaction from contributor or receiver is encoded as passcodes/passkeys, contribute passcodes is created base on contribute amount from contribute side and be saved from budget, receive passcodes is created base on receive amount, with contribute passcodes from receive side.

If receive amount less than contribute amount, next receive passcodes is still encoded with this contribute amount until this contribute amount go to zero. If receive amount larger than contribute amount, receive passcodes is encoded from multiple contribute passcodes until this receive amount go to zero.

If charity hosting has any problem, we can trace passcodes from 2 sides contributor and receiver for contribute/receive transparent.

p-charity keeps private contribute and receive profile, budget and transaction amount, contributor also get receive passcodes when one receive transaction occur.

p-charity supports enough stages(opening, dividing, closing, opening, dividing, closing, …) of one charity budget/event, automation contribute/receive, verify contributor/receiver, percentage amount, source amount.

### Notes
https://six-zinc-ad4.notion.site/p-charity-1bd5e832d6ee80a28300d660fbf8d2c4