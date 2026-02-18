
---

# Product Requirements Document (PRD): Tiba Tennessee Investor Portal (v2)

## 1. Executive Summary

* **Project Name:** Tiba Tennessee Investor Landing Page.
* **Objective:** To create a high-converting, single-page investor presentation that captures interest from HNWIs and hospitality investors.
* **Target Audience:** Angel investors, Real Estate PE firms, and accredited investors seeking "Quiet Luxury" and "Wellness" assets.
* **Core Value Proposition:** A nature-led, ritual-focused landscape hotel in the Appalachian Highlands, capitalizing on the booming wellness tourism market^^^^^^^^.
  **+2**

---

## 2. Design & Brand Identity (The "Skin")

* **Design Philosophy:** "Informed Modernity" & "Natural Assimilation." **The site must feel like a digital extension of the retreat—calm, spacious, and elemental**^^^^^^^^.
  **+1**
* **Color Palette (Strict "Black & White" + Accent):**
  * **Primary Backgrounds:** *Stone* (`#222323`) for dark sections; **White/Off-White for light sections to maintain high contrast**^^^^.
    **+1**
  * **Text:** *Ivory* (`#F0EEDC`) on dark backgrounds; *Stone* (`<span class="citation-92">#222323</span>`) on light backgrounds^^^^^^^^.
    **+1**
  * **Accent (Sparingly):***River Green* (`<span class="citation-91">#A3996A</span>`)^^. Use *only* for primary CTA buttons or subtle hover states.
* **Typography:**
  * **Headlines:***Baskerville* (Serif) – Elegant, editorial feel^^.
  * **Body Copy:***Montserrat* (Sans Serif) – Clean, readable^^.
* **Imagery Style:** High-contrast renderings, misty landscapes, and detail shots of textures (wood, stone, water)^^.

---

## 3. Site Architecture & Content Map

### A. Navigation Bar (Sticky)

* **Visual:** Transparent background becoming solid *Stone* (`#222323`) on scroll.
* **Logo:** Tiba Logomark (The Stupa/Mountain icon) Left Aligned^^.
* **Links:** Vision, The Asset, Location, Team.
* **CTA Button:** "Request Deck" (Color: *River Green* `#A3996A`, Pill shape).

### B. Hero Section (The Hook)

* **Reference Module:** `section_hero` (Elevate template structure).
* **Background:** Full-screen looping video (drone footage of the Tennessee property/lake) to match the current landing page style.
* **Headline (Baskerville):** "A Retreat Beyond the City’s Reach"^^.
* **Sub-headline (Montserrat):** "Investing in the future of nature-led wellness hospitality in the Appalachian Highlands"^^^^^^^^.
  **+2**
* **Social Proof (New Requirement):** A sleek, horizontal bar or overlay text below the headline reading: "As seen in  **Forbes** ,  **MSN** , and  **AP News** ."
* **Primary CTA:** "Discover the Opportunity" (Anchor scroll).

### C. Investment Highlights (The "Metrics" Bar)

* **Reference Module:** `hero_bottom` (Elevate) - *Positioned immediately below Hero.*
* **Background:** White or  *Stone* .
* **Content:**
  * **Stat 1:** "XX Acres" (Label: Private Wilderness).
  * **Stat 2:** "XX Keys" (Label: Lakeside Suites & Cabins).
  * **Stat 3:** "$XXM" (Label: Projected Asset Value).
  * **Stat 4:** "202X" (Label: Targeted Opening).

### D. The Concept (The "Experience" Section)

* **Reference Module:** `section_experience` (Elevate).
* **Headline:** "Wellness by Design, Stillness by Nature"^^.
* **Copy:** "A destination where silence is the main amenity. We create a playground with intention, discovering equilibrium between venue and nature"^^^^^^^^.
  **+1**
* **Visuals:**
  * *Image 1:* The Infinity Lake Pool render^^.
  * *Image 2:* Detail of "Natural Ingredients" (Stone/Wood textures)^^.

### E. The Asset Showcase (The "Product")

