---
title: "7-Minute Loan Approvals: Pocketly’s Growth with DigiLocker SSO"
url: "https://decentro.tech/blog/pocketly-case-study/"
date: "Mon, 20 Apr 2026 07:02:44 +0000"
author: "Apoorva Kumar"
feed_url: "https://decentro.tech/blog/feed/"
---
<figure class="wp-block-image size-large featured-post-img"><img alt="" class="wp-image-9655" height="1779" src="https://decentro.tech/blog/wp-content/uploads/Pocketly_InternalBanner.jpg" width="1779" /></figure>



<p>India&#8217;s fastest-growing digital lending platform for young borrowers eliminated onboarding drop-offs with Decentro&#8217;s DigiLocker SSO Suite,&nbsp; turning a multi-step compliance process into a seamless, government-verified background check.</p>



<h2>The Credit Opportunity — And Its Onboarding Burden</h2>



<figure class="wp-block-image size-large is-resized"><img alt="Digital Lending Market Opportunity" class="wp-image-9647" height="557" src="https://decentro.tech/blog/wp-content/uploads/Pocketly_Stats.jpg" width="915" /></figure>



<p>India&#8217;s digital lending market has undergone a quiet revolution. Smartphone penetration, UPI infrastructure, and a generation of first-time borrowers have collapsed what was once a branch-banking experience, weeks of paperwork, physical document submission, and manual underwriting, into something that should take minutes on a phone screen.</p>



<p>But speed has a shadow. Every digital loan disbursement sits squarely within the RBI&#8217;s regulatory perimeter. That means mandatory KYC for every borrower, rigorous identity verification against government-issued documents, and an audit trail that lenders and their NBFC partners must maintain at all times. For platforms operating at the scale of millions of users, this compliance burden, if managed manually, becomes a structural drag on the very thing that makes digital lending valuable: speed.</p>



<p><em>&#8220;In consumer lending, the onboarding experience is the product. A borrower who abandons a KYC form mid-journey isn&#8217;t just a lost application; it&#8217;s a broken promise. And at scale, broken promises are existential.&#8221;</em></p>



<h2>About Pocketly</h2>



<figure class="wp-block-image size-large"><img alt="Pocketly website" class="wp-image-9648" height="1102" src="https://decentro.tech/blog/wp-content/uploads/Screenshot-2026-04-20-at-12.09.52 PM.png" width="2864" /></figure>



<p><strong>Credit for Young India</strong></p>



<p>Launched as a challenger to slow, document-heavy personal lending, Pocketly gives India&#8217;s next generation of borrowers access to instant loans of up to ₹25,000 at live-approval speed, with direct bank transfer and zero paperwork. The platform spans salaried employees, self-employed professionals, and first-time credit seekers. It has disbursed over 1.25 crore loans worth more than ₹3,500 crore to a user base that now exceeds 10 million.</p>



<p>Backed by a $3 million funding round and ISO 27001:2023 certified, Pocketly competes on three things: minimum KYC, a 100% digital journey, and sub-7-minute approvals. Its product promise is fundamentally tied to its ability to onboard fast, which means compliance infrastructure that slows the journey is not merely a UX problem. It is a direct threat to disbursement volume.</p>



<h2>The Problem</h2>



<figure class="wp-block-image size-large"><img alt="The problem in the funnel " class="wp-image-9649" height="934" src="https://decentro.tech/blog/wp-content/uploads/Pocketly_Gaps.jpg" width="2133" /></figure>



<p><strong>Two Onboarding Gaps Causing a Leaky Funnel</strong></p>



<p>For a platform that competes on approval speed, friction in the KYC journey shows up immediately in drop-off metrics. Pocketly identified two compounding issues that are degrading both conversion rates and confidence in compliance.</p>



<p><strong>Document Upload Flows: Manual, Friction-Heavy, Incomplete</strong></p>



<p>First-time borrowers attempting to complete KYC through traditional document-upload flows faced too many steps — photograph submissions, OCR extraction, and manual-review queues. The result was high abandonment precisely when borrower intent was highest. Each drop-off represented both a lost loan and a potential compliance gap: an incomplete KYC record that couldn&#8217;t be used downstream.</p>



<p><strong>Identity Verification: No Authoritative Source, High Forgery Risk</strong></p>



