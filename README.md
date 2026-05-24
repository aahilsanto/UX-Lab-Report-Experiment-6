# UX Lab Report — Experiment 6
## Solution Ideation, User Stories, Scenarios, Flow Diagrams, and Information Architecture

**Name:** Ahil Santo A

**Reg no:** 212224040018



## Aim

To apply core UX design techniques — solution ideation, user story writing, scenario building, flow diagramming, and information architecture — on a real-world e-commerce platform (Amazon.in) in order to generate structured design thinking outputs that address identified user needs.



## Algorithm

1. Identify a known UX problem from the platform and generate multiple solution ideas using the Crazy 8s ideation technique.
2. Use previously created personas to write at least five user stories in the standard format — *"As a [user], I want to [goal], so that [benefit]."*
3. Select one user story and expand it into a detailed narrative scenario describing the user's context, emotional state, and environment.
4. Choose a key user task and represent its step-by-step flow using a standard flow diagram with appropriate symbols.
5. Analyse the platform's navigation structure, perform a card sorting exercise, and create a site map representing the information architecture.



## Task 1 — Solution Ideation (Crazy 8s)

### UX Problem Selected
**"The Amazon.in homepage is cluttered and overwhelming, making it difficult for users — especially first-time or low-tech users — to find what they need quickly."**

### What is Crazy 8s?
Crazy 8s is a rapid ideation technique where the designer generates **8 distinct ideas in 8 minutes** — one idea per minute. The goal is quantity over quality, forcing creative thinking beyond the obvious first solution.



### 8 Ideation Concepts

| # | Idea Title | Description |
|---|---|---|
| 1 | **Personalised home feed** | Show only categories the user browses most. First-time users see a simple "What are you looking for?" prompt with 6 large category tiles. |
| 2 | **Icon-first navigation bar** | Replace the text-only navigation with icon + label pairs. Each category gets a recognisable icon (cart for groceries, laptop for electronics) so users can scan faster. |
| 3 | **Simplified mobile-first layout** | Reduce the homepage to a single search bar, 4 featured category cards, and today's top deal. Remove the promotional banners completely for the first visit. |
| 4 | **Smart login prompt** | Show a soft sticky banner at the top: "Sign in to see your deals" with one-tap login. Disappears once the user is logged in. Solves the invisible login problem. |
| 5 | **Progressive disclosure cards** | Product cards show only the main image and price by default. Hovering or tapping reveals the product name, rating, and buy button — reducing visual clutter. |
| 6 | **Voice / regional language search** | Add a microphone icon next to the search bar with auto-detect for Tamil, Hindi, or English. Reduces friction for users uncomfortable with typing in English. |
| 7 | **Deal of the day spotlight** | Replace the rotating banner with a single, large, full-width "Deal of the Day" card. One product, one price, one action — eliminates choice paralysis from multiple simultaneous promotions. |
| 8 | **Assisted onboarding for new users** | On first visit, show a 3-step mini-wizard: "Tell us what you shop for" → "Set your location" → "You're ready!" — then show a tailored homepage. |



## Task 2 — User Stories

Based on the Amazon.in personas from Experiment 1 (Priya Ramesh — tech-savvy professional, and Murugan Selvam — elderly low-tech user):

| # | User Story |
|---|---|
| US1 | As a **first-time visitor**, I want to **see a clear Sign In button with an icon**, so that **I can log in quickly and access my saved addresses and wishlists**. |
| US2 | As a **busy professional**, I want to **search for a product and see clean, large results with clear images and prices**, so that **I can compare and decide without scrolling through cluttered cards**. |
| US3 | As an **elderly user**, I want to **browse products by large category icons instead of reading text labels**, so that **I can find what I need without feeling confused or overwhelmed**. |
| US4 | As a **deal-seeking shopper**, I want to **see one highlighted deal per visit clearly displayed on the homepage**, so that **I don't miss promotions and don't feel distracted by too many banners at once**. |
| US5 | As a **returning customer**, I want to **go directly to my cart and complete my purchase in as few steps as possible**, so that **I can save time and avoid re-entering my address and payment details every time**. |
| US6 | As a **mobile user in Tamil Nadu**, I want to **search using my voice in Tamil**, so that **I don't have to type long product names in English on a small keyboard**. |



## Task 3 — Narrative Scenario

### Selected User Story
**US3:** *"As an elderly user, I want to browse products by large category icons instead of reading text labels, so that I can find what I need without feeling confused or overwhelmed."*



### Scenario: Murugan Tries to Buy a Mixer Grinder

**User:** Murugan Selvam, 63, retired farmer, Villupuram district, Tamil Nadu.
**Device:** Shared Android smartphone (basic model, small screen).
**Time:** Saturday afternoon, 3:00 PM.
**Environment:** Sitting in his home's front veranda, moderate sunlight on screen, no reading glasses nearby.



