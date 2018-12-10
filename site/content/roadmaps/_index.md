---
title : "Roadmap"
description : "FHIR Hunt - Plan and Roadmap"
weight : 3
---

## Phase 1

#### The following roadmap has estimates for dates and duration for the FHIR Hunt Project - Phase 1

{{<mermaid>}}

gantt
    dateFormat  YYYY-MM-DD
    
    section Launch FHIR Hunt Site 
      Setup a docker container of WordPress in Netspective DO Docker engine mounted on www.fhirhunt.com                 :done, docker, 2018-10-23, 8h
      Purchase and setup Plugin Hunt Theme using a new alias epicthemes-admin@netspective.org                           :done, theme, 2018-10-23, 2018-10-24
      Install wpGraphQL for API access                                                                                  :done, wpgraphql, 2018-10-24, 2018-10-25
      Create minor theming to with Netspective Media logos, etc.                                                        :done, customize, 2018-10-25, 2018-10-31
      Add a new FHIR Hunt logo with caption for branding                                                                :done, brand, 2018-10-25, 4h
      Add head shot of Shahid to masthead and say “Curated and published by @ShahidNShah”                               :done, shahid, 2018-10-26, 1d
      Create and add Google Analytics code                                                                              :done, analytics, 2018-10-29, 4h
      Remove logout message as it’s clear you’re logged out since there’s a Login button                                :done, logout, 2018-10-29, 1d
      Customize the product page to look similar to ProductHunt website                                                 :done, product-page, 2018-10-30, 2018-10-31
      Create a simple catalog (base data) at www.fhir.org by search for products that use FHIR for interoperability     :done, catalog, 2018-10-30, 2018-11-02
      Fix the issues in front end form submission                                                                       :done, submit, 2018-11-02, 2018-11-03
      QA the site in mobile and desktop and fix issues identified                                                       :done, qa-launch, 2018-11-05, 2018-11-09

    section FHIR Interoperable Product Curation
      Discuss with Radhika, create an account for her to start adding FHIR Products                                     :done, radhika, 2018-10-29, 2018-10-30
      Add the content that Radhika provided for 'About Us' page                                                         :done, about-us, 2018-11-01, 2018-11-02
      Add the categories and sub categories provided by Radhika                                                         :done, categories, 2018-11-01, 2018-11-02
      Add as many URLs you can find from the HL7 2018 apps roundtable Presentation Schedule                             :done, roundtable, 2018-11-05, 2018-11-16
      Create ahrefs alerts for all our categories and terms in FHIR Hunt                                                :ahrefs, 2018-11-19, 2018-11-23

    section Announcements and Promotions
      Create fhirhunt-twitter-admins@netspective.org as an alias tied to our main Netspective Media twitter admin user group  :done, twitter-admin-email, 2018-10-29, 2018-10-30
      Create a new @FHIRHunt twitter account                                                                            :done, twitter-account, 2018-10-29, 2018-10-30
      Tie that @FHIRHunt to our www.FHIRHunt.com website                                                                :done, tie-twitter-handle, 2018-10-30, 2018-10-31
      Add it to Buffer.com                                                                                              :done, buffer, 2018-10-30, 2018-10-31
      Start tweeting automatically anything added to www.FHIRHunt.com to @FHIRHunt                                      :done, tweet-submissions, 2018-11-21, 2018-11-23

    
{{</mermaid>}}

---

## Phase 2

#### The following roadmap has estimates for dates and duration for the FHIR Hunt Project - Phase 2

{{<mermaid>}}