<p>Without a direct connection to government-issued, digitally signed document repositories, Pocketly&#8217;s verification layer relied on user-submitted photographs and OCR, methods that are both slower and less reliable than source-fetched verification. Tampered documents and mismatched identities created fraud risk that scaled dangerously with loan volume.</p>



<h2>The Solution</h2>



<p><strong>KYC as a Background Process, Not a Barrier</strong></p>



<p>Pocketly integrated <a href="https://decentro.tech/resources/digilocker-apis" rel="noreferrer noopener" target="_blank">Decentro&#8217;s DigiLocker Suite</a>, including the SSO DigiLocker APIs, to embed government-backed identity verification directly into its mobile onboarding flow, so borrowers never experience compliance as a delay.</p>



<p><strong>SSO DigiLocker Suite</strong></p>



<p><a href="https://docs.decentro.tech/docs/kyc-and-onboarding-identities-digilocker-services" rel="noreferrer noopener" target="_blank">Decentro&#8217;s SSO DigiLocker APIs</a> replaced a multi-step document upload flow with a single, consent-driven session that fetches government-verified identity documents directly from the UIDAI DigiLocker repository, no photographs, no uploads, no OCR errors.</p>



<figure class="wp-block-image size-large"><img alt="" class="wp-image-9651" height="688" src="https://decentro.tech/blog/wp-content/uploads/Screenshot-2026-04-20-at-12.18.18 PM-1.png" width="2348" /></figure>



<figure class="wp-block-image size-large is-resized"><img alt="" class="wp-image-9652" height="164" src="https://decentro.tech/blog/wp-content/uploads/Screenshot-2026-04-20-at-12.18.03 PM.png" width="915" /></figure>



<p>How it works:</p>



<ul><li>Borrower signs up on Pocketly with their mobile number</li><li>Decentro checks for an existing DigiLocker account, routing returning users to a <strong>pinless sign-in</strong> screen, and new users to a frictionless sign-up flow</li><li>An SSO DigiLocker session is initiated; the borrower authenticates within the Pocketly app without being redirected away</li><li>The platform fetches the borrower&#8217;s list of issued documents and retrieves their government-signed identity and address proof in a single step</li><li>Explicit, purpose-bound consent is captured for every document fetch, satisfying RBI and DPDP requirements automatically</li><li>Loan application proceeds. Funds are disbursed. Total time: under 7 minutes from sign-up</li></ul>



<h2>Business Stakes</h2>



<p><strong>Why Real-Time KYC Is Non-Negotiable for Digital Lending</strong></p>



<p>Unlike a salaried bank loan, where days of processing are the norm and the borrower expects to wait, Pocketly&#8217;s customers are often in the middle of a financial need. A medical expense. A rent shortfall. An opportunity that won&#8217;t wait. A <a href="https://decentro.tech/products/kyc-onboarding" rel="noreferrer noopener" target="_blank">KYC flow</a> that stalls mid-journey isn&#8217;t a UX inconvenience; it&#8217;s a broken product promise. Decentro&#8217;s integration addressed three specific commercial and regulatory risks simultaneously.</p>



<p><strong>Onboarding Abandonment.</strong> Borrowers failing to complete KYC in a single session is a direct conversion loss that compounds with every additional step in the verification flow.</p>



<p><strong>Regulatory Non-Compliance.</strong> Incomplete or manually verified KYC records create audit exposure for Pocketly and its NBFC lending partners, a risk that scales with loan volume and becomes increasingly costly as the book grows.</p>



<p><strong>Document Fraud.</strong> Identity documents submitted via photograph or OCR carry forgery risk. Without source-fetched, digitally signed government documents, fraud scales with application volume and is difficult to detect in real time.</p>



<h2>Results &amp; Impact</h2>



<p>Post-integration, Pocketly&#8217;s onboarding pipeline transformed from a document-upload bottleneck into a frictionless, fully automated compliance engine — without requiring borrowers to submit a single photograph or wait for manual review.</p>



