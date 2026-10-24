# Mohamed Tamer

I spent two years in last-mile operations in Egypt — inside a major
e-commerce delivery station, and on the follow-up desk after it:
sorting, splitting a governorate's orders between couriers, chasing
delivery associates through the day, and answering for the success
rate at the end of it. Courier follow-up and scorecards were my
daily bread.

Now I build the tools I used to wish someone would hand me.

Everything below runs. Each project has tests, states its own
limitations in its README instead of hiding them, and carries its own
design identity — no two of them look alike, on purpose. All demo
data is fictional.

## The big two

**[PetBridge](https://github.com/MohameddTamer/petbridge)** — my Arab
Open University graduation project, grown into a real product. A pet
services platform for Egypt with three separate systems: owners
manage pets, health records and bookings; providers run their
business, availability and earnings; an admin approves every provider,
service and product before it goes live. Bookings, a pinned 12%
commission and settlement are the core of the system, not a feature
bolted on. An installable web app, so the same build serves the
browser and both phones.

**[DSP Control Tower](https://github.com/MohameddTamer/dsp-control-tower)** —
the follow-up desk as one screen. Outsourcing offices ranked by their
real delivery rate over any date range you pick, couriers ranked
inside each office, leave and vacation kept out of the percentages,
mid-day alerts when a courier starts falling behind, and an invoice
check that caught 3 phantom days in its own demo data. This is the
desk I worked, turned into software.

## The station, piece by piece

**[Dispatch Ready](https://github.com/MohameddTamer/dispatch-ready)** —
the morning gate. Five checks per courier, and the backend, not the
supervisor's memory, decides who leaves.

**[RTS Returns Manager](https://github.com/MohameddTamer/rts-returns-manager)** —
the end-of-day returns pile with reason codes, contact attempts, and
one rule the backend enforces: nothing is reshipped before a customer
contact is logged.

**[Office Invoice Checker](https://github.com/MohameddTamer/office-invoice-checker)** —
offices bill by courier days; this checks the bill against attendance
minus leave and puts the money difference on the line.

**[Exception Tracker](https://github.com/MohameddTamer/exception-tracker)** —
reads a shipments file and prints only the parcels that need a person
today, each with one action. Stuck parcels do not fix themselves.

**[Delivery Analyzer](https://github.com/MohameddTamer/delivery-analyzer)** —
an orders CSV in; which courier, which area and which failure reason
is costing you money, out.

## For stores and small shops

**[COD Leak Calculator](https://github.com/MohameddTamer/cod-leak-calculator)** —
what failed cash-on-delivery orders actually cost a store per month,
with saved scenarios an owner can compare instead of a number he saw
once and forgot.

**[Address Validator](https://github.com/MohameddTamer/address-validator)** —
catches the failed delivery before it ships: bad phone numbers, a
city in the wrong governorate, an address with no landmark. It also
sorts WhatsApp confirmation replies — Arabic included, because that
is what customers type — into confirmed, postpone, refused, or needs
a human.

**[Daftar](https://github.com/MohameddTamer/daftar-debt-notebook)** —
the corner shop's paper debt notebook, rebuilt so it cannot get wet,
torn or lost. Balances compute themselves, debts past a customer's
limit are stamped, not hidden, and a payment bigger than the balance
is refused.

## How I work

I start from the numbers a business already has, not from a pitch
deck. If the numbers say the problem is small, I say so. Every
project here was critiqued against its own gaps before it was called
finished, and the gaps that remain are written down in the open.
