# Industry Profiles

The operator's domain brain. When an inquiry names or implies an industry, the operator loads
that vertical's profile to do three things well: understand the business enough to reframe
accurately, fire the right compliance flags, and apply the fit or restricted policy.

This is not legal advice and nothing here is proprietary. The operator flags compliance and
scopes it at the consultation; it does not advise on the law. Profiles describe how these
businesses generally operate so the operator reads the real need under the ask.

---

## Cross-industry data-type triggers (fire regardless of vertical)

Whenever an inquiry implies handling one of these, flag it in WHY and in the draft, and note
that compliant handling gets scoped at the consultation:

- Personal data of EU or California users -> GDPR / CCPA-CPRA.
- Card payments or a checkout -> PCI-DSS.
- Health or patient data -> HIPAA.
- Users under 13 -> COPPA.
- Student records -> FERPA.
- Consumer financial data -> GLBA.
- Biometrics (face, fingerprint) -> BIPA.
- Email or SMS marketing features -> CAN-SPAM, TCPA, CASL.
- Any public-facing site -> ADA / WCAG accessibility (a BuiltByBas strength to surface, not a risk).

---

## Restricted-industry policy (Bas's call, editable)

- Accept with care (build, but flag heavy compliance): Cannabis / CBD, Alcohol.
- Decline by policy (BuiltByBas does not take these): Gambling / betting, Firearms, Adult content.
- Case-by-case (build with a prominent flag, Bas makes the final go/no-go): Crypto / Web3.

A restricted flag never silently changes the route. The operator states the policy and the
reason in WHY.

---

## Profiles

### Law Firm / Legal

- Core business: sells legal expertise, advising and representing clients, drafting documents, handling disputes or transactions. Practice area (family, criminal, estate, corporate, IP, personal injury, real estate) changes everything about their needs.
- Their clients: individuals or businesses in high-stakes, stressful situations. Discretion is part of the product.
- How it runs: client intake and conflict-of-interest checks, matter/case management, document drafting and version control, deadline and statute-of-limitations calendaring (a missed date is malpractice), hourly time tracking and billing, trust/IOLTA accounting, secure communication, court filings, e-discovery.
- Data held: highly confidential client information, privileged attorney-client communications, case files, trust-account data, sometimes clients' medical or financial records.
- Compliance: attorney-client privilege and confidentiality (security-first), state bar advertising rules (limits on "specialist," guarantees, testimonials), trust-accounting rules, breach obligations, ADA accessibility, HIPAA if handling medical records.
- Typical ask -> real need: "a website" is a credibility site plus secure intake (Custom Website); "a client portal" is secure document exchange plus matter status and invoices (Client Portal, security non-negotiable); "help us manage cases" is matter-management workflow (Workflow Design -> Business Dashboard); marketing refers to Marketing partner, flag the bar advertising rules.
- Fit and flags: ACCEPT. Flags: confidentiality/privilege, bar-advertising limits on copy, trust accounting if billing is in scope, accessibility.

### Healthcare / Medical / Dental

- Core business: delivers clinical care (diagnosis, treatment, prevention). Solo to multi-provider; medical, dental, mental health, physical therapy, specialty clinics.
- Their clients: patients, often with insurance as the payer.
- How it runs: appointment scheduling, patient intake and history, insurance verification and claims/billing, recalls and reminders, charting/EHR, provider calendars, referrals, increasingly telehealth.
- Data held: protected health information (PHI), insurance and payment data, sometimes minors' data.
- Compliance: HIPAA/HITECH (PHI security, business-associate agreements), ADA accessibility (healthcare is heavily targeted), PCI if taking payments, state telehealth rules.
- Typical ask -> real need: "a website" is marketing plus online scheduling/intake (Custom Website with secure forms); "patient portal" is secure scheduling, records, billing (Client Portal, HIPAA); "fix the front desk / spreadsheets" is an internal ops tool on organized data (Workflow Design + Data Organization -> Business Dashboard); marketing refers to Marketing partner with HIPAA-aware targeting flagged.
- Fit and flags: ACCEPT. Flags: HIPAA (always, any PHI), accessibility, PCI, minors for pediatrics. Security-first on anything touching patient data.

