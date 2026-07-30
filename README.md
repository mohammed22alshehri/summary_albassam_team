# Shift Summary

A lightweight, single-page web app for recording and sharing team shift reports.

## What it does

Shift Summary helps a support and operations team log what happened during a shift and turns it into a ready-to-send message for a WhatsApp group. Instead of writing a report from scratch every time, agents fill in a short form and the app builds the message automatically.

## Features

The app lets agents pick the shift (Morning, Evening, or Night) and adjusts the date automatically for overnight shifts. A team selector lets agents tap to mark who was on shift. Quick counters track calls received, outbound calls, requests raised, complaints, follow-ups, and emails received, each with plus and minus buttons. For every counter above zero, small detail forms appear for reason, ticket number, and company, so the summary includes real context rather than just numbers. All of this is compiled live into a formatted "Shift Summary" message shown in a WhatsApp-style preview bubble, which can then be copied to the clipboard or shared straight to WhatsApp using the Web Share API.

## Tech stack

Plain HTML, CSS, and vanilla JavaScript, with no frameworks or build step required. Deployed with GitHub Pages.

## Usage

Open index.html, or the GitHub Pages link, on a phone or desktop, fill in the shift details, then tap Copy Message or Share to WhatsApp.
