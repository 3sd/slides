# CiviCRM at the Green Party of Ireland

[Lawrence Hemmings](mailto:lawrence.hemmings@greenparty.ie), [Green Party of Ireland](https://greenparty.ie)

[Michael McAndrew](mailto:michaelmcandrew@thirdsectordesign.org), [Third Sector Design](https://3sd.io)

-

## What we'll cover

The story behind the project

The features we implemented

The lessons we learned

Questions and answers

Note:

Split equally between telling the story of the project and showing what CiviMember and friends can do.

Aim to:

- talk through what we have done
- illustrate what is possible
- inspire and share some lessons learned

=

# The story so far

### https://greenparty.ie

Note:
Eileen was involved early on.

It sucks when you are on an old version

It was fun to do the upgrade.

=

# How it works

-

## Membership types[*](https://anon.my.greenparty.ie/civicrm/admin/member/membershipType?reset=1)

Map your membership structure into CiviCRM<br >
Each type may have different:

- fees
- duration
- auto-renew options
- related members
- parent organisation.

Note: Some basic concepts

-

## Membership status[*](https://anon.my.greenparty.ie/civicrm/admin/member/membershipStatus?reset=1)

Statuses describe the membership life-cycle<br /><br />

##### *pending > new > current > grace > expired*

-

## Online sign up and renewal

[Join form](https://my.greenparty.ie/join)

- Recurring payments by default
- Completely automated, including:
  - user account creation
  - welcome emails

Note:

Intervention only required for exceptional cases. No work required for optimal route.

Dwell on user account creation if there is time

-

## Recurring payments

[Donate form](https://my.greenparty.ie/donate-one-off)

- Uses the Stripe extension (mantained by MJW)
- Membership payments are recurring by default
- Donations are one off or recurring
- We're improving the cancellation workflow

-

## Website Integration

- Website is WordPress but CiviCRM is on Drupal
- Public facing Civi pages (e.g. [the volunteer form](http://my.greenparty.ie/volunteer)) inherit the WordPress theme

Note: show the Members link in the menu as well as the volunteer form.

-

## Member dashboard

[Dashboard](https://anon.my.greenparty.ie/dashboard)

- Overview of membership
- Communication preferences via GDPR extension

-

## Local party access

- Party organisations and officers mapped in CiviCRM
- Local officials have restricted access
  - [View membership reports](***)
  - [Email local members](***)
- Based on ACLs
- and a little custom code

-

## Approach

Use out-of-the box CiviCRM and popular extensions when possible

Develop custom extensions when necessary

A long view with continued investment

Note: explain the + and - of each approach

=

# Next steps

- Evidence based decision making
- Take advantage of more extensions

=

# Lessons learned

Note:

* Contribution pages are hard to theme
* Join up your website and CRM projects
* GDPR

=

# Q & A

=

# Thank you!
