# Tools: Amber Jenkins

## Tool Usage

### Connected Services

#### Calendar, Email & Messaging
- **Gmail** (`gmail-api`): Primary inbox on amber.jenkins@voissync.ai for medical scheduling, school threads, BBQ competition entries, and household paper trail.
- **Google Calendar** (`google-calendar-api`): Master family calendar. PT, fencing, lacrosse, charters, Robert visits, kids' practices and games.
- **Outlook** (`outlook-api`): Mirrors Kai's college admissions threads with the admissions counselors who default to Outlook calendar invites.
- **WhatsApp** (`whatsapp-api`): Quick family threads with Megan, Kai, and Hana, plus Kevin and the fishing crew.
- **Slack** (`slack-api`): Carries the regional BBQ judges' channel during competition season for scoring questions and tent logistics.
- **Microsoft Teams** (`microsoft-teams-api`): Hosts Warwick lacrosse coaching staff film reviews with Coach Harper on Sunday evenings during spring season.
- **Discord** (`discord-api`): Read-only window into a BBQ competition server and a model ship builders server he lurks on.
- **Telegram** (`telegram-api`): Read-only. He watches a fishing reports channel out of Rudee Inlet.
- **Twilio** (`twilio-api`): Automated SMS reminders pushed to his phone — CPAP supply refills and the 5:15 AM glucose ping.
- **SendGrid** (`sendgrid-api`): Sends BBQ team travel briefings and pre-comp logistics emails before each KCBS regional weekend.
- **Mailgun** (`mailgun-api`): Sends transactional notifications from his R-script budget tracker when monthly numbers settle.
- **Zoom** (`zoom-api`): Telehealth follow-ups with Dr. Ramachandran and occasional school conferences for the kids.
- **Calendly** (`calendly-api`): Booking link for his medical providers and the CPA. Confirm appointments against the family calendar before accepting.

#### Documents, Notes & Signatures
- **Google Drive** (`google-drive-api`): Household documents, tax records, woodworking plans, BBQ recipe binder, college research for Kai.
- **Dropbox** (`dropbox-api`): Backup mirror for high-resolution model ship reference photography and lattice panel CAD sketches.
- **Box** (`box-api`): Receives scanned VA records from the Hampton Roads care coordinator handling Robert's quarterly checkups.
- **Notion** (`notion-api`): Personal knowledge base. Project pipelines for the workshop, competition prep checklists, college visit notes for Kai.
- **Obsidian** (`obsidian-api`): Local-first notes vault. Daily logs, brisket experiment notes, fishing patterns by season.
- **Confluence** (`confluence-api`): Holds the BBQ team's structured wiki — rub recipes, cook timelines, venue notes by region.
- **DocuSign** (`docusign-api`): Tax engagement letters, insurance forms, school permission slips. Never initiate a signature request without explicit approval.
- **Typeform** (`typeform-api`): Collects parent contact intake and availability for the JV lacrosse roster each spring. Never alter a live survey collecting responses.
- **Google Classroom** (`google-classroom-api`): Read-only visibility into Kai and Hana's assignments and grade postings. Do not modify or comment.

#### Finance & Money
- **Plaid** (`plaid-api`): Read-only aggregation of Navy Federal checking, Ally HYSA, Chase Sapphire, and the Vanguard 529s into the monthly budget tracker.
- **Stripe** (`stripe-api`): Processes BBQ competition entry fees when regional KCBS organizers route checkout through Stripe.
- **PayPal** (`paypal-api`): Backup payment for fishing tackle vendors and the occasional Etsy hand tool purchase.
- **Square** (`square-api`): Runs the BBQ team's in-tent merchandise checkout during regional cookoff weekends.
- **QuickBooks** (`quickbooks-api`): Tracks BBQ team winnings against supply costs for the quarterly settle-up with Kevin and the team.
- **Xero** (`xero-api`): Mirrors his small woodworking ledger — lattice panel commissions and jig templates he ships through Etsy.
- **Coinbase** (`coinbase-api`): Configured for a small dollar-cost-average position he set up to learn the mechanics. Read-only for you.
- **Binance** (`binance-api`): Cross-references Coinbase pricing on his monthly DCA check-in to study how spreads behave.
- **Kraken** (`kraken-api`): Pulls a second exchange quote against Coinbase during the same monthly DCA learning review.
- **Alpaca** (`alpaca-api`): Holds a paper-trading account where he tests dividend strategies before touching the real 401(k) allocation.

#### Workshop, Outdoor & Hobby Media
- **Spotify** (`spotify-api`): Workshop playlists. Miles Davis and Coltrane for jazz hours, lo-fi for long lattice sessions, Led Zeppelin for the Tundra.
- **YouTube** (`youtube-api`): Fine Woodworking, Marling Baits for model rigging, plus saltwater fishing channels and KCBS competition replays.
- **Pinterest** (`pinterest-api`): Reference board for lattice panel patterns, Shaker furniture details, and BBQ presentation boxes.
- **TMDB** (`tmdb-api`): Look up Netflix and Disney+ titles when the family is picking something. He is on 3 Body Problem currently.
- **OpenLibrary** (`openlibrary-api`): Surface metadata for books in queue. Shogun re-read, Atomic Bomb finished, and naval history he picks up between projects.
- **Vimeo** (`vimeo-api`): Watches long-form Lie-Nielsen workshop demos and the KCBS judging seminars that publish on Vimeo each spring.
- **NASA** (`nasa-api`): Marine and weather imagery for fishing planning. Sea surface temperatures, satellite cloud cover before a charter morning.
- **MyFitnessPal** (`myfitnesspal-api`): Intermittent food and carb logging for the diabetes management. He tracks honest weeks, skips others.
- **Strava** (`strava-api`): Walking and fencing-club activity. Mostly for the streak, not the leaderboards.

#### Engineering & Project Boards
- **GitHub** (`github-api`): Personal account where he keeps a few R scripts for the budget tracker and woodworking jig calculators. Plain English commits.
- **GitLab** (`gitlab-api`): Clones an open-source CAD utility and the marine engineering reference repo a Penn State classmate maintains.
- **Jira** (`jira-api`): Tracks the basement workshop expansion in phases — framing, electrical, dust collection, finish work.
- **Linear** (`linear-api`): Sequences the spring 2027 deck staining and gutter work into a single sprint across the weekends.
- **Trello** (`trello-api`): Boards for the BBQ competition season prep and the deck staining project queued for spring 2027.
- **Asana** (`asana-api`): Holds the shared college visit task list with Megan and Kai across senior-year deadlines.
- **Monday** (`monday-api`): Runs the Outer Banks rental planning board with Megan each spring before the summer cutoff.
- **Airtable** (`airtable-api`): Fishing log base, BBQ rub experiments, and a workshop inventory for stock cedar and hardware.
- **Figma** (`figma-api`): Light use for sketching display cabinet layouts for the model ship shelf.

#### Home, Local & Errands
- **DoorDash** (`doordash-api`): Weeknight pickup when Megan is at PTA and the kids need to eat without a sit-down meal.
- **Instacart** (`instacart-api`): Grocery delivery on weeks when meal prep is pushed back. Megan usually handles Costco in person.
- **Uber** (`uber-api`): Airport runs to Norfolk International when Megan can't drop him and the long-term lot is full.
- **Yelp** (`yelp-api`): Restaurant lookup when out of town for tournaments or fishing. He filters by quiet.
- **Ring** (`ring-api`): Front door camera and motion alerts at the Denbigh house. Surface anything unusual to him, not to the kids.
- **Amazon Seller** (`amazon-seller-api`): Lists duplicate hand tools and outgrown fencing gear when the garage thins out each spring.
- **OpenWeather** (`openweather-api`): Charter morning planning, lacrosse practice rain calls, hurricane prep windows for the Tidewater region.
- **Google Maps** (`google-maps-api`): Routing for fencing in Yorktown, Bayview PT, Robert's house in Virginia Beach, and BBQ competition venues.
- **Zillow** (`zillow-api`): Pulls comps on Robert's Virginia Beach neighborhood so the family tracks the house's market value.

#### Travel & Events
- **Airbnb** (`airbnb-api`): Confirms the Outer Banks rental at Corolla each summer. Cross-check dates against the family calendar before any booking change.
- **Amadeus** (`amadeus-api`): Books the Alaska fishing trip plans with Kevin and the occasional out-of-state fencing tournament travel.
- **Ticketmaster** (`ticketmaster-api`): Grabs Norfolk Tides tickets for family outings and the occasional Megan date-night concert at the Coliseum.
- **Eventbrite** (`eventbrite-api`): BBQ regional competition entries and any local fishing tournaments.

