# Soulful Steps Entertainment — Website Build Spec

Source: "SoulfulSteps Site Redesign" Google Doc, condensed and structured for handoff to Claude Code.

---

## 1\. Brand Basics

- **Business name:** Soulful Steps Entertainment   
- **Sub-head:** Bollywood Fusion Latin Performances  
- **Tagline:** "Our performances are stories danced in front of your eyes"  
- **Header nav:** Logo (left) · Instagram \+ TikTok links · Menu → Products, Artists, Our Story, Podcasts

---

## 2\. Sitemap

1. Home  
2. Product Page & Packages  
3. About page \- Our Story  
4. Artist Page (roster) → individual Artist Profile pages  
5. Dancer of the Month  
6. Podcasts / Short Stories / Media Coverage  
7. Contact / Intake Form (new — needed for booking flow, see §7)

---

## 3\. Page-by-Page Content

### 3.1 Home Page

**Sections, in order:**

1. Header (nav as above)  
2. Hero: On the right: image: Hero img , On the left: business name, sub-head, tagline  
3. Primary CTA (Let’s celebrate your day): Secondary CTA ( Learn more)  
4. 3 Testimonial cards. Contains (image, Venue: NAME, customer quote)  
     
   > **Card 1:** image: Die With a Smile Testimonial photo, Venue: Pan American Food & Music Festival. Customer testimonial: "There's something really unique about Soulful Steps. They don't just do moves, you can really feel their emotions." — DJ Alejo.  
   >   
   > **Card 2**: image: Señorita Sassy image, Venue: Sangeet. (a joyful pre-wedding celebration) Customer testimonial: “Your performance was Mindblowing, we love the Senēorita song for ever.”  – Priya a guest at the Sangeet.  
   >   
>    **Card 3:** image:  O Saki Saki open arms  image, Venue: Jubilee (25th Wedding anniversary) Customer testimonial: “You guys exceeded our expectations, the energy and elegance you brought was absolutely incredible. You’d Bollywood sit was on point”.   
   >   
5. Featured Products (pulls from Product Page — see §3.2)  
6. Primary CTA buttons in hero **and** repeated throughout the page (see §6 CRO notes)

---

### 3.2 Product Page & Packages

Each "product" is a performance piece with a consistent content model. Use this as the data schema:

{

  name, message, story, vibe, occasions, genre, song, artists, audioClip, image carousel

}

**Product 1 — "A Love Story"**

- Message: Love that refuses to be taken for granted. A reminder to hold each other close and live every day and night with hearts full.  
- Story: She wakes from a bad dream realizing she's taken the relationship for granted; as she tries to express her love, he doesn't yet know she's dropped her guard, ready to let go of insignificant problems and cherish every night.  
- Vibe: Emotional, romantic showcase; tension-filled opening resolving into a sweeping, joyful close  
- Occasions: Anniversary, Weddings, Proposals, Jubilee, Golden Jubilee  
- Genre: Latin / Salsa  
- Song: "Die With a Smile" — Lady Gaga & Bruno Mars  
- Artists: Salimeh, Alberto  
- image carousel: A Love Story folder  
- Has audio clip placeholder

**Product 2 — "Señorita — A Playful piece"**

- Message: Life is meant to be lived fully, fearlessly, and together — the joy of stepping outside the ordinary and saying yes to the moment.  
- Story: Two dancers meet across the floor — Bollywood grace meeting Latin fire. Flirtatious, magnetic chemistry builds through the piece into an undeniable connection by the final note.  
- Vibe: Fiery, free-spirited, communal — flamenco passion fused with Latin rhythm; playful, magnetic, sultry; romantic energy building into celebratory release  
- Occasions: Weddings (esp. multicultural/fusion), engagement parties, sangeet/mehndi nights, anniversaries, milestone birthdays, graduations, bachelor/bachelorette parties, friend reunions, retirement parties, and cross-cultural celebrations  
- Genre: Bollywood-Latin mashup (Flamenco, Bollywood, Merengue)  
- Song: "Señorita" — Farhan Akhtar, Hrithik Roshan, Abhay Deol, María del Mar Fernández  
- Artists: *(not listed — confirm)*  
- image carousel: Señorita — A Playful piece folder


**Product 3 — "Fiery Party celebration \- Bollywood Fusion"**