<figure class="wp-block-table"><table><tbody><tr><td></td><td><strong>Before Decentro</strong></td><td><strong>After Decentro</strong></td></tr><tr><td><strong>KYC Method</strong></td><td>Manual document uploads; OCR-based extraction</td><td>Government-issued, digitally signed via DigiLocker</td></tr><tr><td><strong>Verification Speed</strong></td><td>Multi-step; high abandonment mid-flow</td><td>Real-time, single-session completion</td></tr><tr><td><strong>Identity Source</strong></td><td>User-submitted photographs</td><td>UIDAI-issued e-Aadhaar via DigiLocker</td></tr><tr><td><strong>Fraud Risk</strong></td><td>OCR errors; tampered document exposure</td><td>Eliminated; source-fetched, tamper-proof</td></tr><tr><td><strong>Compliance Trail</strong></td><td>Manual; audit gaps</td><td>Automated, consent-logged, audit-ready</td></tr><tr><td><strong>Time to Disbursement</strong></td><td>Delayed by verification backlog</td><td>Sub-7-minute approval enabled</td></tr></tbody></table></figure>



<figure class="wp-block-image size-large"><img alt="impact of Decentro's intergration with Pocketly" class="wp-image-9654" height="1227" src="https://decentro.tech/blog/wp-content/uploads/Pocketly_Decentro_x_Pocketly.jpg" width="2500" /></figure>



<p>Beyond the table, the integration delivered measurable operational impact:</p>



<ul><li><strong>3X </strong>increase in KYC completion within a single borrower session</li><li><strong>60% </strong>reduction in onboarding abandonment directly attributed to verification friction</li><li><strong>40%</strong> growth in first-loan disbursements within 30 days of go-live</li></ul>



<h2>Voice of the Customer</h2>



<figure class="wp-block-image size-large"><img alt="Pocketly Testimonial" class="wp-image-9653" height="1426" src="https://decentro.tech/blog/wp-content/uploads/Pocketly_Testimonial.jpg" width="2500" /></figure>



<p><em>&#8220;At Pocketly, our promise to borrowers is simple: fast credit, zero hassle. Decentro&#8217;s DigiLocker SSO integration has been instrumental in delivering on that promise at scale. By replacing manual document uploads with a government-backed verification experience, we&#8217;ve been able to serve more borrowers faster while staying fully compliant. The pinless sign-in experience has been a meaningful unlock for our repeat user base — reducing drop-offs at what was previously a friction-heavy step. Decentro&#8217;s infrastructure handles the complexity so our team stays focused on what matters: building great products for Young India.&#8221;</em></p>



<p>— <strong>Keshav Nagpal, Software Engineer, Pocketly</strong></p>



<h2>In Closing</h2>



<p><strong>KYC Infrastructure Is a Growth Lever, Not Just a Cost Centre</strong></p>



<p>For Pocketly, automated identity verification isn&#8217;t optional. It is the product. By integrating Decentro&#8217;s DigiLocker SSO Suite, Pocketly converted its compliance layer from a friction point into a competitive advantage: borrowers onboard faster, approvals happen within the same session, and a consent-logged, audit-ready verification trail backs every loan disbursed.</p>



<p>This mirrors results Decentro has delivered across the fintech ecosystem — 200% growth in DigiLocker adoption at <a href="https://decentro.tech/blog/olyv-case-study/" rel="noreferrer noopener" target="_blank">Olyv,</a> and measurable onboarding improvements across partners, including <a href="https://decentro.tech/blog/salaryse-case-study/" rel="noreferrer noopener" target="_blank">SalarySe</a>, and others, reinforcing that smart, API-first KYC at the point of onboarding is among the highest-ROI infrastructure investments a digital lending platform can make.</p>



<p>Decentro&#8217;s verification infrastructure processes hundreds of thousands of validations daily, serving partners across lending, remittances, neo-banking, and investment platforms. The architecture scales with loan volume and adapts to evolving regulatory requirements,&nbsp; so compliance never becomes a ceiling on growth.</p>



<p><strong>Ready to streamline your onboarding?</strong><a href="https://decentro.tech/signup">&nbsp;</a></p>



<p><a class="decentro-homepage-signup" href="https://decentro.tech/signup?" rel="noreferrer noopener" target="_blank">Let&#8217;s Connect</a></p>
<p>The post <a href="https://decentro.tech/blog/pocketly-case-study/" rel="nofollow">7-Minute Loan Approvals: Pocketly’s Growth with DigiLocker SSO</a> appeared first on <a href="https://decentro.tech/blog" rel="nofollow">Decentro</a>.</p>
