# API Endpoints

## Accounts

GET    /accounts/:token/featured_listings(.:format)
GET    /accounts/closest(.:format)
GET    /accounts/membersites(.:format)
GET    /accounts/:account_id/profile(.:format)
GET    /accounts(.:format)
GET    /accounts/:id(.:format)

## Blog Posts

GET    /blog_posts(/:year(/:month(/:day)))(.:format)
GET    /blog_posts/:year/:month/:day/:permalink(.:format)
GET    /blog_posts/:id/summary(.:format)
GET    /blog_posts/recent(.:format)
GET    /blog_posts/lre(.:format)
GET    /blog_posts/metadata/tags(.:format)
POST   /blog_posts/:blog_post_id/blog_comments(.:format)
GET    /blog_posts/:id(.:format)

## Communities

GET    /communities/:id/listings/unshowcased(.:format)
GET    /communities(.:format)
GET    /communities/:id(.:format)

## Currencies

GET    /currencies(.:format)

## Destinations

GET    /destinations/:destination_id/listings/featured(.:format)
GET    /destinations/:destination_id/profiles/featured(.:format)
GET    /destinations(.:format)
GET    /destinations/:id(.:format)

## Events

GET    /events(.:format)

## Features

GET    /features/listings(.:format)
GET    /features/homepage_large(.:format)
GET    /features/homepage_small(.:format)
GET    /features/community_gateway(.:format)
GET    /features/destinations_gateway(.:format)
GET    /features/homepage_professionals(.:format)
GET    /features(.:format)

## Galleries

GET    /galleries/:id(.:format)

## Leads

PUT    /leads/:id/mark_read(.:format)
POST   /leads(.:format)
GET    /leads/:id(.:format)

## Legal Pages

GET    /legal_pages(.:format)

## Listings

GET    /listings/:listing_id/images(.:format)
GET    /listings/recently_shared(.:format)
GET    /listings/most_shared(.:format)
GET    /listings/most_viewed(.:format)
GET    /listings/geocodes(.:format)
GET    /listings/tweetable(.:format)
GET    /listings/metadata(/:action)(.:format)
GET    /listings(.:format)
GET    /listings/:id(.:format)

## Listing Images

GET    /listing_images/:id(.:format)
GET    /listing_images/:id/:image_size(.:format)

## Imports

GET    /imports/listhub/listings(.:format)
POST   /imports/listhub/listings(.:format)
PATCH  /imports/listhub/listings/:id(.:format)
PUT    /imports/listhub/listings/:id(.:format)
DELETE /imports/listhub/listings/:id(.:format)
GET    /imports/:import_id/listings(.:format)
POST   /imports/:import_id/listings(.:format)
GET    /imports/:import_id/listings/new(.:format)
GET    /imports/:import_id/listings/:id/edit(.:format)
GET    /imports/:import_id/listings/:id(.:format)
PATCH  /imports/:import_id/listings/:id(.:format)
PUT    /imports/:import_id/listings/:id(.:format)
DELETE /imports/:import_id/listings/:id(.:format)
GET    /imports/:import_id/mls_keys(.:format)
GET    /imports/:import_id/subscriptions(.:format)
GET    /imports/tsv(.:format)
GET    /imports/xml(.:format)

## Magazine

GET    /magazine(.:format)

## Press Releases

GET    /press_releases(.:format)
GET    /press_releases/:id(.:format)

## Products

GET    /products/:id(.:format)

## Profiles

GET    /profiles/:profile_id/unfeatured_agents(.:format)
GET    /profiles/agents(.:format)
GET    /profiles/default_contacts(.:format)
GET    /profiles/default_contacts_and_offices(.:format)
GET    /profiles/offices(.:format)
GET    /profiles/lounge_people(.:format)
GET    /profiles/metadata/:action(.:format)
GET    /profiles/:profile_id/listings/unfeatured(.:format)
POST   /profiles/:profile_id/testimonials(.:format)
POST   /profiles/:profile_id/mailchimp_subscription(.:format)
GET    /profiles/:profile_id/mailchimp_subscription(.:format)
PATCH  /profiles/:profile_id/mailchimp_subscription(.:format)
PUT    /profiles/:profile_id/mailchimp_subscription(.:format)
DELETE /profiles/:profile_id/mailchimp_subscription(.:format)
GET    /profiles(.:format)
GET    /profiles/:id(.:format)

## Mailchimp Subscriptions

GET    /mailchimp_subscriptions/metadata/interest_categories(.:format)

## Profile Languages

GET    /profile_languages(.:format)

## Sessions