- Message: A playful celebration of cultures and dances. Where intricate Bollywood meets Smooth Latin dance couple dance connection   
- Story: She is sassy and got it all, he must impress her with his Bollywood Solo. Will he deliver?  
- Vibe: Upbeat, sharp choreography, masterful stage presence and playful connections  
- Occasions: Diwali, Holi, Sangeet Night, Mehndi Night, Birthdays, Weddings  
- Genre: Bollywood, Cha-cha & Merengue  
- Song: "O Saki Saki" — Vishal Shekhar, Neha Kakkar, B Parrak  
- Artists: Salimeh, Alberto  
- image carousel:  Bollywood Fusion  
- Has audio clip placeholder

**Product 4 — "Colours"**

- Message: Bringing cultures and people together  
- Story: *(in development)*  
- Vibe: Mysterious, vibrant, badass, fiery  
- Occasions: Quinceañera, Bat Mitzvah, Birthdays, Weddings, Anniversary  
- Genre: Bollywood fusion, Salsa, Bachata  
- Songs: "Sa Ni Nana," "Boranda," "Sus Huellas" *(spellings to confirm)*  
- Artists: Deivy, Nick, Victoria, Salimeh  
- image carousel: : an emotional moment  
- Has audio clip placeholder

**Package 1**

- Includes: "Die With a Smile — A Love Story" \+ "Señorita — Live Boldly, Live Now"  
- Price: $400

---

### 3.3 Artist Page (Roster \+ Profiles)

**Roster page:** Two lead "founder" buttons/tags shown prominently:

- **Salimeh** — colorful purple button, white text  
- **Alberto** — red/orange button, white text (nicknamed "The Bollywood Latin Prince")

Clicking either leads to that person's individual artist profile.

**Profile page layout (per artist):**

- Left: profile image, well-lit, warm smile, in color (not black & white — color reads as more open/inviting)  
- Right: a short *personality-driven* story (not a resume) \+ style tags

**Style tags (not prose bios) — build as tag/pill components:** | Artist | Styles | |---|---| | Alberto | Salsa, Cha-cha, Bachata, Bollywood Fusion | | Salimeh | Salsa, Cha-cha, Bachata, Kizomba, Argentine Tango, Bollywood Fusion | | Deivy | Salsa, Bachata, Flamenco, Reggaeton, Argentine Tango, Hip Hop, Kizomba | | Victoria | Ballroom, Ballet, Contemporary, Bachata, Zouk | | Nick | Bachata, Hip Hop |

**Personality story copy (drafted from source, needs light editing pass):**

- **Deivy:** A Colombian champion — humble, yet a fiery showman. Known for saying he's "just a really passionate person who likes to dance," despite an enormous competitive resume (Cuban Salsa, Salsa, LA Salsa, Mambo, Popping & Locking, Kizomba, Argentine Tango). On the floor, an insanely skilled showman with a beautiful soul.  
- **Victoria:** Sassy and graceful. A medical tech professional and versatile artist who started in competitive ballroom dancing in Romania, then explored contemporary ballet, sensual bachata, and zouk.  
- **Alberto ("The Charming"):** Earned his nickname in the dance community — genuinely charming and skilled. His uplifting energy and bright smile bring people joy at every party; one of the most charming and elegant Nicaraguans you'll meet in Toronto. *(Needs a second story/anecdote — flagged as "will add.")*  
- **Salimeh (founder/co-founder story, closing note for her page):** An unconventional Persian-Canadian artist and designer with a lifelong vision of bringing together different art forms, styles, backgrounds, and people. Building Soulful Steps is that dream in motion — stories danced in front of you, unforgettable performances that touch hearts and bring joy through full entertainment.  
- **Nick:** *(no story yet — flagged)*

