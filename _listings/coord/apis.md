---
name: Coord
x-slug: coord
description: Coord is a mobility company that creates seamless mobility and self-driving
  experiences today through deep integrations. The company offers bike-share API,
  Curbs API, Tolls API, Routing API and etc.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
x-kinRank: "7"
x-alexaRank: "1035226"
tags: Areas
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/apis.md
specificationVersion: "0.14"
apis:
- name: Coord Bike Share API
  x-api-slug: coord-bike-share-api
  description: the-bike-share-api-is-a-comprehensive-api-that-provides-information-about-bike-sharesystems-including-available-bikes-and-prices-for-an-example-of-how-to-use-the-bike-share-api-see-the-a-hrefhttpscoord-coquickstartbikeshare-target-blankbike-share-guidea--examplesearch-for-a-bikecurl-g-httpsapi-coord-cov1bikelocationlatitude40-73935542longitude73-99931783radius-km0-1access-keyyour-api-keythe-api-methods-allow-you-to-search-for-available-bikes-and-get-quotes-on-bike-rentalsas-well-as-get-detailed-information-about-bike-share-systems-and-bike-share-locations-bike-share-systems-have-one-or-more-locations--since-bikes-in-a-bike-share-system-may-be-in-adock-or-individually-parked-a-bike-location-can-refer-to-either-a-dock-or-a-single-separatelyparked-bike--therefore-a-search-for-bike-locations-is-really-a-search-for-rideable-bikes-bikes-that-are-currently-inuse-or-otherwise-not-ready-for-rental-are-not-searchable-throughthis-api-the-simplest-method-to-call-is-locationreference0findbikesbylocation-with-a-targetlatitude-and-longitude-and-a-search-radius--this-will-return-all-available-locations-withinthat-radius-and-information-about-each-location-calling-quotereference0getquote-will-return-all-quotes-for-allsystems-or-if-provided-with-specific-system-ids-quotes-for-just-the-specified-systems-calls-to-systemsystem-idreference0getbikesystem-orlocationsystem-idlocation-idreference0getbikelocation-are-helpful-toget-more-information-about-individual-systems-or-locations-respectively-calling-systemreference0findbikesystemsbylocation-with-a-target-latitude-and-longitudeand-a-search-radius-will-return-all-systems-within-that-radius-and-information-about-eachsystem--quotes-and-passesquotes-are-the-cost-and-details-of-renting-a-single-bike-from-a-system--they-consist-of-aset-of-pass-types-where-each-type-defines-a-buyable-pass-for-a-system--a-passrepresents-the-right-to-rent-bikes-from-a-single-system-for-a-certain-length-of-time-or-acertain-number-of-rides--for-instance-you-could-see-a-single-ride-pass-a-single-day-passa-30day-pass-or-an-annual-pass-passes-also-come-with-usage-fees-that-represent-the-cost-of-riding-a-bike-for-a-certainlength-of-time-within-a-given-rental--to-model-systems-that-charge-solely-by-the-length-ofeach-ride-with-no-upfront-charge-we-return-a-single-0-pass-type-representing-the-systemspricing-in-general-with-charge-by-time-set-to-true--finally-we-have-information-about-thetax-rate-this-pass-could-be-subject-to-here-is-an-example-3day-pass-that-costs-24-00-where-rides-over-30-minutes-are-billed-at-5-per15-minutes---id-2--system-id-citibike--max-days-3--charge-by-time-false--cost-----currency-usd----amount-2400----usage-fees-----cost-------currency-usd------amount-500--------prorated-false----start-time-seconds-1800----fee-increment-seconds-900----tax-regions-----name-new-york-city----tax-rate-0-08875-------name-jersey-city----tax-rate-0-07--here-is-an-example-7-95-singleride-pass-with-usage-fees-and-tax-details-omitted--id-1--system-id-citibike--max-rides-1--charge-by-time-false--cost-----currency-usd----amount-795----usage-fees------------tax-regions----------and-heres-an-example-from-a-pay-as-you-go-system-that-charges-2-for-30-minutes-and-7-cents-aminute-thereafter--as-you-can-see-usage-fees-are-cumulative-they-all-get-charged-togetheras-a-single-ride-increases-in-length-and-passes-each-of-their-start-time-seconds-values---id-3--system-id-jumpdc--charge-by-time-true--usage-fees-----cost-------currency-usd------amount-200--------prorated-false----start-time-seconds-0-------cost-------currency-usd------amount-7--------prorated-false----start-time-seconds-1800----fee-increment-seconds-60----tax-regions----------
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/location-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/location-get-openapi.md
- name: Coord Bike Share API
  x-api-slug: coord-bike-share-api
  description: the-bike-share-api-is-a-comprehensive-api-that-provides-information-about-bike-sharesystems-including-available-bikes-and-prices-for-an-example-of-how-to-use-the-bike-share-api-see-the-a-hrefhttpscoord-coquickstartbikeshare-target-blankbike-share-guidea--examplesearch-for-a-bikecurl-g-httpsapi-coord-cov1bikelocationlatitude40-73935542longitude73-99931783radius-km0-1access-keyyour-api-keythe-api-methods-allow-you-to-search-for-available-bikes-and-get-quotes-on-bike-rentalsas-well-as-get-detailed-information-about-bike-share-systems-and-bike-share-locations-bike-share-systems-have-one-or-more-locations--since-bikes-in-a-bike-share-system-may-be-in-adock-or-individually-parked-a-bike-location-can-refer-to-either-a-dock-or-a-single-separatelyparked-bike--therefore-a-search-for-bike-locations-is-really-a-search-for-rideable-bikes-bikes-that-are-currently-inuse-or-otherwise-not-ready-for-rental-are-not-searchable-throughthis-api-the-simplest-method-to-call-is-locationreference0findbikesbylocation-with-a-targetlatitude-and-longitude-and-a-search-radius--this-will-return-all-available-locations-withinthat-radius-and-information-about-each-location-calling-quotereference0getquote-will-return-all-quotes-for-allsystems-or-if-provided-with-specific-system-ids-quotes-for-just-the-specified-systems-calls-to-systemsystem-idreference0getbikesystem-orlocationsystem-idlocation-idreference0getbikelocation-are-helpful-toget-more-information-about-individual-systems-or-locations-respectively-calling-systemreference0findbikesystemsbylocation-with-a-target-latitude-and-longitudeand-a-search-radius-will-return-all-systems-within-that-radius-and-information-about-eachsystem--quotes-and-passesquotes-are-the-cost-and-details-of-renting-a-single-bike-from-a-system--they-consist-of-aset-of-pass-types-where-each-type-defines-a-buyable-pass-for-a-system--a-passrepresents-the-right-to-rent-bikes-from-a-single-system-for-a-certain-length-of-time-or-acertain-number-of-rides--for-instance-you-could-see-a-single-ride-pass-a-single-day-passa-30day-pass-or-an-annual-pass-passes-also-come-with-usage-fees-that-represent-the-cost-of-riding-a-bike-for-a-certainlength-of-time-within-a-given-rental--to-model-systems-that-charge-solely-by-the-length-ofeach-ride-with-no-upfront-charge-we-return-a-single-0-pass-type-representing-the-systemspricing-in-general-with-charge-by-time-set-to-true--finally-we-have-information-about-thetax-rate-this-pass-could-be-subject-to-here-is-an-example-3day-pass-that-costs-24-00-where-rides-over-30-minutes-are-billed-at-5-per15-minutes---id-2--system-id-citibike--max-days-3--charge-by-time-false--cost-----currency-usd----amount-2400----usage-fees-----cost-------currency-usd------amount-500--------prorated-false----start-time-seconds-1800----fee-increment-seconds-900----tax-regions-----name-new-york-city----tax-rate-0-08875-------name-jersey-city----tax-rate-0-07--here-is-an-example-7-95-singleride-pass-with-usage-fees-and-tax-details-omitted--id-1--system-id-citibike--max-rides-1--charge-by-time-false--cost-----currency-usd----amount-795----usage-fees------------tax-regions----------and-heres-an-example-from-a-pay-as-you-go-system-that-charges-2-for-30-minutes-and-7-cents-aminute-thereafter--as-you-can-see-usage-fees-are-cumulative-they-all-get-charged-togetheras-a-single-ride-increases-in-length-and-passes-each-of-their-start-time-seconds-values---id-3--system-id-jumpdc--charge-by-time-true--usage-fees-----cost-------currency-usd------amount-200--------prorated-false----start-time-seconds-0-------cost-------currency-usd------amount-7--------prorated-false----start-time-seconds-1800----fee-increment-seconds-60----tax-regions----------
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/location-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/location-get-openapi.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/system-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/system-get-openapi.md
- name: Coord Bike Share API
  x-api-slug: coord-bike-share-api
  description: the-bike-share-api-is-a-comprehensive-api-that-provides-information-about-bike-sharesystems-including-available-bikes-and-prices-for-an-example-of-how-to-use-the-bike-share-api-see-the-a-hrefhttpscoord-coquickstartbikeshare-target-blankbike-share-guidea--examplesearch-for-a-bikecurl-g-httpsapi-coord-cov1bikelocationlatitude40-73935542longitude73-99931783radius-km0-1access-keyyour-api-keythe-api-methods-allow-you-to-search-for-available-bikes-and-get-quotes-on-bike-rentalsas-well-as-get-detailed-information-about-bike-share-systems-and-bike-share-locations-bike-share-systems-have-one-or-more-locations--since-bikes-in-a-bike-share-system-may-be-in-adock-or-individually-parked-a-bike-location-can-refer-to-either-a-dock-or-a-single-separatelyparked-bike--therefore-a-search-for-bike-locations-is-really-a-search-for-rideable-bikes-bikes-that-are-currently-inuse-or-otherwise-not-ready-for-rental-are-not-searchable-throughthis-api-the-simplest-method-to-call-is-locationreference0findbikesbylocation-with-a-targetlatitude-and-longitude-and-a-search-radius--this-will-return-all-available-locations-withinthat-radius-and-information-about-each-location-calling-quotereference0getquote-will-return-all-quotes-for-allsystems-or-if-provided-with-specific-system-ids-quotes-for-just-the-specified-systems-calls-to-systemsystem-idreference0getbikesystem-orlocationsystem-idlocation-idreference0getbikelocation-are-helpful-toget-more-information-about-individual-systems-or-locations-respectively-calling-systemreference0findbikesystemsbylocation-with-a-target-latitude-and-longitudeand-a-search-radius-will-return-all-systems-within-that-radius-and-information-about-eachsystem--quotes-and-passesquotes-are-the-cost-and-details-of-renting-a-single-bike-from-a-system--they-consist-of-aset-of-pass-types-where-each-type-defines-a-buyable-pass-for-a-system--a-passrepresents-the-right-to-rent-bikes-from-a-single-system-for-a-certain-length-of-time-or-acertain-number-of-rides--for-instance-you-could-see-a-single-ride-pass-a-single-day-passa-30day-pass-or-an-annual-pass-passes-also-come-with-usage-fees-that-represent-the-cost-of-riding-a-bike-for-a-certainlength-of-time-within-a-given-rental--to-model-systems-that-charge-solely-by-the-length-ofeach-ride-with-no-upfront-charge-we-return-a-single-0-pass-type-representing-the-systemspricing-in-general-with-charge-by-time-set-to-true--finally-we-have-information-about-thetax-rate-this-pass-could-be-subject-to-here-is-an-example-3day-pass-that-costs-24-00-where-rides-over-30-minutes-are-billed-at-5-per15-minutes---id-2--system-id-citibike--max-days-3--charge-by-time-false--cost-----currency-usd----amount-2400----usage-fees-----cost-------currency-usd------amount-500--------prorated-false----start-time-seconds-1800----fee-increment-seconds-900----tax-regions-----name-new-york-city----tax-rate-0-08875-------name-jersey-city----tax-rate-0-07--here-is-an-example-7-95-singleride-pass-with-usage-fees-and-tax-details-omitted--id-1--system-id-citibike--max-rides-1--charge-by-time-false--cost-----currency-usd----amount-795----usage-fees------------tax-regions----------and-heres-an-example-from-a-pay-as-you-go-system-that-charges-2-for-30-minutes-and-7-cents-aminute-thereafter--as-you-can-see-usage-fees-are-cumulative-they-all-get-charged-togetheras-a-single-ride-increases-in-length-and-passes-each-of-their-start-time-seconds-values---id-3--system-id-jumpdc--charge-by-time-true--usage-fees-----cost-------currency-usd------amount-200--------prorated-false----start-time-seconds-0-------cost-------currency-usd------amount-7--------prorated-false----start-time-seconds-1800----fee-increment-seconds-60----tax-regions----------
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/location-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/location-get-openapi.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/system-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/system-get-openapi.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/location-get-openapi.md
- name: Coord Bike Share API
  x-api-slug: coord-bike-share-api
  description: the-bike-share-api-is-a-comprehensive-api-that-provides-information-about-bike-sharesystems-including-available-bikes-and-prices-for-an-example-of-how-to-use-the-bike-share-api-see-the-a-hrefhttpscoord-coquickstartbikeshare-target-blankbike-share-guidea--examplesearch-for-a-bikecurl-g-httpsapi-coord-cov1bikelocationlatitude40-73935542longitude73-99931783radius-km0-1access-keyyour-api-keythe-api-methods-allow-you-to-search-for-available-bikes-and-get-quotes-on-bike-rentalsas-well-as-get-detailed-information-about-bike-share-systems-and-bike-share-locations-bike-share-systems-have-one-or-more-locations--since-bikes-in-a-bike-share-system-may-be-in-adock-or-individually-parked-a-bike-location-can-refer-to-either-a-dock-or-a-single-separatelyparked-bike--therefore-a-search-for-bike-locations-is-really-a-search-for-rideable-bikes-bikes-that-are-currently-inuse-or-otherwise-not-ready-for-rental-are-not-searchable-throughthis-api-the-simplest-method-to-call-is-locationreference0findbikesbylocation-with-a-targetlatitude-and-longitude-and-a-search-radius--this-will-return-all-available-locations-withinthat-radius-and-information-about-each-location-calling-quotereference0getquote-will-return-all-quotes-for-allsystems-or-if-provided-with-specific-system-ids-quotes-for-just-the-specified-systems-calls-to-systemsystem-idreference0getbikesystem-orlocationsystem-idlocation-idreference0getbikelocation-are-helpful-toget-more-information-about-individual-systems-or-locations-respectively-calling-systemreference0findbikesystemsbylocation-with-a-target-latitude-and-longitudeand-a-search-radius-will-return-all-systems-within-that-radius-and-information-about-eachsystem--quotes-and-passesquotes-are-the-cost-and-details-of-renting-a-single-bike-from-a-system--they-consist-of-aset-of-pass-types-where-each-type-defines-a-buyable-pass-for-a-system--a-passrepresents-the-right-to-rent-bikes-from-a-single-system-for-a-certain-length-of-time-or-acertain-number-of-rides--for-instance-you-could-see-a-single-ride-pass-a-single-day-passa-30day-pass-or-an-annual-pass-passes-also-come-with-usage-fees-that-represent-the-cost-of-riding-a-bike-for-a-certainlength-of-time-within-a-given-rental--to-model-systems-that-charge-solely-by-the-length-ofeach-ride-with-no-upfront-charge-we-return-a-single-0-pass-type-representing-the-systemspricing-in-general-with-charge-by-time-set-to-true--finally-we-have-information-about-thetax-rate-this-pass-could-be-subject-to-here-is-an-example-3day-pass-that-costs-24-00-where-rides-over-30-minutes-are-billed-at-5-per15-minutes---id-2--system-id-citibike--max-days-3--charge-by-time-false--cost-----currency-usd----amount-2400----usage-fees-----cost-------currency-usd------amount-500--------prorated-false----start-time-seconds-1800----fee-increment-seconds-900----tax-regions-----name-new-york-city----tax-rate-0-08875-------name-jersey-city----tax-rate-0-07--here-is-an-example-7-95-singleride-pass-with-usage-fees-and-tax-details-omitted--id-1--system-id-citibike--max-rides-1--charge-by-time-false--cost-----currency-usd----amount-795----usage-fees------------tax-regions----------and-heres-an-example-from-a-pay-as-you-go-system-that-charges-2-for-30-minutes-and-7-cents-aminute-thereafter--as-you-can-see-usage-fees-are-cumulative-they-all-get-charged-togetheras-a-single-ride-increases-in-length-and-passes-each-of-their-start-time-seconds-values---id-3--system-id-jumpdc--charge-by-time-true--usage-fees-----cost-------currency-usd------amount-200--------prorated-false----start-time-seconds-0-------cost-------currency-usd------amount-7--------prorated-false----start-time-seconds-1800----fee-increment-seconds-60----tax-regions----------
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/location-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/location-get-openapi.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/system-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/system-get-openapi.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/location-get-openapi.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/system-get-openapi.md
- name: Coord Bike Share API
  x-api-slug: coord-bike-share-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Areas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/openapi.md
