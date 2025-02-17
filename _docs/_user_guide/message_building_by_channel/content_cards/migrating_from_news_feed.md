---
nav_title: Migrating from News Feed
page_order: 10
---

# Migrating From News Feed to Content Cards

Moving from News Feed to Content Cards takes time, but it is an easy adoption! You cannot automatically migrate content from News Feed to Content Cards - you must integrate Content Cards from scratch. However, with the new flexibility of Content Cards, we don't think you'll miss it or mind.

Reach out to your Braze account manager for more details.

## Features and Functionality

Content Cards offers many capabilities that are not supported by Braze's current News Feed such as additional delivery options like action-based, API delivery, and enhanced analytics like conversion tracking.

As you plan your migration from the News Feed to Content Cards, it will be important to note the main differences between Content Cards and the News Feed:

- Content Cards segmentation is evaluated at the time messages are sent, News Feed segmentation is evaluated at the time that News Feed Cards are viewed.
- Content Cards personalization is templated at the time messages are sent, News Feed card personalization is templated at the time that News Feed Cards are viewed.

| Feature | News Feed | Content Cards |
|---|---|---|
| Transactional and 1:1 Messaging | <i class="fas fa-times"></i> | <i class="fas fa-check"></i> |
| Multivariate and Multi-Channel Campaigns | <i class="fas fa-times"></i> | <i class="fas fa-check"></i> |
| Scheduled, Action-Based, and API-Based Delivery | <i class="fas fa-times"></i> | <i class="fas fa-check"></i> |
| API-Created Messages | <i class="fas fa-times"></i> | <i class="fas fa-check"></i> |
| Dismissing and Pinning Cards | <i class="fas fa-times"></i> | <i class="fas fa-check"></i> |
| Rich Analytics | <i class="fas fa-times"></i> | <i class="fas fa-check"></i> |
| Personalization and Segmentation | Templated at Impression | Templated at Send | 

## Implementation

- Content Cards and the News Feed are separate products, so a simple integration for your app or website is necessary in order to use Content Cards.
- If desired, existing News Feed Cards will need to be manually migrated to Content Card Campaigns when you switch.
- Content Cards is not intended to be used at the same time as the News Feed, as it is a replacement for the News Feed.
- Content Cards does not currently support categories - categories can be achieved via customization and key value pairs.
