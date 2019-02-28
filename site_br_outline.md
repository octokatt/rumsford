# Rumsford Chronicles website
Project outline, first pass
=================

Features:
------
* Blog capability
    - Multiple author capacity
    - API controlled, ideally with Discord pass through
    - Username and password controlled
* Character database
    - User control for updating
    - Attaches to picture for each character
* Google maps integration for plots
* Character sheet page
    - Ability to create character sheets
    - Ability to update character sheets, user controls
* Experience point tracker
    - Spend tracker
    - Beats tracking
    - Aspirations tracking
* Wiki for campaign history
    - Interlink to character sheets, aspirations, blogs

Frameworks:
-------
* Django for CRUD, user bits
* API calls with Requests in Python for Discord pass through
* MySQL for character database, etc.
* PDF generator for character sheets (stretch)s


# Discord Bot
Project outline, first pass
========
* API calls into Django-run database
* Dice roller
* Aspirations updater
* Stats updater
* Wiki updater (simple CAT adds)
* 