- name: Coord Curb Search API
  x-api-slug: coord-curb-search-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Areas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/openapi.md
- name: Coord Multimodal Routing API
  x-api-slug: coord-multimodal-routing-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/routing
  tags: Areas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/openapi.md
- name: Coord Parking Access API
  x-api-slug: coord-parking-access-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/access/parking
  tags: Areas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/openapi.md
- name: Coord Parking Search API
  x-api-slug: coord-parking-search-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/parking
  tags: Areas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/openapi.md
- name: Coord Tolls API
  x-api-slug: coord-tolls-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/tolling
  tags: Areas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/openapi.md
- name: Coord Users API
  x-api-slug: coord-users-api
  description: Coord is a mobility company that creates seamless mobility and self-driving
    experiences today through deep integrations. The company offers bike-share API,
    Curbs API, Tolls API, Routing API and etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/users
  tags: Areas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/areas/master/_listings/coord/openapi.md
x-common:
- type: x-blog
  url: https://medium.com/coord
- type: x-blog-rss
  url: https://medium.com/feed/coord
- type: x-openapi
  url: https://jsapi.apiary.io/apis/coordprodsearchtolls.source
- type: x-api-gallery
  url: http://convertapi.api.gallery.streamdata.io
- type: x-api-stack
  url: http://coord.stack.network
- type: x-developer
  url: https://coord.co/docs/
- type: x-pricing
  url: https://coord.co/#pricing
- type: x-twitter
  url: https://twitter.com/coordcity
- type: x-website
  url: https://coord.co
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---