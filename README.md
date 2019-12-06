![]('./images/lotus-napkin.jpg')

# **Request** 
# Etiquette

---
# What I **mean**

- Good commit messages
- Group similar work
- Small File count


![right](http://deckset-assets.s3-website-us-east-1.amazonaws.com/colnago1.jpg)

---

> The **longer** the PR the more **tiring** it is for the **reviewer**

-- Everyone **Ever**

---

# [fit] **Commit** messages

### Short **&&** sweet
### Imperative
### Current Tense 

![left](http://deckset-assets.s3-website-us-east-1.amazonaws.com/colnago1.jpg)

---

![right](http://deckset-assets.s3-website-us-east-1.amazonaws.com/colnago1.jpg)

### [fit] What is
# Imperative **state**

---

## Say how it **changes** the code when **merged**

---

## [fit] Use the **present** tense for messages

### [fit] **Use your** editor **for commit messages**

---
# **Examples**
### [fit] Some Good **&&** Some Bad

---
# **From** Me
```bash
8509f7814 define average equity value correctly
6ee8ce562 add test for weighting factors
ea36b65d3 remove deprecation warning.
b9765fd7f add in missing methods that i'll need soonish
237c6d196 use balance sheet because that's smarter
503837e6e get debt test passing
ebd919ca3 remove more things from that we don't use
5f43a9c1b notice that we don't need to serialize common equity values
553b51198 Merge remote-tracking branch 'origin/develop' into rb/summary_data
42aafbeef rename argument and get cash test passing
00c08444c get the average equity values test passing
6241b5408 working toward something usable
6cc336a8b expect 1+ average equity values
```
---
# From **others**

```bash
c719aaa737 add otp secret ot .env.test file add user for otp testing Add tests for otp login attempts minor formatting fixes
377af7ce45 safe navigation for otp validation
68ae304520 remove before action as we are using create now add tests
5b34594731 remove test that doesn`t apply anymore
237987f040 use OTP_SECRET_KEY instead of SECRET_TOKEN
723ca174dc Add test for otp provisioning controller
322a4ff216 formatting
55e5347c6c alphabetize hash add double quotes
d37a1282d4 remove extra line
bb375c436e Add view for entering mfa code Only show two factor if user is an admin Rename qrcode partial to otp_form
75aa00705c rename everything to otp_provisioning from otp_provisioner Use secret token to encrypt otp keys ...
74b4f87cc0 rubocop
fde8869540 Add qrcode view back rename otp provisioner to provisionings lock
d7a71be4d9 allow qr code to be generated for users current otp secret redirect to login page, not just back
12f5d56a6c rubocop fixes
360d0d7b8d formatting
e26c88eed3 fix tests
```
---
### Adding **more** details
#### **12f5d56a6c** rubocop fixes
---
### **12f5d56a6c** ~~rubocop fixes~~
#### **12f5d56a6c** resolve style violations in __FILE__
---
## **Improving** on something too **detailed**
---
# **This**

```bash
c719aaa737 add otp secret ot .env.test file add user for otp testing 
               Add tests for otp login attempts minor formatting fixes
```
---
# **Becomes**

```bash
c719aaa737 resolve otp test configuration login setup

  * add otp secret ot .env.test file
  * add user for otp testing
  * Add tests for otp login attempts minor formatting fixes
```
---
# The **Template**

```bash
[VERB] for [FEATURE/BUG]

Details in paragraph form or in
* bullet
* points
```
---
![](http://deckset-assets.s3-website-us-east-1.amazonaws.com/colnago1.jpg)

# Group **Similar** Work

---

# Our **Work**

* Feature
* Bugs
* Styles
* Feedback
* More **feedback** if I'm a **Reviewer**

---
![left](http://deckset-assets.s3-website-us-east-1.amazonaws.com/colnago1.jpg)
# Story Time
### Vertical **user** slices formally known as **top down development**

* Start with what the user sees
* Lower down the stack
* End with full feature

---
## The **Feature**
### Allow **valuation** users to view and add **Onboarding** Discounts

---
## **The** Steps
![right](http://deckset-assets.s3-website-us-east-1.amazonaws.com/colnago1.jpg)

* List of discounts
* New discount form
* Connect DB
* Permissions

---
# How many **Pull** Requests?

![inline](http://deckset-assets.s3-website-us-east-1.amazonaws.com/colnago1.jpg)

---
## Let's get **lower**

* Controller
* Model
* Validations
* Relations
* Routes
* Migrations
* Tests

---
## Tips **&&** Tricks
### git commit **--patch**

---
![](http://deckset-assets.s3-website-us-east-1.amazonaws.com/colnago1.jpg)

---
![](http://deckset-assets.s3-website-us-east-1.amazonaws.com/colnago1.jpg)

# **End**

---
# Sources

[The Art of Pull Requests](https://hackernoon.com/the-art-of-pull-requests-6f0f099850f9)
[Practical Guide To Small & Easy PR Requests](https://sourcediving.com/a-practical-guide-to-small-and-easy-to-review-pull-requests-a7f04a01d5d5)
[Git Commit Best Practices](https://github.com/trein/dev-best-practices/wiki/Git-Commit-Best-Practices)