**"How Salimeh & Alberto met" story (can live on Alberto's page or Our Story):** Salimeh had seen Alberto three times before approaching him at a salsa social where a competition was being announced. She asked if he'd heard about it; he said yes; she said "good, because you and I are competing" — and that's how they became dance partners, going on to compete in Toronto, Montreal, and San Francisco.

---

### 3.4 About \- Our Story

- Alberto and Salimeh became partners on the night of a Salsa competition in Toronto, after Salimeh (having seen him only 3 times before) walked up and said:  
  - Salimeh: "Have you heard there's a competition?"  
  - Alberto: "Yes, I have."  
  - Salimeh: "Good, because we are gonna be competing there together."  
  - Alberto: "Challenge accepted."  
- Embed: video of their first competition — [https://www.youtube.com/watch?v=LTTTQu4OC\_o](https://www.youtube.com/watch?v=LTTTQu4OC_o)  
- Since then: they've traveled to train, compete, and perform at many events.

---

### 3.5 Dancer of the Month

**Concept:** A recurring feature page honoring a social dancer from the community.

- Content per feature: photo, short dance clip, and 5 specific things the community acknowledges them for (example given: mannerism, respectfulness/politeness, creativity, generosity — giving their partner room to express themselves rather than only leading).  
- The featured dancer is notified (e.g. by email) that they've been mentioned on the site.  
- Intent: builds community engagement and gives dancers a reason to keep coming back to the site.  
- Future extension: short recorded interviews/podcast clips with featured dancers, posted on this page.

---

### 3.6 Podcasts / Short Stories / Media Coverage

Three related but distinct content types to design for:

1. **Podcast episodes:** Conversational short episodes (not solo monologue) about reading a partner's energy/vibe and elevating the social dancing experience. Format idea: share a "challenge" the team is testing, discuss observations, invite the team's take — recorded after rehearsals or performances.  
2. **Short Stories:** Personal essays from Salimeh's (and eventually other dancers'/founders') dance life — how dance has shaped relationships and life events. Open to contributions from other team members, with a consistent format per entry.  
3. **Media Coverage:** placeholder section for press/media mentions (named in doc metadata, no content drafted yet).

---

## 4\. Booking / Purchase Flow (Contact Page — net new)

The only path to purchase is contacting the company directly — needs an **intake form**, not e-commerce checkout. Form fields:

- Email address  
- Phone number  
- Event details  
- Open text: "What story would you want to tell at your event?" (prompt: look at the Products page and describe in their own words what would best suit the event)  
- Preferred contact time — offer a few time-slot options rather than "call anytime" (framed as more respectful of the client's time)

After submission: internal team follows up by phone to discuss customization.

---

## 5\. Component Inventory (for Claude Code)

- Header w/ logo, social links, nav menu  
- Hero section w/ Primary CTA button/ Secondary CTA button  
- Testimonial carousel/grid (3 items)  
- Product/performance card (schema in §3.2) — used on Home (featured) and full Product page  
- Package card (bundled products \+ price)  
- Artist tag/pill button (custom color per artist: Salimeh \= purple/white text, Alberto \= red-orange/white text)  
- Artist profile layout (image left, story \+ tags right)  
- Style tag pill component (reusable, per §3.3 table)  
- Video embed block (YouTube)  
- Dancer-of-the-Month feature block (photo \+ clip \+ 5 acknowledgments)  
- Podcast episode list/player block  
- Short story post block  
- Intake/contact form  
- Repeated CTA button (used in hero \+ throughout page per CRO notes)

---

## 6\. CRO Notes (from source doc)

- Include CTA buttons in the Hero section — not just the header.  
- Repeat CTA buttons throughout the page, not just once.  
- Persistent nav menu linking to all main pages.

---

## 7\. Open Questions / Gaps to Resolve Before Build

- **Company name:** doc uses "Soulful Steps Entertainment" in some places and "Soulful Steps Dance Entertainment Company" elsewhere — pick one canonical name for the whole site.  
- 2 of 3 home page testimonials are still needed.  
- Product 3 ("Señorita") has no listed artists — confirm who performs it.  
- "Colours" story is marked "developing" — needs final copy before launch, and song titles need spelling confirmed.  
- Alberto's bio needs a second personal story/anecdote (noted as "will add" in source).  
- Nick's and Victoria's personality stories are missing (Victoria has a story now; Nick has none).  
- Package pricing: only Package 1 ($400) is defined — confirm if more packages/pricing tiers exist.  
- Confirm whether "Colours" and other multi-artist pieces need a distinct product card layout (4 artists vs. the standard 2).  
- Media Coverage section has no content yet — placeholder or cut for v1?

---

*Prepared for handoff to Claude Code. Recommend resolving the Open Questions above (or at minimum flagging them as TODOs) before generating page templates, so copy and data schemas don't need to be reworked mid-build.*  
