---
title: Privacy
layout: default
--- 

# Your Privacy is important to us
Review our privacy practices and security procedures below. Both of our founders are security and privacy paranoid, which allows them to make Sophie as privacy-concious as possible.

## Don't Collect, Don't Tell
This policy is very specific. We collect the bare minimum that is required to function. This, in this case, is your age and username. We don't collect personal information more specific than that, we never know your address, banking information, or real first name. (unless you use your real first name for a username) <br/>
We do not knowingly collect information from children under the age of 13, and if you claim to be under the age of 13 Sophie will ignore your age.

## Aliases
We use Aliases in our API, instead of exposing personal information. Instead of using the real point number, we return a string that has a ranking based on those points, like "None", "Moderate", "Average", or "Severe". We also use aliases in age, such as "Minor" or "Adult" to give third parties that want to protect children the information they need, and nothing more.

## Hashbrowns
We use hashes to hash usernames, so in the event our database is compromised, it'll be more difficult to actually get any useful information out of it. We only have usernames, and those are hashed. Usernames are compared in hashes instead of directly, which keeps you a bit more secure.

## Message Collection
We do have a shiny collection of messages. We delete any messages that are false-positives, and any messages that are not too severe are also removed. We only keep messages we intend to report to law enforcement, or of users we want to keep an eye on. This database is encrypted at-rest and on-run. 

## Consent
Consent is very important, however we are collecting user information without it. If we asked for consent, pedophiles would just decline and go about their sick way. Due to the nature of Sophie's operations, we can cite several laws that do not require us to ask, as we do not collect very specific information nor do we sell it or produce personally identifiable information.

## At-Rest
When our servers are taking a nice little nap, your data is encrypted. This makes a direct attack against our database much more difficult, and will protect your data when we aren't watching. Imagine reading a message written in a foreign language with no translation avaliable, that's what it's like to hackers that try to steal our database at-rest. They'll have to guess millions of times before they'll get access to your information, which can take hundreds of years!

## On-Alert
We use several technologies to protect user data on our server, including geeky authorization protocols for our admins and other annoying tactics to make hackers' lives miserable. We will know if someone tries to break in, and we can stop it before they can even try to access our database. We also encrypt our entire database when it's in use, so a hacker would have to intercept into our RAM in order to read entries, and even that won't expose our entire database!