* **Reference Module:** `section_showcase` (Elevate).
* **Layout:** Horizontal scroll or Grid of the specific units.
* **Item 1: "Lakeside Suites"** (Replaced "Cabins")
  * *Description:* Waterfront luxury featuring private decks, jacuzzis, and an elemental build designed to immerse guests in the land^^.
* **Item 2: "The Lobby"** (Replaced "Main Lodge")
  * *Description:* The heart of the retreat featuring fire-cooking kitchens, wine bars, and gathering spaces for connection^^^^^^^^.
    **+1**
* **Item 3: "Nature & Wellness"** (Replaced "Treatment Menu")
  * *Description:* Not just a spa, but a connection to the land. **Features include ice-baths, sound healing, and nature trails that allow the elements to restore you**^^^^^^^^^^^^^^^^^^.
    **+2**

### F. The Opportunity Cards (Why Invest?)

* **Reference Module:** `section_overview` (Elevate).
* **Layout:** 3 Cards with Icons (Black icons on White cards, or White icons on *Stone* cards).
* **Card 1 (Market):** "The Wellness Boom."
  * *Copy:* Capitalizing on the underserved U.S. market for design-led, nature-first hospitality.
* **Card 2 (Location):** "The Appalachian Advantage."
  * *Copy:* Located in Tennessee, offering a secluded retreat accessible from major hubs^^^^.
    **+1**
* **Card 3 (Yield):** "High-Value Asset."
  * *Copy:* A model built for high ADR and diversified revenue streams.

### G. Location Context

* **Reference Module:** *New Section* (Adapt `section_banner` from Elevate).
* **Visual:** Styled Map of Tennessee (Black and White style).
* **Headline:** "Rooted in the Land"^^.
* **Copy:** "Tennessee, USA. A destination to arrive, and feel whole"^^^^^^^^.
  **+1**

### H. The Team (Trust Signals)

* **Reference Module:** Adapt `section_metrics` (Elevate) to be bio cards.
* **Headline:** "Visionaries & Executors."
* **Bio 1:** **William Dair** (Founder/CEO) - *Focus: Vision & Art-driven development.*
* **Bio 2:** **Edo Dozovic** (Partner) - *Focus: Hospitality operations & Guest experience.*
* *(Note: Josh Jennings has been removed as requested).*

### I. Timeline/Roadmap

* **Reference Module:** `section_events` (Elevate).
* **Purpose:** Show investors the project status.
* **Event 1:** "Land Acquisition (Completed)."
* **Event 2:** "Concept & Design (Completed)."
* **Event 3:** "Capital Raise (Current Phase)."
* **Event 4:** "Groundbreaking (QX 202X)."

### J. Footer & Lead Capture

* **Reference Module:** `section_footer` (Elevate).
* **Form:** "Request the Investor Deck."
  * *Fields:* Name, Email, Investor Type (Angel/VC/PE), Phone.
  * *Button Color:**River Green* (`<span class="citation-74">#A3996A</span>`)^^.
* **Social Links:** LinkedIn, Instagram (Tiba Living).
* **Legal:** Disclaimer regarding investment risks.

---

## 4. Content Strategy & Keywords

* **Tone:** Authentic, Ceremonial, Sophisticated^^^^^^^^.
  **+1**
* **Key Phrases to Use:**
  * **"Wellness by design, Stillness by nature"**^^.
  * **"A retreat—beyond the city's reach"**^^.
  * **"Rooted in the land. A return to yourself"**^^.
  * **"To Arrive to a destination"**^^.

---

## 5. Technical Requirements

1. **Platform:** Webflow.
2. **Responsiveness:**
   * **Mobile:** Stacked layout. The "Metrics" bar must turn into a 2x2 grid on mobile.
3. **Loading Speed:** Lazy load all high-res renders. Video in Hero must be optimized/compressed for web to ensure fast load times.
4. **SEO:**
   * *Title Tag:* Tiba Tennessee | Luxury Wellness Resort Investment.
   * *Meta Description:* Invest in Tiba Tennessee—a nature-led, ritual-focused landscape hotel in the Appalachian Highlands.
5. **Analytics:** Google Analytics 4 (GA4) + Meta Pixel.
