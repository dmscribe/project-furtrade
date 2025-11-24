# beadwork.ca – Project Fur Trade
"Under the Scrutiny of Land Owners" 

[Python] [Django] 

Software License
This software is released under the terms of the MIT license.  See COPYING for more information or see https://opensource.org/license/MIT.

What is Project Fur Trade? 

beadwork.ca is a full-stack Django platform (in active development) celebrating Indigenous beadwork, art, storytelling, and community — built as Project Fur Trade in deliberate homage to the historic trade routes that carried beads, stories, and relationships across Turtle Island.

This repository is the complete, production-ready foundation that will power the live site at https://beadwork.ca.

## Created by
Daniel Scribe
Pimacikamak Cree Nation / Norway House Cree Nation  
(also known as Dan Ryder)

In loving memory and honour of my grandfather  
WWII Veteran & Cree Educator Murdock Scribe
Norway House Cree Nation  
— a man who taught generations that stories, language, sacred knowledge, and craftsmanship are the real wealth we trade.

## Current Features
- Secure user authentication  
- Message/posting system (foundation for artist stories & marketplace)  
- Clean, minimal design (ready for full Indigenous-led visual identity)  
- Fully version-controlled from day one  
- One-click deploy to Render / Railway

## Live Development Version
https://project-fur-trade-2025.onrender.com  
(placeholder until beadwork.ca DNS points here)

## Future Vision for beadwork.ca

beadwork.ca will become a location-aware, Indigenous-led global platform that blends marketplace, social feed, and cultural preservation — all built on the historic metaphor of the fur trade routes that once carried beads and quills across Turtle Island.

### Core Features (in active roadmap)

- Artist Profiles
  Full profiles showing post history, reputation score, and community trust indicators.

- Bazaar Feed – The Heart of the Platform  
  A smart, geo-aware global feed that automatically adapts to the user’s real-time device location.  
  Four post categories with intentional ranking:  
  1. Selling – highest visibility (prioritizes commerce)  
  2. Trading – strong secondary placement  
  3. Showcasing – beautiful work that keeps users scrolling  
  4. Information / Storytelling – events, teachings, cultural posts (lower but still visible)

- Mandatory Post Requirements  
  Every post must include:  
  - At least one image  
  - Text description  
  - Verified geographic location (no post without location authentication)

- Location-Based Interaction Rules  
  - Unregistered visitors: can browse and search everything  
  - Registered users: can comment  
  - Posting, bookmarking (“marking”), or trading: requires device location verification

- The Marking System – Transparent Engagement  
  - Users can publicly “mark” (bookmark/save) posts  
  - Merchants instantly see who marked and who viewed their post (registered users only)  
  - Creates real social proof and helps merchants gauge interest without messaging

- Reputation & Storytelling Layer  
  Long-form “Information” posts become part of a user’s reputation.  Elders, knowledge keepers, and educators can share teachings, event announcements, or oral-history-style stories that live permanently and boost trust scores.

- Event & Calendar Integration  
  Information posts double as community event notices — no separate calendar needed at launch.  The feed itself becomes the living calendar.

It’s a digital trade route where beads, stories, and relationships move again — but this time, Indigenous people own the route.

## Local Development

git clone https://github.com/dmscribe/project-furtrade.git
cd beadwork.ca
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