POST   /sessions(.:format)
GET    /sessions/:session_token(.:format)
DELETE /sessions/:session_token(.:format)

## Passwords

POST   /passwords(.:format)
GET    /passwords/:pw_reset_token(.:format)

## Saved Searches

GET    /saved/searches/ready_to_email(.:format)
GET    /saved/searches/:id(.:format)

## Users

GET    /users/:user_id/blog_comments(.:format)
GET    /users/:user_id/blog_posts(.:format)
GET    /users/:user_id/communities(.:format)
GET    /users/:user_id/listings(.:format)
GET    /users/:user_id/press_releases(.:format)
GET    /users/:user_id/imports(/:type)(.:format)
GET    /users/:user_id/saved/listings(.:format)
POST   /users/:user_id/saved/listings(.:format)
PATCH  /users/:user_id/saved/listings/:id(.:format)
PUT    /users/:user_id/saved/listings/:id(.:format)
DELETE /users/:user_id/saved/listings/:id(.:format)
GET    /users/:user_id/saved/searches(.:format)
POST   /users/:user_id/saved/searches(.:format)
PATCH  /users/:user_id/saved/searches/:id(.:format)
PUT    /users/:user_id/saved/searches/:id(.:format)
DELETE /users/:user_id/saved/searches/:id(.:format)
GET    /users/:user_id/saved/profiles(.:format)
POST   /users/:user_id/saved/profiles(.:format)
PATCH  /users/:user_id/saved/profiles/:id(.:format)
PUT    /users/:user_id/saved/profiles/:id(.:format)
DELETE /users/:user_id/saved/profiles/:id(.:format)
GET    /users/:user_id/saved/communities(.:format)
POST   /users/:user_id/saved/communities(.:format)
PATCH  /users/:user_id/saved/communities/:id(.:format)
PUT    /users/:user_id/saved/communities/:id(.:format)
DELETE /users/:user_id/saved/communities/:id(.:format)
POST   /users(.:format)
GET    /users/:id(.:format)
PATCH  /users/:id(.:format)
PUT    /users/:id(.:format)

## Sitemap

GET    /sitemap(.:format)

## Member Reports

GET    /member_reports(.:format)
POST   /member_reports(.:format)

## Reports

GET    /reports/agents(.:format)
GET    /reports/clickthroughs(.:format)
GET    /reports/inquiries(.:format)
GET    /reports/leads(.:format)
GET    /reports/listing(.:format)
GET    /reports/listings(.:format)
GET    /reports/owner(.:format)
GET    /reports/profile(.:format)
GET    /reports/users(.:format)
GET    /reports/inquiries(.:format)
GET    /reports(.:format)
POST   /reports(.:format)
GET    /reports/new(.:format)
GET    /reports/:id/edit(.:format)
GET    /reports/:id(.:format)
PATCH  /reports/:id(.:format)
PUT    /reports/:id(.:format)
DELETE /reports/:id(.:format)

## RETS Feeds

PATCH  /rets_feeds/:id(.:format)
PUT    /rets_feeds/:id(.:format)

## Outbound Link Hits

POST   /outbound_link_hits(.:format)

## LuxRE URLs

GET    /luxre_urls/:id(.:format)

## Week in Review

GET    /week_in_review(.:format)
GET    /week_in_review/week_of/:week_of(.:format)
GET    /week_in_reviews/newest(.:format)
PUT    /week_in_reviews/:week_in_review_id/mailchimp_campaign/schedule(.:format)
GET    /week_in_reviews/:week_in_review_id/mailchimp_campaign/lists(.:format)
POST   /week_in_reviews/:week_in_review_id/mailchimp_campaign(.:format)
GET    /week_in_reviews/:week_in_review_id/mailchimp_campaign(.:format)
PATCH  /week_in_reviews/:week_in_review_id/mailchimp_campaign(.:format)
PUT    /week_in_reviews/:week_in_review_id/mailchimp_campaign(.:format)
DELETE /week_in_reviews/:week_in_review_id/mailchimp_campaign(.:format)
GET    /week_in_reviews(.:format)
GET    /week_in_reviews/:id(.:format)

## Forms

POST   /forms/:form_id/entries(.:format)
GET    /forms(.:format)
GET    /forms/:id(.:format)

## Controller Actions

POST   /:controller/:id/forward(.:format)
PUT    /:controller/:id/hit(.:format)
GET    /:controller/metadata/archive(.:format)

## Admin

GET    /admin/destinations/:id(.:format)
GET    /admin/profiles(.:format)
GET    /admin/profiles/:id(.:format)
GET    /admin/users(.:format)