Murugan's daughter called him from Chennai and told him to buy a mixer grinder online and she'll reimburse him — "just go to Amazon, Appa, it's easy." He opens the browser and types "amazon" hesitantly. The homepage loads. His eyes immediately land on the large rotating banner showing summer fashion deals — not what he wants. He squints and tries to read the black navigation bar. "Fresh… MX Player… Mobiles…" — he does not know what most of these mean.

He feels a quiet frustration. *"Where is kitchen items?"* He taps the hamburger menu hoping for clearer options. A long list of categories slides in, all in small English text. He scrolls slowly, unsure. He eventually taps "Home & Kitchen" by accident while trying to tap "Electronics."

He lands on the Home & Kitchen page. The product thumbnails are small, four across, and the text beneath them is tiny. He cannot clearly distinguish between a mixer, a blender, and a food processor from the small images. He zooms in awkwardly on his phone.

After about 4 minutes of frustration, he calls his grandson and asks him to help. He feels embarrassed — he wanted to do this on his own.

**Emotional arc:** Hopeful → Confused → Frustrated → Defeated

**Opportunity:** If the homepage had large, labelled category icons (especially in Tamil), and product cards were bigger with clearer images, Murugan could have completed this task independently in under 2 minutes.



## Task 4 — Flow Diagram

### Task: Searching and Adding a Product to Cart on Amazon.in

<img width="900" height="1268" alt="amazon_flow_diagram" src="https://github.com/user-attachments/assets/e3146c61-4ad8-4a96-b43a-154cbad36ccc" />

### Flow Description

The flow diagram covers the following path:

1. **Start** — User opens Amazon.in
2. **Logged in?** (Decision) — Yes → proceed | No → Show login prompt → Login → proceed
3. **Enter search term** in search bar
4. **Results found?** (Decision) — No → Show "No results" + suggest alternatives | Yes → Display product listing
5. **Select a product** from results
6. **Read product details** (images, price, reviews)
7. **Add to Cart**
8. **Continue shopping?** (Decision) — Yes → return to search | No → Go to Cart
9. **Proceed to Checkout**
10. **End**



## Task 5 — Information Architecture (IA)

### Website Selected: Amazon.in

### Step 1 — Card Sorting Exercise

Card sorting is a UX research method where content items (written on individual "cards") are grouped by users into categories that make sense to them.

**Method used:** Open card sorting (users define their own category names)

**Cards prepared (sample of 20 content items from Amazon.in):**

| Card No. | Content Item |
|---|---|
| C01 | Mobiles |
| C02 | Laptops |
| C03 | Headphones |
| C04 | Refrigerators |
| C05 | Air conditioners |
| C06 | Washing machines |
| C07 | Men's clothing |
| C08 | Women's sarees |
| C09 | Running shoes |
| C10 | Rice & dal |
| C11 | Snacks & beverages |
| C12 | Cooking oil |
| C13 | Baby diapers |
| C14 | Toys & games |
| C15 | Skincare products |
| C16 | Today's deals |
| C17 | Track my order |
| C18 | Return & refund |
| C19 | Amazon Pay |
| C20 | Gift cards |



### Step 2 — Card Groups (Sorted Categories)

After sorting, the cards naturally grouped into the following categories:

| Category | Cards Included |
|---|---|
| Electronics | C01, C02, C03 |
| Home appliances | C04, C05, C06 |
| Fashion | C07, C08, C09 |
| Grocery & food | C10, C11, C12 |
| Kids & baby | C13, C14 |
| Beauty & personal care | C15 |
| Offers & deals | C16 |
| Orders & support | C17, C18 |
| Payments & rewards | C19, C20 |



### Step 3 — Site Map

```
Amazon.in
│
├── Home
│   ├── Search bar
│   ├── Today's deals banner
│   └── Recommended for you
│
├── Electronics
│   ├── Mobiles
│   ├── Laptops & computers
│   └── Audio & headphones
│
├── Home appliances
│   ├── Refrigerators
│   ├── Air conditioners
│   └── Washing machines
│
├── Fashion
│   ├── Men's clothing
│   ├── Women's clothing
│   └── Footwear
│
├── Grocery & food
│   ├── Staples (rice, dal, oil)
│   └── Snacks & beverages
│
├── Kids & baby
│   ├── Baby care
│   └── Toys & games
│
├── Beauty & personal care
│   └── Skincare, haircare
│
├── Offers & deals
│   └── Today's deals, Coupons
│
├── My account
│   ├── Track my order
│   ├── Returns & refunds
│   └── Wishlist
│
└── Payments & rewards
    ├── Amazon Pay
    └── Gift cards
```



## Summary

| Task | Tool / Method | Key Output |
|---|---|---|
| Solution ideation | Crazy 8s | 8 design ideas for homepage clutter problem |
| User stories | Persona-based writing | 6 user stories covering diverse needs |
| Narrative scenario | Scenario writing | Murugan's mixer grinder task story |
| Flow diagram | Task flow with standard symbols | Search → Add to cart flow (see image) |
| Information architecture | Card sorting + site map | 9 grouped categories + full site map |