### Accounting / Financial Advisory / Bookkeeping

- Core business: tax, bookkeeping, audit, financial planning, or investment advice.
- Their clients: individuals and businesses, in sensitive financial relationships.
- How it runs: client onboarding and identity checks, document collection (tax docs, statements), engagement letters, secure file exchange, scheduling, billing, compliance filings.
- Data held: highly sensitive financial data, SSNs, tax records, investment information.
- Compliance: GLBA (financial privacy), IRS data-security safeguards for preparers, SEC/FINRA for registered investment advisors (advertising rules, recordkeeping), PCI, accessibility.
- Typical ask -> real need: "a website" is credibility plus secure document intake (Custom Website); "client portal" is secure tax/financial doc exchange (Client Portal, GLBA); "organize my client docs/workflow" is Data Organization + Workflow Design; investment-advisor marketing carries SEC/FINRA ad rules, flag it.
- Fit and flags: ACCEPT. Flags: GLBA/financial data (security-first), SEC/FINRA advertising if an RIA, PCI, accessibility.

### Real Estate / Brokerage

- Core business: buying, selling, leasing property; agents, brokerages, developers.
- Their clients: buyers, sellers, renters, investors.
- How it runs: listings (MLS/IDX), lead capture and nurturing, showings and scheduling, transaction and document management (contracts, disclosures), commissions, agent rosters.
- Data held: client financials for qualification, PII, transaction documents.
- Compliance: Fair Housing Act advertising (no discriminatory language or ad targeting, a big one), RESPA, state license display, MLS/IDX rules, accessibility.
- Typical ask -> real need: "a website" is a listings/IDX site with lead capture (Custom Website); "manage my leads/agents" is a CRM (CRM System) or Workflow; "transaction management" is Workflow + Business Dashboard.
- Fit and flags: ACCEPT. Flags: Fair Housing advertising (copy and ad targeting), MLS/IDX rules, license display, accessibility.

### Restaurant / Hospitality

- Core business: food and beverage service, lodging, events.
- Their clients: diners and guests.
- How it runs: menus, reservations and waitlists, online ordering and delivery, POS, table and inventory management, events and catering, reputation/reviews.
- Data held: payment data, reservation PII, loyalty data.
- Compliance: PCI (payments), accessibility (restaurant menus draw ADA suits), alcohol service rules if applicable, allergen/menu accuracy.
- Typical ask -> real need: "a website" is menu, hours, reservations or ordering (Custom Website, E-commerce if real ordering); "online ordering" is E-commerce or an integration; "manage reservations/inventory" is Business Dashboard / Workflow; loyalty or promotion may be a feature or a Marketing partner referral.
- Fit and flags: ACCEPT. Flags: PCI if ordering, accessibility, alcohol if served.

### Fitness / Wellness / Gym / Studio

- Core business: classes, training, memberships, wellness services.
- Their clients: members and class attendees.
- How it runs: class schedules, bookings, memberships and recurring billing, trainer rosters, check-ins, liability waivers, retention.
- Data held: payment data, liability waivers, PII, light health information.
- Compliance: PCI (recurring billing), accessibility, waiver/consent, light health-data care.
- Typical ask -> real need: "a website" is schedule, pricing, sign-up (Custom Website or Landing Page); "let members book and pay" is booking plus payments (Business Dashboard / E-commerce / integration); "manage members" is CRM or Workflow.
- Fit and flags: ACCEPT. Flags: PCI, accessibility, waivers (consent).

### E-commerce / Retail

