## Mailing and Marketing with CiviCRM

Michael McAndrew<br>
Third Sector Design

http://slides.3sd.io/civicon-2016/mail

-

## Third Sector Design

Can help with your campaigns and business goals

Create open source software

Focused on CiviCRM

Established 2005

-

## Me

Worked with CiviCRM since 2008

Live in Devon

-

## You

note: Starting out with CiviMail / using it a bit but want to know if they are missing something / using exenstions with CiviMail

-

Questions, feedback and<br />conversation welcome!

## Text 020 3322 3721[*](http://mail46.thirdsectordesign.org/)
*standard network rate*

note: get your questions answered and help me with the SMS demo. talking also allowed.

=

## We'll be talking about...

* Out of the box functionality
* Mosaico
* Tokens and prepopulating forms
* Sending and receving SMS
* 3rd party providers (specifically Sparkpost & Mailchimp, though others exist)

=

# The basics

-

## The problem with email

- it's bad
- really bad!
- composing & sending is difficult

note: Composing (HTML), Sending (Spam)

-

# The options
(for composing email)

-

# WYSIWYG editor
[for example](http://mail46/civicrm/mailing/send?mid=5&continue=true&reset=1)

-

# Headers and footers
1. find a nice template, e.g. [1](https://www.sendwithus.com/resources/templates), [2](http://www.hongkiat.com/blog/open-source-email-templates/)
2. [add it as a header and footer](http://mail46/civicrm/admin/component?reset=1&action=browse)
3. use it in your email

-

# Mosaico

=

Don't forget to text!

# Text 020 3322 3721[*](http://mail46.thirdsectordesign.org/)

=

# Tokens and prepopulating forms

[for example](http://mail46/civicrm/a/#/mailing/14)

-

## Clever smarty stuff

```
{if $first_name}
  Hi {$first_name}!
{else}
  Hi there!
{/if}
```

-

## Clever smarty stuff 2

```
{if $city}
  You live in {$city}.
{else}
  I don't know what city you live in.
{/if}
```

-

## Clever smarty stuff - example

[Full example](http://mail46/civicrm/a/#/mailing/15)

=

# Sending and receiving SMS

- Download a provider extension (twilio)
- Configure your SMS provider (outbound) [*](http://mail46.thirdsectordesign.org/civicrm/admin/sms/provider?reset=1)
- Configure callback for (inbound) [*](https://www.twilio.com/console/phone-numbers/PN6ed1738ed475677d1388301a2200afc5)
- Start sending and receiving SMS

=

# Third Party Providers

- Sparkpost
- CiviSMTP
- Mailchimp
- Mandrill (RIP)
- [Many others](https://civicrm.org/blog/andrewhunt/alternatives-to-mandrill)

note: why use them?

-

## Sparkpost

-

## Mailchimp

=

# Getting help

- [Stack Exchange](http://civicrm.stackexchange.com/)
- [User guide](https://docs.civicrm.org/user/en/stable/)
- [CiviCRM partners](https://civicrm.org/partners-contributors)

=

# Questions

note:
