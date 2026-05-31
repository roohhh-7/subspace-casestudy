# Product Intern Assignment

## PRODUCT TEARDOWN & STRATEGIC ROADMAP: SUBSPACE

**Target Role:** Product Intern  
**Company of Interest:** Subspace.money  
**Submission Date:** May 31, 2026  
**Candidate:** Rohit S  

## Section 01. Product Overview

Subspace is a multi-product consumer platform positioned at the intersection of group utility finance and digital asset management in India. Operating with an automated AI-driven back-end architecture, the platform aims to reduce individual discretionary costs through three core consumer offerings:  

### Core Pillars
*   **Subscription Sharing Marketplace:** A peer-to-peer matchmaking directory where users pool slots for premium family accounts (such as YouTube Premium or Spotify) to split recurring costs.
*   **Discounted Gift Cards:** A single-user digital checkout system allowing instant voucher purchases (e.g., Zomato, Amazon) at a markdown rate.
*   **Subspace Minutes:** A localized, hyper-local physical gadget rental marketplace offering short-term, rapid deliveries on cameras, audio accessories and gaming hardware.

## Section 02. Executive Summary

*   **The Status Quo:** Subspace is a highly profitable, bootstrapped consumer fintech platform in India pulling in a massive ₹36.5 crore ARR with a lean team and a 90%+ AI-driven backend.
*   **The Core Paradox:** While single-user transactions are perfectly optimized (e.g., live testing of buying a gift card via UPI delivered an instant redemption code), the core multi-user subscription sharing flow remains manual, fragile, and prone to high user friction.
*   **The Objective:** This teardown evaluates the mobile (iOS and Android) and web touchpoints to identify critical friction points across onboarding, platform parity, and legal compliance.
*   **The Ultimate Goal:** Provide an immediate, actionable product blueprint to transform Subspace from a manual matchmaking directory into a fully automated financial sharing utility.

## Section 03. Research Methodology

The product was evaluated through a combination of firsthand product usage, competitor benchmarking and user research.

### Sources Used
*   **Cross-Platform Live Testing (Android, iOS, Web):** Personally tested the end-to-end interface and payment flows. This included executing a live UPI transaction to successfully buy a digital gift card and auditing the manual subscription-sharing setup against Subspace's official feature blogs.
*   **Onboarding & Gateway Audits:** Initiated web authentication protocols via WhatsApp to systematically trace OTP delivery states and channel verification setups.
*   **Public Feedback & Reviews:** Scoured user forums like reddit and app store like google play reviews to evaluate long-term consumer sentiment regarding account stability, bugs, and support response times.
*   **Competitor Benchmarking:** Conducted a structural parity audit against primary domestic and global alternatives, specifically examining the automation and compliance setups of Fleek 2.0 and Spliiit.

### Evaluation Areas
*   **GTM & ICPs:** Assessing how effectively Subspace establishes immediate institutional trust and converts cost-conscious users during early onboarding stages.
*   **Competitor Analysis:** Evaluating Subspace's core moats, cost structures, and feature depth against alternative market players.
*   **Features & Services:** Auditing the operational efficiency drop-off when moving from single-user digital checkouts to multi-user group sharing loops.
*   **User Experience (UX):** Mapping out user journey friction, human-dependent communication loops, and data persistence across the interface.
*   **Potential Collaborations:** Pinpointing high-leverage B2B integrations to automate back-end logistics and eliminate manual product overhead.

The analysis focuses on identifying high-impact product opportunities through real product interactions, user sentiment and competitive benchmarking. All recommendations are based on observed user flows, marketplace behaviour and business impact rather than hypothetical feature suggestions.

## Section 04. User Journey Walkthrough

To understand the core friction points within Subspace, we must look at how the application handles its two primary transaction types: the seamless single-user voucher flow and the fragmented multi-user subscription-sharing loop.

### 4.1 The Single-User Flow: Purchasing a Gift Card
Live testing reveals that Subspace's single-user digital rails are highly optimized and execute cleanly.
<img width="567" height="106" alt="image" src="https://github.com/user-attachments/assets/0898652f-5ed7-434a-a230-57bb7c9fea44" />


### 4.2 The Multi-User Flow: Joining a Shared Subscription Group
When a co-subscriber attempts to join a shared group (e.g., a YouTube Premium Family plan), the journey shifts from an automated utility into a manual coordination loop.

<img width="564" height="164" alt="image" src="https://github.com/user-attachments/assets/e7244697-79db-4915-a5b3-8469b075128a" />


*Methodology Note on Multi-User Workflows: While single-user voucher delivery was verified firsthand via live checkout, the end-to-end multi-user subscription-sharing journey was mapped by analyzing official Subspace feature blogs.*

## Section 05. Competitor Analysis

| Feature / Dimension | Subspace | Fleek | Spliiit |
| :--- | :--- | :--- | :--- |
| **Main Purpose** | P2P public/private subscription cost sharing, subscription tracking, discounted brand gift cards, and hyper-local physical gadget rentals. | Helps users track subscriptions, avoid unwanted renewals, and split costs with friends. | Connects people globally to legally share subscription plans and reduce costs. |
| **Target Users** | Indian users, especially those who prefer UPI and newly added credit card integration. | Urban Indian users who pay for multiple streaming, software, and premium subscriptions. | Users in Europe, UK, and Canada looking to share subscription costs across countries. |
| **How Sharing Works** | Hosts create listings, upload proof of purchase, and coordinate members through in-app chat. (as per blogs) | Automatically detects subscriptions and helps users split bills within their friend groups. | Uses official family/team-sharing features and invite-based access to add members. |
| **Trust & Safety** | AI verifies subscription proof, payments are released gradually, and support helps resolve issues. | Limits sharing to trusted friends and family, reducing fraud risks. | Strong compliance, identity verification, and regulated payment handling. |
| **Platform Availability** | Mainly Android app and website; iOS lacking core moats. | Available on both Android and iOS with a consistent experience. | Available on web, Android, and iOS. |
| **Products & Services** | Subscription sharing and managing, gift cards and gadget rentals. | Subscription management and cost-splitting only. | Dedicated subscription-sharing marketplace across many categories. |
| **Revenue Model** | Earns from gift card commissions, rental fees. | Earns from subscription bundles, affiliate partnerships, and loyalty rewards. | Earns through transaction fees and premium memberships. |

## Section 06. SWOT analysis

### Internal Factors

**Strengths (Core Moats)**
*   **True Hybrid Architecture:** Possesses backend infrastructure capable of tracking and auto-detecting recurring subscription charges via API, alongside direct credit card bill splitting.
*   **Dual-Engine Target Demographics:** Captures both mass-market, budget-conscious users utilizing native UPI payment rails, and premium credit card holders splitting heavy recurring bills.
*   **Escrow Fraud Barrier:** Operates a secure escrow ledger system that releases funds to hosts incrementally on a daily basis, mitigating account-takeover risk and building consumer trust.
*   **Highly Diversified Revenue Flywheel:** Multiple revenue streams running concurrently, including marketplace group transaction take-rates, digital voucher margins, and hyper-local gadget rentals.

**Weaknesses (Product & Operational Gaps)**
*   **Buried Automation Stack:** High-leverage automated tracking and credit card features are deeply buried or underpromoted, causing the primary user experience to default to manual steps.
*   **Fulfilment Bottleneck:** The core P2P sharing cycle depends heavily on manual human coordination via an in-app chat box (requiring hosts to manually type emails, copy links, and wait 12–24 hours for platform approval).
*   **Severe Cross-Platform Disparity:** Visual design layouts, service catalogs, and onboarding paths vary significantly across the Web portal, Android application and mainly iOS system.
*   **Diluted Core Focus:** Allocating lean operational resources across three completely different products (Marketplace, Vouchers, and Physical Hardware Rentals) limits execution velocity on the core product.

### External Factors

**Opportunities (Growth Paths)**
*   **Automated Verification Links:** Transforming the manual, chat-dependent credential loop into an automated integration by allowing users to upload programmatic family invite links directly.
*   **Open-Banking Financial Dashboards:** Exposing the underlying auto-detection API directly to users to create an intuitive financial health dashboard that tracks all recurring household bills.
*   **B2B Corporate Partnerships:** Packaging the subscription-splitting infrastructure as an employee perk program for remote teams managing corporate SaaS bundles.
*   **B2B OTT Partnerships:** Collaborating with domestic OTT apps (e.g., JioCinema, Zee5) to offer platform-approved co-subscription bundles.

**Threats (Market Risks)**
*   **Tightening Provider Policies:** Major platform providers (like Netflix, Google, or Spotify) actively tightening family sharing policies and geofencing multi-user groups.
*   **Direct Automation Competitors:** Pure-play utility services (like Fleek 2.0 or Spliiit) capturing urban user segments through highly optimized, single-purpose financial interfaces.
*   **Evolving Payment Compliance:** Regulatory updates regarding recurring auto mandates or peer-to-peer escrow accounts within the domestic fintech landscape.

## Section 07. Feedback Section

### Feedback 01: Onboarding Trust Deficit (GTM & ICPs)
*   **Observed:** Live onboarding testing across web and mobile reveals major branding misalignments. When requesting an OTP via SMS, the message is signed by a third-party header (-SYNCHROVOX AI PRIVATE LIMITED). If attempting a WhatsApp login on the web app, the message flow hits a dead-end with zero OTP delivery, operating under an unverified personal profile named "~Mritunjoy Das Bot" using a standard mobile number. Furthermore, the developer support email listed publicly on the Google Play Store uses a personal address (`cubetechnologyindia at gmail . com`).
 <img width="1362" height="404" alt="image" src="https://github.com/user-attachments/assets/7db9ad03-b74b-48bc-9771-5dc3feca85a2" />

*   **Problem:** This creates a huge drop-off point at Step 0 of the user onboarding funnel. For a consumer fintech platform managing group finances, receiving security codes from an unrecognized entity ("Synchrovox AI") alongside an unverified personal WhatsApp profile completely breaks institutional trust. It triggers immediate fraud suspicions, causes user churn before ecosystem entry and might drive public scam accusations on forums.
*   **Ship Instead:**
    *   **Unify the Brand Interface:** Establish an official, verified Telecommunication DLT registration in India to secure a dedicated, recognizable brand SMS header (e.g., SUBSPC or SBSPCE).
    *   **Upgrade to Enterprise Gateways:** Fully deprecate the manual personal WhatsApp script setup. Integrate a professional, enterprise-grade business gateway (e.g., Infobip or Msg91 WhatsApp Business API) featuring a strict fallback loop—if a WhatsApp template delivery fails, automatically route a branded SMS backup.
    *   **Fix Public Touchpoints:** Instantly update the public developer contact email across all App Store and Google Play listings to a verified corporate domain address (`support@subspace.money`).

### Feedback 02: Building for iOS Users (UX, Growth & Strategy)
*   **Observed:** During my first-hand cross-platform analysis of the live apps, I discovered that the iOS application completely lacks Subspace's primary business moat, the peer-to-peer subscription-sharing marketplace. While testing the iPhone build, I found its functions was limited to discounted brand gift cards only. There was no subscription management and any indication of “Subspace minutes” as well, it only had a static "Suggest a Subscription!" feedback input box.
 <img width="722" height="252" alt="image" src="https://github.com/user-attachments/assets/886b9591-95d1-4360-800b-b448ffa077a0" />
<img width="463" height="480" alt="image" src="https://github.com/user-attachments/assets/1421d1fb-5ab2-4788-980e-b96b86b5772f" />

*   **Problem:** Leaving subscription sharing off iOS cuts Subspace completely out of India's highest Average Revenue Per User (ARPU) demographic which has the people most likely to pay for premium plans like Netflix 4K or YouTube Premium. It also completely breaks the network effect. If an Android host wants to share a plan with their friends, but half those friends use an iPhone, they can't do it through the app. The group falls apart, and they just go back to splitting bills manually on WhatsApp.
*   **Ship Instead:** The reason they haven't launched this on iOS is likely Apple's strict Guideline 3.1.1, which bans public credential reselling and slaps a 30% tax on digital sales. To get around this, Subspace shouldn't clone the Android store on iOS. Instead, they should build a compliant, private Expense Ledger modelled after global players like Spliiit:
    1.  **Private group:** An iOS host sets up a private billing group and invites their friends directly via text or email, keeping it out of a public storefront.
    2.  **Escrow Layering:** Co-subscribers pay their split share inside the iOS app using standard UPI deep-linking.
    3.  **Programmatic Distribution:** Once the money hits escrow, Subspace programmatically emails the official family plan invite links to the co-subscribers. This keeps the app fully compliant with Apple's rules while finally letting iOS users into the ecosystem.

### Feedback 03: The Manual OTP Friction (UX & Services)
*   **Observed:** Looking closely at user complaints on Reddit and the Play Store, the biggest operational bottleneck happens right after payment when users face a "device not part of household" lockout. Currently, the automation completely halts; the co-subscriber has to hop into an in-app chat box, message the group host, and wait hours for them to manually forward a verification link or a 4-digit OTP code.
   <img width="669" height="426" alt="image" src="https://github.com/user-attachments/assets/1d62088d-cdef-40ff-a15d-469c93272907" />

*   **Problem:** This manual dependency completely destroys user retention and creates an unmanageable customer support burden. Users buying a slot expect instant access. When high host unresponsiveness leaves them locked out of a service they just paid for, they immediately cancel, file payment disputes, and leave highly damaging reviews online.
*   **Ship Instead:** Completely remove the human bottleneck by implementing an automated, server-side Email-Parsing Interception Gateway modeled after global builders like GamsGo:
    1.  **Dedicated Forwarding Aliases:** When a host lists a static-credential group, require the master account to be registered under a platform-provided forwarding email alias (e.g., `group_1092@subspace.money`).
    2.  **Programmatic Scraped Delivery:** When a buyer encounters a geofence block and clicks "Verify Household", the system triggers Netflix to mail the verification link to that alias. Subspace's backend parser intercepts the email in real-time, extracts the 4-digit code, and surfaces it directly on the buyer's dashboard within 60 seconds—zero host interaction required.

### Feedback 04: Legal & Geofencing Vulnerabilities (Collaboration & Compliance)
*   **Observed:** Subspace's original subscription-sharing model relies heavily on hosts sharing account credentials with buyers. While this may work for some services, it creates significant issues on platforms like Netflix. In regions such as Europe, platforms like Spliiit can facilitate Netflix sharing through Netflix's official "Extra Member" feature, allowing users to join accounts without exchanging passwords. However, Netflix has removed the Extra Member option in India, encouraging users to purchase individual plans instead of shared access.
*   <img width="928" height="213" alt="image" src="https://github.com/user-attachments/assets/cb3e1f7b-f684-405e-84f5-cffa09a57b34" />

*   **Problem:** Netflix actively enforces household restrictions using Wi-Fi networks, IP addresses, and device recognition. Users accessing an account from outside the designated household are frequently asked to verify access through one-time codes sent to the account owner. This creates a poor user experience, as buyers must repeatedly contact hosts for access codes or account assistance. The result is recurring logouts, increased refund requests, higher customer support costs, and reduced trust in the platform.
*   **Ship Instead:** Reduce dependence on high-risk password-sharing models and build the platform around more scalable and compliant access mechanisms.  
    **Architecture:**
    1.  **Prioritize Official Family Invites:** Focus on services that support legitimate family-plan invitations, such as YouTube Premium, Spotify, and Microsoft 365, where users join through invite links and maintain their own credentials.
    2.  **Expand Through B2B OTT Partnerships:** Partner directly with Indian streaming platforms such as Zee5, JioHotstar, and SonyLIV. Many of these services primarily limit simultaneous screens rather than enforcing strict household-based access controls, creating a more reliable user experience.
    3.  **Move Away from Shared Credentials:** Gradually deprioritize listings that require users to share master account usernames and passwords, especially on platforms with aggressive geofencing and household verification systems.

### Feedback 05: Automating Host Listings & Payments (Supply & Fintech Scaling)
*   **Observed:** Subspace has automated personal subscription tracking, but the process of creating shared subscription groups remains largely manual. Hosts must enter subscription details, upload receipts, and wait for verification before their listing goes live. Additionally, users are often encouraged to link their bank accounts for automatic bill detection, which can create trust and privacy concerns for many Indian users.
*   **Problem:** The manual verification process creates friction and slows down the growth of the subscription marketplace. At the same time, asking users to connect their bank accounts introduces a significant trust barrier, leading to onboarding drop-offs. If users instead rely on manual entry, billing mistakes, missed renewals, and service disruptions become more likely.
*   **Ship Instead:** Reduce friction by automating subscription detection and group payments while maintaining user privacy.  
    **Architecture:**
    1.  **On-Device Subscription Detection:** With user consent, use a privacy-first SDK that scans subscription-related SMS alerts and email receipts directly on the user's device. This allows the app to automatically detect and verify subscription purchases without requiring manual receipt uploads or bank account linking.
    2.  **Multi-Party UPI Autopay:** When users join a shared subscription, allow them to opt into a recurring UPI Autopay mandate for their share of the payment. The platform can then automatically collect contributions before the renewal date, eliminating manual payment requests, follow-ups, and collection delays.

## Section 08. Prioritization Matrix

| # | Feedback Title | Expected User Value | Engineering Complexity | Launch Priority |
| :--- | :--- | :--- | :--- | :--- |
| **01** | Onboarding Trust Deficit (GTM & ICPs) | High – Instantly reduces drop-offs and improves conversion at the top of the funnel | Low – Primarily copy changes, UX refinements, and deferred verification flows | P0 (Quick Win) |
| **05** | Automating Host Listings & Payments (Supply & Fintech Scaling) | High – Eliminates verification delays and automates subscription split payments | Medium – Requires on-device parsing capabilities and UPI Autopay integration | P0 (Core Engine) |
| **03** | The Manual OTP Friction (UX & Services) | High – Improves access reliability and reduces customer churn | Medium–High – Requires automated invite delivery, escrow integration, and refund workflows | P1 (High-Value Feature) |
| **02** | Building for iOS Users (UX, Growth & Strategy) | Medium – Expands reach to high-value iOS users and improves platform accessibility | High – Requires alternative checkout architecture and platform-compliant billing flows | P1 (Strategic Growth) |
| **04** | Legal & Geofencing Vulnerabilities (Strategy & Compliance) | High – Reduces platform risk and improves long-term sustainability | High – Requires catalog restructuring, partnership efforts, and backend changes | P2 (Long-Term Pivot) |

## Section 09. Conclusion

Subspace solves a real problem by helping users reduce the cost of digital subscriptions through sharing. However, several parts of the current experience are still manual, including onboarding, subscription verification, payment collection, and access fulfillment. These friction points can affect user trust, retention, and overall platform growth.

**Based on the analysis, the most important focus areas are:**
*   Improve onboarding and reduce trust barriers for new users.
*   Automate subscription verification and group payment collection.
*   Reduce reliance on manual chats and host intervention for access delivery.
*   Focus on more reliable and sustainable subscription-sharing models.

By addressing these areas, Subspace can provide a smoother user experience, reduce support overhead, and build a stronger foundation for future growth.

### Final Recommendation
Focus first on fixing the core user journey before expanding the platform. Improving trust, automation, and reliability will likely have a greater impact on user growth and retention than adding new features or services.