gantt
    dateFormat  YYYY-MM-DD
    
    section Extending the platform
      Install social login plugin that will allow GITHub, LinkedIn, Twitter and Facebook                                :done, social-login, 2018-10-29, 2018-11-02
      Add custom fields to capture additional info like, licensing, tags, product website, GIT repository, watch, star, fork, etc. :done, custom-fields, 2018-11-05, 2018-11-07
      Add tool tips for the less obvious icons/data like upvote, GIT scores, etc. shown on the product listing          :done, tool-tips, 2018-11-05, 2018-11-07
      Identify and install a good plugin to make use of advanced custom field and taxonomy capability                   :done, taxonomy-plugin, 2018-11-06, 2018-11-07
      Add the additional fields on front-end submission modal/window popup                                              :active, submit-popup, 2018-11-07, 2018-11-31
      Add new menu items at the top to filter “Trending, Popular, Random” lists for FHIR Hunt                           :done, new-menu, 2018-11-13, 2018-11-22
      Add “Watch” or “Subscribe” feature – similar to same feature in GitHub … being notified in case record changes    :watch, 2018-11-23, 2018-11-27
      Ability to invite Vendors to claim their products and fill in the missing product details                         :vendor-claim, 2018-11-19, 2018-11-28
      Capability for users to assert licence of products (topic based feedback linked to product reviewed)              :user-assert, 2018-11-22, 2018-11-30
      QA the site in mobile and desktop and fix issues identified                                                       :qa-extend, 2018-11-19, 2018-11-30

    section FHIRHunt SEO Onpage Optimization
      Keyword Research                                                                                                  :done, keyword, 2018-11-16, 2018-11-19
      Meta Tag Creation & Implementation                                                                                :done, meta-tag, 2018-11-19, 1d
      Interlinking                                                                                                      :done, interlinking, 2018-11-19, 1d
      Image Alt Optimization                                                                                            :done, image-alt, 2018-11-19, 2018-11-19
      URL Optimization                                                                                                  :done, url-optimize, 2018-11-19, 2018-11-19
      Add Robots.txt                                                                                                    :done, robots, 2018-11-20, 1d
      Add Sitemap.xml                                                                                                   :done, sitemap, 2018-11-19, 1d

    section Telemetry Tools Integration and Monitoring
      Google Webmasters Integration                                                                                     :done, webmaster, 2018-11-20, 1d
      Make sure SEO scoring is getting integrated, that Google Analytics is turned on, etc.                             :done, seo-scoring, 2018-11-19, 2018-11-20
      Setup Grafana and Prometheus monitoring for anything that Google Analytics cannot report                          :done, grafana-prometheus, 2018-11-19, 2018-11-22
      Query Prometheus to get the list of products trending over a given period of time and tie to the Trending menu    :active, trending, 2018-11-22, 2018-11-30
      Monitor Website on a daily, weekly and monthly basis                                                              :monitor-website, 2018-11-26, 2018-12-31


    section On Going Tasks
      Curate more products that use FHIR for interoperability to the product catalogue                                  :active, catalog, 2018-10-29, 2018-12-31
      Add unique featured image for each of the FHIR product that is submitted daily to the site                        :active, featured-image, 2018-10-30, 2018-12-31

    
{{</mermaid>}}

---

## Phase 3

#### The following roadmap has estimates for dates and duration for the FHIR Hunt Project - Phase 3

{{<mermaid>}}

gantt
    dateFormat  YYYY-MM-DD

    section Extending the platform
      If there’s a FHIR Hunt Git or BitBucket repo, include the license scan on the detail page                         :license-scan, 2018-12-03, 2018-12-31
      Add ‘Ask FHIR Hunt’ for product recommendations and advice where community members can view questions and replies  :ask, 2018-12-03, 2018-12-31
      Add Topics, Live chats, Blog, News letter, Time travel, Apps, Branding, etc.                                      :chat, 2018-12-03, 2018-12-31
      Add FAQ, Terms of use, Privacy policy                                                                             :faq, 2018-12-03, 2018-12-31
      Ship feature - A toolkit for makers to ship awesome products                                                      :ship, 2018-12-03, 2018-12-31
      Makers feature - share, connect, reach user’s goals. Allow users to connect with their peers on FHIR Hunt.        :makers, 2018-12-03, 2018-12-31
      Events feature - Find and join the best tech events around the world with the FHIR Hunt community                 :events, 2018-12-03, 2018-12-31
      Upcoming feature - Popular upcoming products                                                                      :upcoming, 2018-12-03, 2018-12-31
      Collection feature - It gives the cross section of all the posts in an organized way. Here users can follow and/or view the individual posts in each collection :collection, 2018-12-03, 2018-12-31
      Add a “Digital Health Interop Opportunities” section similar to “Opps Daily” newsletter                           :opportunities, 2018-12-03, 2018-12-31
      Allow people to submit suggestions for new products, services, etc. privately                                     :suggestions, 2018-12-03, 2018-12-31
      Ability to review, curate, or pass to our vendors these submitted suggestions                                     :review-suggestions, 2018-12-03, 2018-12-31
      Track the IPG URL for a product/solution in case there is one (or more than one)                                  :track-IPG-URL, 2018-12-03, 2018-12-31
      For each product, we can tie it to projects where it’s in use or something similar                                :tie2projects, 2018-12-03, 2018-12-31
      See what data IPG is tracking and how we can track similar (they’re just using tags)                              :track-IPG-data, 2018-12-03, 2018-12-31
      Integrate with IPG APIs, if any                                                                                   :integrate-IPG-APIs, 2018-12-03, 2018-12-31
    
{{</mermaid>}}

---