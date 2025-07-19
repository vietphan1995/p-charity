# p-charity

# Introduction

[https://github.com/vietphan1995/p-charity](https://github.com/vietphan1995/p-charity)

p-charity is an application software help you host charity budget, contributors can spend amount to this budget and receivers can get amount this budget. Every transaction from contributor or receiver is encoded like passcodes/passkeys/paircodes/pairkeys as p-code, contribute p-code is created base on contribute amount from contribute side and be saved from budget, receive p-code is created base on receive amount, with contribute p-code saved in budget from receive side.

If receive amount less than contribute amount, next receive p-code is still encoded with this contribute amount until this contribute amount go to zero. If receive amount larger than contribute amount, receive p-code is encoded from multiple contribute p-code until this receive amount go to zero.

If charity hosting has any problem, we can trace and pair p-code from 2 sides contributor and receiver for contribute/receive transparent.

p-charity keeps private contribute and receive profile, budget and transaction amount, contributor also get receive p-code when one receive transaction occur.

p-charity supports enough stages(opening, dividing, closing, opening, dividing, closing, …) of one charity budget/event, automation contribute/receive, verify charity hosting/contributor/receiver, percentage amount, source amount.

### Notes
https://six-zinc-ad4.notion.site/p-charity-1bd5e832d6ee80a28300d660fbf8d2c4