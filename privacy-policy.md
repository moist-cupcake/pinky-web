---
layout: default
title: Pinky Privacy Policy
permalink: /privacy-policy/
---

# Pinky — Privacy Policy

_Last updated: 2026-06-25_

Pinky is a Discord bot that shows activity statistics for the servers
it's installed in. It is built to collect as little as possible.

## What Pinky stores

- **Message counts per channel.** Pinky counts how many messages are
  posted in each channel, in aggregate. It does **not** store who sent
  a message, and it **never** stores message text.
- **Role pings.** When a message pings a role, Pinky records *which*
  role was pinged and when — but only for roles with **at least 5
  members**, and never *who* sent the ping or who belongs to the role.
- **Server activity.** Pinky keeps hourly counts of members joining and
  leaving. It does **not** store who joined or left.

That's all that's retained for statistics. Pinky also keeps a small
amount of its own operational state (channel and message IDs for its
scheduled messages, plus timestamps) — this contains no information
about your members.

## What Pinky does *not* store

Pinky stores no usernames, user IDs, member lists, or message content,
so the statistics it keeps hold nothing that identifies you. Uploaded
files and attachments are never saved.

## Reading your messages

To run commands, respond to image keywords, and apply each server's
moderation rules, Pinky reads message content **in the moment** and
then discards it — message text is never stored. Our legal basis for
this is **legitimate interests** (GDPR Art. 6(1)(f)): operating the bot
and enforcing each server's rules, balanced against the fact that
nothing is stored.

## How the data is used

Statistics are used only to produce activity graphs and stats **inside
the server where they were collected**. They are never sold and never
shared outside the server they came from.

Pinky runs as a Discord bot, so the platform itself — and your account
on it — is governed by Discord's own privacy policy.

## Where your data is processed

Most of Pinky's processing happens on servers in the European Union
(the Netherlands). One feature — responding to image keywords — runs on
a hosting provider in the United States, which briefly reads message
content to detect the keyword and stores nothing. For members in the
EEA or UK, this means message content is processed in the US; we rely on
the EU **Standard Contractual Clauses** in our hosting provider's
data-processing agreement as the safeguard for that transfer.

## Retention

Aggregated statistics are kept no longer than 30 days, then
automatically deleted. (In normal operation they are kept for around
two weeks.) Raw per-message records are condensed within about 10
minutes and then deleted.

## Your rights

Pinky stores no information that identifies you, so for the activity
statistics there is nothing per-user to access, correct, export, or
delete — there is simply no record tied to you (GDPR Art. 11).

Two rights still apply to the message-reading described above:

- **You can object** to Pinky processing your messages. In practice
  Pinky can't be switched off for one member, so this means asking the
  server's admin to remove the bot, or leaving the server.
- **You can complain** to your local data protection authority if you
  believe your data has been mishandled.

## Contact

For questions about this policy, email **pinky_privacy@fastmail.com**,
or contact your server's bot administrator.

## This Page

The canonical URL for page this page is
https://moist-cupcake.github.io/pinky-web/privacy-policy/