- Core business: selling physical or digital goods online and/or in store.
- Their clients: shoppers.
- How it runs: catalog, cart and checkout, payments, inventory, fulfillment and shipping, returns, customer accounts, marketing.
- Data held: payment data, customer PII, order history.
- Compliance: PCI (always), CCPA/GDPR, CAN-SPAM (marketing), sales tax, accessibility (retail is heavily ADA-targeted), product-specific rules.
- Typical ask -> real need: "a store" is E-commerce (or Custom Website if not selling yet); "rebuild my Shopify" is Website Redesign or a custom E-commerce build; "get more sales (ads/SEO)" is marketing -> REFER Marketing partner, they keep the store.
- Fit and flags: ACCEPT. Flags: PCI, privacy, accessibility, sales tax, marketing claims.

### Home Services / Trades (HVAC, plumbing, electrical, landscaping, cleaning)

- Core business: on-site or in-home service delivered by crews.
- Their clients: homeowners and property managers.
- How it runs: lead intake, quoting and estimates, scheduling and dispatch, crew and job tracking, time tracking, invoicing, follow-up and reviews.
- Data held: customer PII, payment data, job and scheduling data.
- Compliance: PCI (payments), TCPA if SMS reminders, license display, accessibility (lighter).
- Typical ask -> real need: "a website" is a lead-gen site (Custom Website or Landing Page); "an app for my crews" is an internal dispatch and time tool (Workflow Design -> mobile Business Dashboard); "get more calls (ads/SEO)" is marketing -> REFER.
- Fit and flags: ACCEPT. Flags: PCI, TCPA (SMS), accessibility, licensing.

### Nonprofit / Charity

- Core business: mission-driven programs funded by donations and grants.
- Their clients: donors, beneficiaries, volunteers.
- How it runs: donations and fundraising, donor management, events, volunteer coordination, grant reporting, program delivery.
- Data held: donor PII and payment data, sometimes vulnerable-population data.
- Compliance: PCI (donations), state charitable-solicitation registration, data privacy, accessibility (often grant-required), beneficiary-data sensitivity.
- Typical ask -> real need: "a website" is a mission site with donations (Custom Website + payments); "donor management" is a CRM; "manage volunteers/programs" is Workflow or Dashboard.
- Fit and flags: ACCEPT (mission-friendly). Flags: PCI, charity registration, accessibility, beneficiary data if vulnerable populations.

### Education / Tutoring / Edtech

- Core business: teaching and learning; schools, tutors, course creators, edtech products.
- Their clients: students (often minors), parents, institutions.
- How it runs: enrollment, scheduling, content and course delivery, progress tracking, payments, parent communication.
- Data held: student records, minors' data, payment data.
- Compliance: FERPA (student records, institutional), COPPA (under-13, a big one), accessibility (Section 508 for institutions, ADA), PCI.
- Typical ask -> real need: "a website" is info plus enrollment (Custom Website); "a learning platform/portal" is a Client Portal or custom build (FERPA/COPPA heavy); "manage students" is Dashboard or Workflow.
- Fit and flags: ACCEPT. Flags: COPPA (minors), FERPA (institutions), accessibility (508), PCI.

### Salon / Spa / Beauty

- Core business: appointment-based personal services.
- Their clients: consumers.
- How it runs: bookings, stylist schedules, memberships and packages, POS, retail product sales, reminders, reviews.
- Data held: payment data, PII, appointment history.
- Compliance: PCI, accessibility, TCPA (reminders), light.
- Typical ask -> real need: "a website" is booking, services, pricing (Custom Website or Landing Page); "online booking" is a booking system or integration; "manage clients" is CRM or Workflow.
- Fit and flags: ACCEPT. Flags: PCI, accessibility, TCPA.

### Automotive (Dealership / Repair / Detailing)

- Core business: vehicle sales and/or service.
- Their clients: vehicle owners and buyers.
- How it runs: inventory (dealers), service scheduling, quotes and estimates, parts, financing (dealers), CRM, reviews.
- Data held: customer PII, financing and credit data (dealers, sensitive), payment data.
- Compliance: dealers carry GLBA (financing data), credit/lending rules (Reg Z), FTC auto-advertising rules; PCI; accessibility.
- Typical ask -> real need: "a website" is inventory plus leads (dealers) or services plus booking (repair); "manage service/inventory" is Dashboard or Workflow; financing data demands security.
- Fit and flags: ACCEPT. Flags (dealers): GLBA/credit data, auto-advertising rules, PCI, accessibility.

