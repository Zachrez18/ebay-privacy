Privacy Policy
AI eBay Listing Assistant · Last updated November 25, 2026

This private, single-owner application is operated for Turnpike Appliance / Total Appliance Service. It helps its owner prepare listings from their own photos and notes, and send reviewed drafts to eBay. Final publication takes place inside eBay Seller Hub.

Information stored by this application
We store the owner’s platform identity to protect their workspace; owner-uploaded photos, condition notes, measurements, draft text, preferences and submission history; and encrypted eBay OAuth access and refresh tokens after the owner connects eBay. App credentials are held in server-side hosting secrets, never in the client bundle. Local browser storage holds unsaved draft recovery data.

eBay data and permissions
The application does not import or persist existing eBay listings, orders, buyer information, customer addresses or messages. It stores the owner’s original draft content and minimal operational metadata needed to prevent duplicate submissions: task identifiers, processing outcomes, timestamps and image-upload references for the owner’s photos. eBay result files are inspected in memory, then discarded; their rows and listing/customer content are not saved. Category and required-item-specific metadata may be cached for 24 hours.

Connecting eBay uses OAuth 2.0. The application does not receive or store your eBay password. Tokens are encrypted with AES-GCM in the backend database and refreshed when needed. We request base API and inventory permissions for the existing draft feed and photo workflow. These permissions are broader than a draft-only permission; application code restricts submissions to drafts and provides no automatic publication.

When information is shared
Photos and draft details are sent to eBay only when the owner chooses to send a draft. If the owner explicitly requests AI analysis and has configured an AI key, selected analysis photos and notes are sent to the OpenAI API with response storage disabled. OpenAI may retain API data under its applicable service and abuse-monitoring policies. Voice dictation, when used, is processed by the browser’s speech service under its provider’s policies.

OpenAI Sites and its underlying Cloudflare infrastructure host the application, database and private photo storage. Hosting providers may process technical request logs under their own policies. The application adds no advertising trackers and does not sell personal information. External eBay research links open eBay, where eBay’s policies apply.

Retention and deletion
Owner-provided drafts and photos remain until the owner deletes them. Deleting a local draft removes its attached private photos and local submission history; it does not delete an eBay draft. Browser recovery data is cleared after a successful save or local deletion. Disconnect eBay in Settings to remove stored OAuth tokens; revoke the application in eBay Account permissions to remove the authorization at eBay. Submission metadata remains with the local draft for duplicate prevention. Authorization state expires after ten minutes; expired records are removed at the next connection attempt. Provider backups and technical logs follow the hosting provider’s retention practices; immediate deletion from those systems is not promised.

Access and security
The privacy policy, authorization failure page and state-validated eBay OAuth callback are publicly accessible. The dashboard and listing tools require ChatGPT sign-in and a server-side check against the configured owner email. Backend operations check verified identity, owner authorization and record ownership; write requests check their origin. Credentials and tokens are not included in draft backups or returned to browser code. No system can guarantee absolute security.

Contact
For access, correction, deletion or privacy questions, contact zach@totalapplianceservice.com.

Return to listing assistant
