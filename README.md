# Eventum

A PHP social network for proposing, finding and organizing events, with friends, private messages and event group chats.

<img src="images/front/eventum2.png" alt="Eventum logo" width="200">

## What it does
- Sign up, log in and edit your profile and avatar.
- Friends system: search for users, send and accept friend requests, chat privately and exchange images.
- Public or private events proposed by users, with a picture, that anyone can join in one click (private events need an invitation).
- Invite friends to an event.
- A group chat for each event, visible only to its participants, with image sharing.
- A form to create and edit events, and a personal page listing the events you created and the ones you joined.
- Live search for events and users, messaging and theme switching run over AJAX. Light and dark theme.

## Tech stack
PHP 7, MySQL 5.7 (mysqli), vanilla JavaScript (AJAX), HTML and CSS.

## Run it locally
The database schema is not included in the repository, so the site cannot be run as is. It expects a local MySQL database named `eventum_db` (connection settings in `utils/database.php`) and a PHP server such as MAMP or XAMPP.

## Context
Built in April 2023 for the WE4A course (Web technologies and programming) at UTBM. The assignment was a messaging site, which we extended into a social network for events.

Authors: Marius Diguat--Mateus and Eliséo Vardanega.

Credits: thanks to Antoine Litzler for letting us reuse some functions of `database.php` seen in class (modified or not).
