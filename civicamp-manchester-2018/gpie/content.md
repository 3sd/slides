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
- parent organisation

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

## Website integration

- Website on WordPress on [www.greenparty.ie](http://www.greenparty.ie)
- CiviCRM on Drupal on [my.greenparty.ie](http://my.greenparty.ie)
- Public pages look exactly the same
- Various integration techniques (CiviCRM pages, webforms, API)

Note: show the Members link in the menu as well as the volunteer form.

Not ideal, but you can't tell. Good in certain situations.
-

## Member dashboard

[Dashboard](https://anon.my.greenparty.ie/dashboard)

- Overview of membership
- Communication preferences
- Powered by GDPR extension
- And a little custom code

-

## Local party access

- Party structure and officers mapped in CiviCRM[*](https://anon.my.greenparty.ie/civicrm/contact/view?reset=1&cid=8426)
- Local officials can:
  - view local membership reports
  - email their members
- Based on ACLs
- and some custom code

-

## Approach

Use out-of-the box CiviCRM/extensions when possible

Develop custom extensions when necessary

A long view with continued investment

Note: explain the + and - of each approach

=

# Next steps

More analysis

More extensions

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