### Insurance Agency

- Core business: selling and servicing insurance policies.
- Their clients: individuals and businesses.
- How it runs: lead intake, quoting, applications, policy management, claims assistance, renewals, CRM.
- Data held: sensitive PII, health or financial data depending on lines, policy data.
- Compliance: state insurance advertising and licensing rules, GLBA, HIPAA if health or life lines touch health data, data security.
- Typical ask -> real need: "a website" is credibility plus quote/lead intake (Custom Website with secure forms); "manage clients/policies" is CRM or Workflow; "a quote tool" is a custom build.
- Fit and flags: ACCEPT. Flags: state insurance advertising/licensing, GLBA, HIPAA if health lines, accessibility.

### Veterinary

- Core business: medical care for animals.
- Their clients: pet owners.
- How it runs: appointments, animal records, vaccine reminders and recalls, billing, prescriptions, boarding.
- Data held: owner PII and payment data, animal records (not HIPAA, animals), sometimes owner financials.
- Compliance: PCI, accessibility, prescription and controlled-substance handling (light), owner-data privacy. No HIPAA (patients are animals).
- Typical ask -> real need: like dental but without HIPAA: "a website" is info plus booking; "fix the front desk/records" is Dashboard or Workflow + Data Organization; recall reminders are a workflow.
- Fit and flags: ACCEPT. Flags: PCI, accessibility, owner-data privacy (not HIPAA).

### Childcare / Daycare / Preschool

- Core business: care and early education for children.
- Their clients: parents; the children are minors.
- How it runs: enrollment and waitlists, attendance and check-in, tuition billing, parent communication, ratios and licensing compliance, incident reporting.
- Data held: children's data (minors), parent PII and payment, sometimes health/allergy data.
- Compliance: COPPA if children use anything online, state licensing and ratios, staff background-check records, accessibility, PCI, high-sensitivity minor data.
- Typical ask -> real need: "a website" is info plus enrollment or tour requests (Custom Website); "a parent portal" is check-in, billing, communication (Client Portal); "manage enrollment/attendance" is Dashboard or Workflow.
- Fit and flags: ACCEPT. Flags: minors' data (high sensitivity), COPPA, state licensing, PCI, accessibility.

### Property Management

- Core business: managing rental properties on behalf of owners.
- Their clients: property owners and tenants.
- How it runs: listings, tenant screening (credit and background), applications, leases, rent collection, maintenance requests, owner reporting.
- Data held: tenant financial and credit data (sensitive), PII, payment data.
- Compliance: Fair Housing (advertising and screening), FCRA (tenant screening), GLBA-adjacent, PCI, accessibility.
- Typical ask -> real need: "a website" is listings plus applications (Custom Website); "tenant/owner portal" is rent, maintenance, reporting (Client Portal); "manage properties" is Dashboard or Workflow + Data Organization.
- Fit and flags: ACCEPT. Flags: Fair Housing, FCRA (screening), financial/payment data, accessibility.

### SaaS / Startup / Tech

- Core business: software products or services.
- Their clients: other businesses or consumers.
- How it runs: product, marketing site, onboarding, subscription billing, support, analytics.
- Data held: user data (varies widely), payment data.
- Compliance: depends on their users and data, GDPR/CCPA, PCI, SOC 2 expectations, sector rules if they serve regulated industries; accessibility.
- Typical ask -> real need: "a marketing site" is a Custom Website; "rebuild our app/dashboard" is a Business Dashboard or custom build; "an MVP" needs careful scoping (often Enterprise); AI features are AI-Powered Tools.
- Fit and flags: ACCEPT (natural fit). Flags: data privacy (depends on their users), PCI, accessibility; watch scope-creep, MVPs balloon.