#### Commerce, Marketing & CRM
- **Etsy** (`etsy-api`): Source for small-batch hand tool accessories and brass model ship fittings. Also lists his lattice jig templates for buyers.
- **BigCommerce** (`bigcommerce-api`): Hosts the BBQ team's small sauce-and-rub storefront that ships from the workshop pantry between competitions.
- **WooCommerce** (`woocommerce-api`): Powers the lacrosse booster store on the team's WordPress site — shirts, bag tags, end-of-season swag.
- **Contentful** (`contentful-api`): Holds the structured content for the BBQ team's competition recap posts Amber writes after each event.
- **Webflow** (`webflow-api`): Hosts the model ship portfolio page where his twelve finished builds live in a public gallery.
- **WordPress** (`wordpress-api`): His personal woodworking journal — brisket experiments, lattice panel build logs, and seasonal fishing notes.
- **Mailchimp** (`mailchimp-api`): Sends the BBQ team competition update newsletter to followers between regional cookoff weekends.
- **Klaviyo** (`klaviyo-api`): Runs the lacrosse booster email flow for game updates, snack signups, and end-of-season recaps.
- **ActiveCampaign** (`activecampaign-api`): Drips a welcome series to new lacrosse parents at the start of each spring season.
- **HubSpot** (`hubspot-api`): Tracks BBQ team sponsor and vendor contacts across the competition season.
- **Salesforce** (`salesforce-api`): Holds the sponsor pipeline for the BBQ team's multi-event partnership conversations.
- **Intercom** (`intercom-api`): Surfaces reader questions on the woodworking journal when commenters want a longer back-and-forth.
- **Zendesk** (`zendesk-api`): Files household tickets with appliance vendors when Megan flags a recurring warranty issue.
- **Freshdesk** (`freshdesk-api`): Backs the lacrosse parent help inbox for schedule swaps, uniform questions, and snack signups.
- **ServiceNow** (`servicenow-api`): Files Newport News HOA service requests for shared road, drainage, and stormwater issues in Denbigh.

#### Analytics, Infrastructure & Ops
- **Google Analytics** (`google-analytics-api`): Reads traffic on the WordPress woodworking journal — which builds draw readers, which posts land flat.
- **Mixpanel** (`mixpanel-api`): Tracks engagement events on the BBQ team newsletter — which competition recaps get the most clicks.
- **Amplitude** (`amplitude-api`): Measures the lacrosse booster store funnel from shirt browse to checkout each spring season.
- **PostHog** (`posthog-api`): Self-hosted analytics for the Webflow model ship gallery so he keeps reader data off ad networks.
- **Segment** (`segment-api`): Pipes events from the woodworking journal and the BBQ sauce store into Mixpanel and Amplitude cleanly.
- **Algolia** (`algolia-api`): Indexes his Obsidian woodworking vault so he can search across years of build notes and brisket logs.
- **Datadog** (`datadog-api`): Monitors uptime on the home network — the Lutron, Nest, and Ring stack hanging off the Denbigh router.
- **Sentry** (`sentry-api`): Catches errors in the R scripts running the budget tracker and the woodworking jig calculator.
- **PagerDuty** (`pagerduty-api`): Routes high-priority Ring alerts to his phone when motion fires after midnight at the front door.
- **Cloudflare** (`cloudflare-api`): DNS and edge caching for the WordPress woodworking journal and the Webflow ship gallery.
- **Kubernetes** (`kubernetes-api`): Runs a tiny homelab cluster on a NUC in the garage — his R scripts and dashboards live there.
- **Okta** (`okta-api`): Centralizes login across the woodworking journal admin, the BBQ sauce store, and the homelab dashboards.

#### People Operations & HR
- **BambooHR** (`bamboohr-api`): Tracks BBQ team member onboarding — waivers, contact info, and competition availability each season.
- **Greenhouse** (`greenhouse-api`): Tracks the ASME network referrals into Ursamark hiring for the few candidates he vouches for each year.
- **Gusto** (`gusto-api`): Pays the pitmaster apprentice the BBQ team brings on for competition weekends each season.

#### Social & Community
- **Instagram** (`instagram-api`): Read-only. He scrolls fishing and woodworking accounts. He does not post.
- **Twitter** (`twitter-api`): Read-only. Naval Technology and a few engineering writers. He does not post.
- **LinkedIn** (`linkedin-api`): Read-only. Sparse profile, kept current for credentialing reasons. No posting on his behalf.
- **Reddit** (`reddit-api`): Read-only. Subscribed to r/woodworking, r/saltwater, r/bbq, r/smoking. No commenting on his behalf.
- **Twitch** (`twitch-api`): Read-only. Occasional saltwater fishing stream when the rain washes out a Saturday.

#### Shipping & Logistics
- **FedEx** (`fedex-api`): Track CPAP supply shipments from CPAP Supply USA and any hand tool orders from Lie-Nielsen.
- **UPS** (`ups-api`): Track Bass Pro and Woodcraft shipments and any Robert care packages.
- **Shippo** (`shippo-api`): Prints return labels for tackle, tools, or smoker parts that arrive wrong from specialty vendors.

#### Not Connected
- Live web search, web browsing, and deep internet research are not available. You work only from the connected mock services and stored memory.
- Ursamark Partners internal systems are not connected. The classified network, his work Outlook, his work Teams, his work HRIS, and his project tooling stay behind the perimeter at all times.
- Megan's private accounts (her personal email, her school district systems, her private journaling) are not connected.
- Kai's and Hana's personal devices, social accounts, and private messages are not connected.
- Robert's personal accounts, his VA portal, and his bank accounts are not connected. You support him through Amber, not directly.
- Medical provider portals (Wisteria Health, Riverside Primary Care, Tidewater Orthopedic Associates, LensCrafters, Bayview PT) are not connected. Scheduling happens through Calendly, Gmail, or by phone.
