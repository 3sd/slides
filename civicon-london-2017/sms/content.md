<div class="title">
<h1>SMS with CiviCRM</h1>
<p class="subtitle">Michael McAndrew, Third Sector Design<br/>
<a class="base01" href="http://slides.3sd.io">http://slides.3sd.io</a></p>
</div>

Note: Delete SMS traffic, delete all SMS activities.

=

# Getting started

-

## SMS providers

<p class="fragment">Send and receive SMS on your behalf</p>
<p class="fragment">Talk to CiviCRM</p>
<p class="fragment">Live in 'the cloud'</p>
<p class="fragment">Twilio, Clickatell and Telerivet</p>

-

## Set up

Easy as 1,2,3...

<p class="fragment">1) Sign up with a <a href="http://twilio.com">provider</a><br >(get an API key and a phone number)</p>
<p class="fragment">2) <a href=" http://sms.demo.3sd.io/civicrm/admin/extensions?reset=1">Install</a> and <a href="http://sms.demo.3sd.io/civicrm/admin/sms/provider?reset=1">configure</a> the provider's extension</p>
<p class="fragment">3) Set up <a href="https://www.twilio.com/console/phone-numbers/PN6ed1738ed475677d1388301a2200afc5">inbound SMS</a> processing</p>

Note: Get API key, Sign up for number

-

## Demo time

You can now <a href="http://sms.demo.3sd.io/civicrm/">send and receive SMS</a>

<p class="fragment">**text 020 3322 3721**</p>

Note: Show SMS traffic report / Pick a number at random and send an SMS

-

## Choosing a provider
<p class="fragment">Twilio, Clickatell and Telerivet work with CiviCRM</p>
<p class="fragment">What countries will you use it in?</p>
<p class="fragment">Two way number availability</p>
<p class="fragment">Pricing</p>
<p class="fragment">Or create a new integration</p>

-

## Telerivet
<p class="fragment">Turn any smart phone into an SMS gateway</p>
<p class="fragment">Global availability (including two way numbers)</p>
<p class="fragment">Useful for existing numbers</p>
<p class="fragment">Charges in addition to your mobile network</p>
<p class="fragment">Network and phone may rate limit sending</p>

=

# SMS conversations
<p class="fragment">Automated series of questions and answers</p>
<p class="fragment">Good for surveys and questionnaires</p>
<p class="fragment">and quizes</p>
<p class="fragment">and choose-your-own-ending adventure stories...</p>

-

## A simple example<a href="http://sms.demo.3sd.io/civicrm/sms/conversation/view?id=1"> * </a>

<div class="sms">
  <div class="fragment civi">How was the conference?</div>
  <div class="fragment contact">Great :)</div>
  <div class="fragment civi">Would you go again?</div>
  <div class="fragment contact">Definitely!</div>
  <div class="fragment civi">Any other comments?</div>
  <div class="fragment contact">Food was rubbish</div>
</div>

-

## Features
<p class="fragment">Add replies to contact fields</p>
<p class="fragment">Add contacts to groups</p>
<p class="fragment">Use tokens in texts</p>
<p class="fragment">Branch based on answers</p>

-

## Branching
<!-- -- data-transition="none" -->
<div class="sms">
  <div class="fragment civi">Can you drive a car?</div>
  <div class="fragment contact">Yes</div>
  <div class="fragment civi">Great, do you have any points on your license?</div>
  <div class="fragment contact">No</div>
</div>

-

## Branching
<!-- -- data-transition="none" -->
<div class="sms">
  <div class="civi">Can you drive a car?</div>
  <div class="fragment contact">No</div>
  <div class="fragment civi">Can you fly a plane?</div>
  <div class="fragment contact">Yep!</div>
</div>

-

## Demo time

**text 'Pets' to 020 3322 3721**

-

## How does it work?

<a href="http://sms.demo.3sd.io/civicrm/sms/conversation/view?id=2">Pet survey </a> functionality check list

<div class=fragment><i class="fa- fa-check"></i> update the contact name</div>
<div class="fragment"><i class="fa- fa-check"></i> add people to the dog and cat owner groups</div>
<div class="fragment"><i class="fa- fa-check"></i> populate the dog and cat name fields</div>
<div class="fragment"><i class="fa- fa-check"></i> use {contact.first_name} token</div>
<div class="fragment"><i class="fa- fa-check"></i> branch based on answers</div>
<div class="fragment"><i class="fa- fa-check"></i> review the conversation</div>
<div class="fragment"><i class="fa- fa-check"></i> user initiated conversations</div>

=

# Next steps

<table class="layout">
  <tr>
    <td style="text-align: right;">Clickatell<br />Twilio</td>
    <td>&rarr;</td>
    <td>UI installer</td>
  </tr>
  <tr>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <td style="text-align: right;">SMS conversation<br />Telerivet</td>
    <td>&rarr;</td>
    <td>Download from<br />extensions directory</td>
  </tr>
</table>

=

# Thanks!

<i class="fa fa-globe" aria-hidden="true"></i> <a class='base01'>https://thirdsectordesign.org</a>

<i class="fa fa-twitter" aria-hidden="true"></i> @michaelmcandrew

<i class="fa fa-envelope" aria-hidden="true"></i> michael@3sd.io

<i class="fa fa-television" aria-hidden="true"></i> <a class="base01" href="http://slides.3sd.io/civicon-2017/sms">http://slides.3sd.io/civicon-2017/sms</a></p>