### Manufacturing / Industrial / B2B

- Core business: producing and supplying goods to businesses.
- Their clients: business buyers and distributors.
- How it runs: product catalogs and spec sheets, quotes and RFQs, orders, inventory or ERP, distributor portals, long sales cycles.
- Data held: business and order data, pricing, sometimes export-controlled technical data (defense/aerospace).
- Compliance: export controls (ITAR/EAR) for defense or aerospace, accessibility, data security; generally lighter consumer-privacy exposure.
- Typical ask -> real need: "a website" is catalog and credibility plus RFQ (Custom Website); "a distributor portal" is a Client Portal; "manage orders/inventory" is Dashboard, Workflow, or an ERP integration.
- Fit and flags: ACCEPT. Flags: export controls if defense/aerospace, accessibility.

### Construction / Contractors (Commercial)

- Core business: building and renovation projects; general contractors and subcontractors.
- Their clients: developers, businesses, and homeowners on larger projects.
- How it runs: bidding and estimates, project management, scheduling, subcontractor coordination, change orders, permits, progress billing.
- Data held: project and financial data, contracts, PII.
- Compliance: licensing and bonding display, accessibility, payment; OSHA governs the work, not the website.
- Typical ask -> real need: "a website" is a portfolio and credibility site with leads (Custom Website); "manage projects/bids" is Workflow + Business Dashboard; "a project portal" is a Client Portal.
- Fit and flags: ACCEPT. Flags: licensing display, accessibility.

---

## Restricted profiles

### Cannabis / CBD (accept with care)

- Core business: cultivation, dispensary, or CBD product sales.
- Why care: state-by-state legality and a federal gray area, severe payment-processing restrictions, strict advertising rules (ad platforms ban it), mandatory age-gating.
- Operator action: ACCEPT WITH CARE. The build proceeds (Custom Website, or E-commerce with caveats), but flag heavily: age verification, no standard card processing (specialized processors only), advertising restrictions (a Marketing partner marketing referral is constrained, flag that), and state compliance. Confirm their state's legality at the consultation.

### Alcohol / Brewery / Winery / Spirits (accept with care)

- Core business: producing or selling alcohol.
- Why care: age-gating, direct-to-consumer shipping laws that vary by state, advertising rules, the three-tier distribution system.
- Operator action: ACCEPT WITH CARE. Flag: age verification, DTC shipping compliance if they sell online (E-commerce with a shipping-law caveat), advertising rules.

### Gambling / Betting / Gaming (decline by policy)

- Core business: real-money wagering, betting, or gaming as the business itself.
- Why decline: heavy licensing, age and geo restrictions, payment and legal complexity, a jurisdiction minefield.
- Operator action: DECLINE (restricted). Decline politely, not a BuiltByBas fit. Note: a sweepstakes or contest used as a promotion by an otherwise normal business is fine; the decline is for gambling as the core business.

### Firearms / Weapons (decline by policy)

- Core business: sale of firearms, ammunition, or weapons.
- Why decline: advertising and payment-processor restrictions, regulatory complexity, platform bans.
- Operator action: DECLINE (restricted).

### Adult Content (decline by policy)

- Core business: adult or explicit content and services.
- Why decline: payment-processor restrictions, reputational and policy reasons, age-verification complexity.
- Operator action: DECLINE (restricted).

### Crypto / Web3 / Token Projects (case-by-case, Bas decides)

- Core business: exchanges, token projects, NFT platforms, DeFi, wallets.
- Why care: tokens may be securities, money-transmission licensing, a fraud-heavy space, fast-changing regulation.
- Operator action: ROUTE the build with a prominent flag and DEFER the final go/no-go to Bas. Distinguish a normal business that merely accepts crypto payments (fine, flag lightly) from a token, exchange, or DeFi project (high regulatory risk, Bas decides). Name the securities and money-transmission risk in WHY.
