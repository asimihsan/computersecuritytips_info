---
title: "Two-Factor Authentication (2FA)"
date: 2020-07-22T23:27:15-07:00
draft: true
slug: "two-factor-authentication"
---

### Summary

Two-factor authentication (2FA) is a feature that websites offer that make it harder for hackers to break into
your account. Enable 2FA on critical websites like your email account.

### What is the problem?

Usually, when you log into a website you use your email address or a username and a password. Your password is
a shared secret that only you and the website know. When you use this secret password with a website, it knows
you must be who you say you are, because nobody else knows the password. Sometimes this password doesn't
always stay a secret. If you use an easy-to-guess password, or hackers break into the website and get access
to the passwords, other people can pretend to be you.

Hackers are continuing to get access to private data, including passwords, at an alarming rate. In 2018 an
estimated 4.5 billion records were breached from websites. In 2019 an estimated 2.7 billion identifying
records were posted on the web for sale [^1]. In 2020 due to the global COVID-19 crisis, attackers are
focusing more on health-care data at an even larger scale [^2].

For vital services like online government portals or email accounts, you may need additional security that a
password alone cannot provide.

### What is a solution?

Many websites today give the option to identify you not just using a secret password but also with your
phone. For example, once you log in with your password, the website sends an SMS text message to your phone
number containing a six-digit code that you must then type in. Only someone with your phone can log into the
website. Even if a hacker guesses your password or hacks the website's passwords, it very unlikely they will
also have access to your phone.

A password is **something you know**. A phone is **something you have**. By setting up a website to only
recognize you based on both something you know and something you have, you are using **two-factor
authentication (2FA)**. The first factor is your password, and the second factor is your phone number. Some
websites also refer to 2FA as **two-factor verification**.

### Examples of how to use 2FA

Search online for how to enable 2FA and you will usually find easy to follow instructions. For example:

- for Gmail, search for ["gmail enable two factor
  authentication"](https://duckduckgo.com/?q=gmail+enable+two+factor+authentication&t=hk&ia=web). You'll then
  find a link ["Google 2-Step Verification"](https://www.google.com/landing/2step/) with instructions to
  follow.
- for Facebook, search for ["facebook enable two factor
  authentication"](https://duckduckgo.com/?q=facebook+enable+two+factor+authentication&t=hk). You'll then find
  a page ["What is two-factor authentication and how does it work on
  Facebook?"](https://www.facebook.com/help/148233965247823/) with instructions to follow.

Almost all websites today offer 2FA as a feature. If they don't, this is a good sign that the company isn't
focused on the security of their customer's data, and you should look for other websites to use instead.


### What can go wrong?

TODO

### Footnotes

[^1]: https://en.wikipedia.org/wiki/List_of_data_breaches
[^2]: https://securityboulevard.com/2020/04/a-round-up-of-data-breaches-in-march-2020/

### Notes

Colnago, Jessica, et al. "“It's not actually that horrible” Exploring Adoption of Two-Factor Authentication at a University." Proceedings of the 2018 CHI Conference on Human Factors in Computing Systems. 2018. https://jessica.colnago.org/publications/Colnago2018.pdf

-   In 2018, Google reported than less than 10% of users use 2FA
-   In 2016, Dropbox reported less than 1% of users use 2FA.
-   "those who have never used 2FA are likely to perceive it as more difficult to use than it actually is"
-   Users afraid of losing phone and not being able to log in again
-   If account not perceived as high-security then users don't think it is worth it.
-   Recommendations of researchers
    -   Deploy 2FA incrementally, only start with systems where security benefits outweigh costs
    -   Provide clear instructions on how to use, and simple steps for avoiding lockout and what to do if locked out
    -   Convince users that 2FA is valuable and easy to use.

Reese, Ken et al. “A Usability Study of Five Two-Factor Authentication Methods.” SOUPS @ USENIX Security Symposium (2019). https://www.usenix.org/system/files/soups2019-reese.pdf

-   "However, about one-third of the participants reported an instance of not having their second-factor
    device immediately available when they needed it."
-   Two thirds of participants using TOTP had a problem typing it in before timeout
-   25% of participants felt like backup codes are just another password, did not understand