# Ticket Responder — CS Training Simulator

A practice tool for hospitality and events support teams.

## What it does

You get 5 random tickets — AV issues, catering problems, 
room complaints — each tagged with a type and urgency. 
First task: drag them into the right priority order. Get 
it wrong (say, ranking "need more name badges" above "VIP 
suite still occupied, speaker arrives in 30 minutes") and 
it won't let you move on until you fix it.

Once the order's right, two options:
- See how Claude would respond, with a tone you pick 
  (empathetic, formal, direct)
- Write your own response and get scored 1-10 with one 
  specific note on what to improve

Works in English, French, or Spanish.

## Tech

Plain HTML/CSS/JS, no build step. Uses the Claude API 
(claude-sonnet-4-5) for translation, responses, and 
feedback. You bring your own API key — it stays in the 
browser, nothing gets stored or sent anywhere else.

## Setup

Open `ticket-responder.html`, paste in an Anthropic API 
key, hit "Generate tickets."

Built for practice, not production — don't drop a real 
production key into this on a shared machine.

## Why I built this

A lot of CS onboarding comes down to shadowing someone for 
a few weeks until prioritization starts to feel automatic. 
This is the version of that you can do on your own time, 
with immediate feedback instead of waiting for a manager 
to review your tickets.****
