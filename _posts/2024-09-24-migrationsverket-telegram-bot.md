---
layout: post
title:  "Migrationsverket booking finder bot"
---

# Migrationsverket sucks

As an immigrant in Sweden, dealing with Migrationsverket (Migration Agency) is always a royal pain. Cases take forever and the bureaucracy is insane. But when you finally navigate through all that, you have to face the final villain, which is booking a day to get your photo and fingerprint taken so they can put that into the little UT-card so you're not deported at first sight.

## Booking codes 

Their booking system is pretty simple (and looks very unsafe if I can say so, but I'm no expert on it). 

When you book an initial time to visit them, it generates a booking code based on your first name without vowels and limited to 4 chars, and 4 seemingly random numbers after. 

For example, in my case it generates the code `HNRQ-xxxx`

If you want to cancel your booking or book another time, you log in into the system with this code and your booking e-mail, so the booking code is essentially your "password" in their booking system.

The code persists if you change your booking though (not sure if it also persists if you cancel and book again, haven't tested it).

## Finding time

As expected, their booking system has a really cool feature, it never tells you when an earlier time is available. Considering that the queue times at Migrationsverket are usually insanely high, the earliest one can book a time to visit them is between 8-12 weeks.

Fuck that.

# Using my diploma for something

When I lost my UT-card last time and got grounded in Sweden, I decided I was pissed off enough to try to automate something that would query their booking systems periodically and let me know if they had an earlier date (I will never submit to include this check in my daily routine).

Great idea: build a Telegram bot to check their system automatically and notify me when an earlier booking appears.

## Telegram bots

How they work

Bot-daddy

# Results

Got an earlier time.

Fun fact, during summer they were open for drop-ins at any time 🙂

_add photo from sign_