# contactparliament
a server that makes it easy for citizens to contact their parliamentarians using VOIP, email and twitter. [This is based on EFF's call congress tool](https://github.com/EFForg/call-congress).

The server will handle several use cases:
```
    We can have the user punch in their post code
    We provide them details of their Member of Parliament and their contact details
    A web-initiated call to connect a user's phone number to their MPs office

    We have the user punch in their post code
    We provide them details of their Member of Parliamnent and their contact details
    A web initated email to send from our server to their MP using their contact details

    We have the user punch in their post code
    We provide them with details of their MP and their contact details
    A tweet to their MP using their contact details

    A web initiated call to connect a user's phone number to a randomly chosen office of a Lord.

    A web initiated email to a randomly chosen office of a Lord.

    A tweet to a randomly chosen Lord.
```
## Progress so far

Pulled List of MPs and Lords (to date as of the most recent general election) in JSON from the theyworkforyou API.


JSON structure
```
{
  "member_id" : "40710",
  "person_id" : "11771",
  "name" : "Justine Greening",
  "party" : "Conservative",
  "constituency" : "Putney",
  "telephone" : "",
  "email" : "",
  "twitter" : ""
},
```

Currently crowdsourcing the contact details for all MPs and Lords.

## Guidance for Crowdsourcing Contacts
* Use [Parliamentary Sources](http://www.parliament.uk/mps-lords-and-offices/) to collate data.
* Primarily use parliamentary contacts over constituency contacts. If possible, secondary constituency contacts will follow.
* Only use publicly available information.
* If MPs do not have a Twitter account, add their party account, for example @UKLabour for the Labour Party


When complete, intergration with existing codebase will follow.
