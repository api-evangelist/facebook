# Facebook (facebook)
Facebook is Meta's social networking platform providing APIs for developers to integrate with Facebook's ecosystem. The Facebook Graph API is the primary way to read and write data to the Facebook social graph. Meta also provides APIs for marketing and advertising, Instagram content management, Messenger bots, Threads publishing, and WhatsApp business messaging.

**URL:** [Visit APIs.json URL](https://developers.facebook.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Advertising, Content Publishing, Messaging, Social Media, Social Networking

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-18

## APIs

### Facebook Graph API
The primary way to read and write data to the Facebook social graph, providing access to user profiles, posts, pages, photos, videos, comments, and social interactions. Supports nodes, edges, and fields for flexible data access.

**Human URL:** [https://developers.facebook.com/docs/graph-api](https://developers.facebook.com/docs/graph-api)

#### Tags:

 - Comments, Graph, Pages, Photos, Posts, Social, Users, Videos

#### Properties

- [Documentation](https://developers.facebook.com/docs/graph-api/overview)
- [APIReference](https://developers.facebook.com/docs/graph-api/reference)
- [Authentication](https://developers.facebook.com/docs/facebook-login/access-tokens)
- [OpenAPI](openapi/facebook-graph-api.yaml)

### Facebook Marketing API
Programmatically manage Facebook ad campaigns, ad sets, ad creatives, Custom Audiences, and advertising reports. Access performance insights and automate campaign optimization at scale.

**Human URL:** [https://developers.facebook.com/docs/marketing-apis](https://developers.facebook.com/docs/marketing-apis)

#### Tags:

 - Ad Campaigns, Advertising, Audiences, Insights, Marketing

#### Properties

- [Documentation](https://developers.facebook.com/docs/marketing-api)
- [APIReference](https://developers.facebook.com/docs/marketing-api/reference)
- [OpenAPI](openapi/facebook-marketing-api.yaml)

### Instagram API
Manage Instagram Business and Creator account content including publishing media, retrieving posts, managing comments, discovering mentions, and accessing account insights for analytics.

**Human URL:** [https://developers.facebook.com/docs/instagram-platform](https://developers.facebook.com/docs/instagram-platform)

#### Tags:

 - Content Management, Instagram, Media, Social Media

#### Properties

- [Documentation](https://developers.facebook.com/docs/instagram-platform)
- [OpenAPI](openapi/facebook-instagram-api.yaml)

### Messenger Platform API
Build messaging experiences on Facebook Messenger and Instagram Direct. Send and receive messages, create bot interactions, use templates and webviews, manage conversation routing, and integrate NLP capabilities.

**Human URL:** [https://developers.facebook.com/docs/messenger-platform](https://developers.facebook.com/docs/messenger-platform)

#### Tags:

 - Bots, Chat, Messaging, Messenger

#### Properties

- [Documentation](https://developers.facebook.com/docs/messenger-platform)
- [OpenAPI](openapi/facebook-messenger-api.yaml)

### Threads API
Publish and manage content on Threads, Meta's text-based social platform. Create posts and carousels, retrieve and moderate replies, access insights, and manage creator profiles at scale.

**Human URL:** [https://developers.facebook.com/docs/threads](https://developers.facebook.com/docs/threads)

#### Tags:

 - Content Publishing, Social Media, Threads

#### Properties

- [Documentation](https://developers.facebook.com/docs/threads)
- [OpenAPI](openapi/facebook-threads-api.yaml)

### WhatsApp Business API
Send and receive messages through WhatsApp Business Platform. Support text, media, templates, interactive messages, and manage business profiles for customer communication at scale.

**Human URL:** [https://developers.facebook.com/docs/whatsapp](https://developers.facebook.com/docs/whatsapp)

#### Tags:

 - Business Messaging, Customer Communication, WhatsApp

#### Properties

- [Documentation](https://developers.facebook.com/docs/whatsapp)
- [OpenAPI](openapi/facebook-whatsapp-api.yaml)

## Common Properties

- [Portal](https://developers.facebook.com)
- [GettingStarted](https://developers.facebook.com/docs/development/create-an-app)
- [ChangeLog](https://developers.facebook.com/docs/graph-api/changelog)
- [StatusPage](https://developers.facebook.com/status)
- [TermsOfService](https://developers.facebook.com/terms)
- [PrivacyPolicy](https://developers.facebook.com/policy)
- [RateLimits](https://developers.facebook.com/docs/graph-api/overview/rate-limiting)
- [GitHubOrganization](https://github.com/facebook)
- [Blog](https://developers.facebook.com/blog)
- [Support](https://developers.facebook.com/support)
- [FAQ](https://developers.facebook.com/docs/development/faq)
- [Errors](https://developers.facebook.com/docs/graph-api/guides/error-handling)

## Features

| Name | Description |
|------|-------------|
| Graph API | HTTP-based API for reading and writing to the Facebook social graph with nodes, edges, and fields. |
| Webhooks | Real-time notifications when changes occur to data your app has access to. |
| Batch Requests | Send multiple API calls in a single HTTP request for improved performance. |
| Access Tokens | OAuth 2.0 access tokens for user, page, app, and client authentication flows. |
| Facebook Login | Authentication system allowing users to log into apps with their Facebook credentials. |
| Meta Pixel | Analytics tool for measuring ad effectiveness and tracking website visitor actions. |
| Conversions API | Server-side event tracking for ad measurement without browser dependencies. |

## Use Cases

| Name | Description |
|------|-------------|
| Social Media Management | Manage pages, publish content, and engage with audiences across Facebook and Instagram. |
| Advertising Automation | Automate ad campaign creation, optimization, and reporting at scale. |
| Customer Messaging | Build conversational experiences on Messenger and WhatsApp for customer support and engagement. |
| Content Publishing | Publish and schedule content across Facebook, Instagram, and Threads platforms. |
| Analytics and Insights | Access performance data and audience insights across Meta platforms. |
| E-Commerce Integration | Integrate product catalogs and shopping experiences with Facebook and Instagram shops. |

## Integrations

| Name | Description |
|------|-------------|
| Shopify | Connect Shopify stores with Facebook and Instagram shops for social commerce. |
| WordPress | Facebook social plugins and login integration for WordPress sites. |
| Salesforce | Sync Facebook lead ads and audiences with Salesforce CRM. |
| HubSpot | Connect Facebook advertising and messaging with HubSpot marketing automation. |
| Zapier | Automate workflows between Facebook and thousands of other apps. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Facebook Graph API](openapi/facebook-graph-api.yaml)
- [Facebook Marketing API](openapi/facebook-marketing-api.yaml)
- [Facebook Instagram API](openapi/facebook-instagram-api.yaml)
- [Facebook Messenger API](openapi/facebook-messenger-api.yaml)
- [Facebook Threads API](openapi/facebook-threads-api.yaml)
- [Facebook WhatsApp API](openapi/facebook-whatsapp-api.yaml)

### JSON Schema

- [User](json-schema/graph-api-user-schema.json)
- [Post](json-schema/graph-api-post-schema.json)
- [Page](json-schema/graph-api-page-schema.json)
- [Campaign](json-schema/marketing-api-campaign-schema.json)
- [Insight](json-schema/marketing-api-insight-schema.json)
- [InstagramUser](json-schema/instagram-api-instagram-user-schema.json)
- [InstagramMedia](json-schema/instagram-api-instagram-media-schema.json)
- [WhatsAppPhoneNumber](json-schema/whatsapp-api-whatsapp-phone-number-schema.json)
- [ThreadsMedia](json-schema/threads-api-threads-media-schema.json)

### JSON Structure

- [User](json-structure/graph-api-user-structure.json)
- [Post](json-structure/graph-api-post-structure.json)
- [Campaign](json-structure/marketing-api-campaign-structure.json)
- [InstagramMedia](json-structure/instagram-api-instagram-media-structure.json)
- [ThreadsMedia](json-structure/threads-api-threads-media-structure.json)

### JSON-LD

- [Graph API Context](json-ld/facebook-graph-api-context.jsonld)
- [Marketing API Context](json-ld/facebook-marketing-api-context.jsonld)
- [Instagram API Context](json-ld/facebook-instagram-api-context.jsonld)

### Examples

- [User](examples/graph-api-user-example.json)
- [Post](examples/graph-api-post-example.json)
- [Campaign](examples/marketing-api-campaign-example.json)
- [InstagramMedia](examples/instagram-api-instagram-media-example.json)
- [ThreadsMedia](examples/threads-api-threads-media-example.json)
- [WhatsAppPhoneNumber](examples/whatsapp-api-whatsapp-phone-number-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Graph API](capabilities/shared/graph-api.yaml) -- 8 operations for social graph access
- [Marketing API](capabilities/shared/marketing-api.yaml) -- 5 operations for campaign management
- [Instagram API](capabilities/shared/instagram-api.yaml) -- 4 operations for content management
- [Messenger API](capabilities/shared/messenger-api.yaml) -- 2 operations for messaging
- [WhatsApp API](capabilities/shared/whatsapp-api.yaml) -- 3 operations for business messaging
- [Threads API](capabilities/shared/threads-api.yaml) -- 4 operations for content publishing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Social Media Management](capabilities/social-media-management.yaml) | Graph API + Instagram API + Threads API | 7 | Social Media Manager |
| [Advertising and Marketing](capabilities/advertising-and-marketing.yaml) | Marketing API + Graph API + Instagram API | 5 | Marketing Manager |
| [Messaging and Communication](capabilities/messaging-and-communication.yaml) | Messenger API + WhatsApp API | 5 | Customer Support |

## Vocabulary

- [Facebook Vocabulary](vocabulary/facebook-vocabulary.yaml) -- Unified taxonomy mapping 19 resources, 6 actions, 3 workflows, and 5 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Facebook Spectral Rules](rules/facebook-spectral-rules.yml) -- 28 rules across 10 categories enforcing Facebook API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
