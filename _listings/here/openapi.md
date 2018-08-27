swagger: "2.0"
x-collection-name: HERE
x-complete: 1
info:
  title: Weather API
  description: the-here-weather-api-provides-weather-forecasts-and-reports-on-current-weather-conditions-provides-information-on-severe-weather-alerts-provides-information-about-when-the-sun-and-moon-rise-and-set-and-the-phase-of-the-moonthis-example-set-works-with-version-1-2-4-or-higheradditional-information-can-be-found-on-developer-here-comhttpsdeveloper-here-comrestapisdocumentationweather
  version: 1.0.0
host: weather.cit.api.here.com
basePath: /weather/1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /isochrone/v1/search.json:
    get:
      summary: Reachability of an Area Within a Specific Time
      description: "*Request a list of the public transit stations that can be reached
        in a given time*\n\nTo find the stations reachable in a specified time use
        the `isochrone/v1/search.json` endpoint specifying a center point using the
        `x` and `y` parameters and a maximum total duration in minutes using the `max_dur
        `parameter.\n  \n\n\n\n* **max_dur**  `number`\n \\- Maximum duration of the
        journeys, in minutes.   Minimum = 5, Maximum = 90.    The default duration
        is 15 minutes.    \n\n* **y**  `number`\n \\- The latitude of the start point
        of your journey.    e.g. `52.515`  \n\n* **x**  `number`\n \\- The longitude
        of the start point of your journey.    e.g. `13.377`    \n\n* **time**  `text`\n
        \\- Specifies the time in ISO 8601 (for example, 2015-10-18T06:36:40)\n        format.
        \n\n* **app_id**  `text`\n \\- A 20 bytes Base64 URL-safe encoded string used
        for the authentication of the client application.    You must include an app_code
        and app_code with every request.\n\n* **app_code**  `text`\n \\- A 20 bytes
        Base64 URL-safe encoded string used for the authentication of the client application.
        \   You must include an app_code and app_code with every request."
      operationId: IsochroneV1SearchJsonGet2
      x-api-path-slug: isochronev1search-json-get
      parameters:
      - in: query
        name: app_code
      - in: query
        name: app_id
      - in: query
        name: max_dur
      - in: query
        name: time
      - in: query
        name: x
      - in: query
        name: "y"
      responses:
        200:
          description: OK
      tags:
      - Reachability
      - Of
      - Area
      - Within
      - Specific
      - Time