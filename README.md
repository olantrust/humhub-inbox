# humhub-inbox
Unified Messaging client for Humhub to manage external comms for Email, SMS, Fax, Voice, Post


This module will enable each Space and User profile to have its own inbox to manage external communications.
It will allow admins to add various messaging provider to allow communications in/out.
It will aim to handle Email (IMAP), Voicemail, Missed calls received, Call recordings made, Fax, SMS/MMS, and postal letters

**Restrictions**

It is only a client to fetch from your existing providers.
It will *not* create calls, voicemails, faxes by itself. I can only fetch them from your service provider(s), i.e. your email provider, fax provider, voicemail provider.
Email users will need to get their IMAP login details
Users of Fax, Voicemails, etc... will either need their messages sent and received via email, or require a plugin.


***Donations welcome to support our development https://olan.uk/donate***


**Roadmap**

*2021*

***1.0***

- Enable unified inbox, exclude Spam, Undelivered, Deleted and Archive messages
- Sort messages by Contact / Group, not by subject
- Filter messages by Topic, Archive, Spam, Undelivered, Deleted, Unread
- Enable module for use by Spaces and Profiles
- Single account permissible of each type for each Space / Profile
- Basic send configuration
- Admin settings to connect service provider - per-Space/Profile
