---
name: Fitbit
x-slug: fitbit
description: Find your fit with Fitbits family of fitness products that help you stay
  motivated and improve your health by tracking your activity, exercise, food, weight
  and sleep.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
x-kinRank: "9"
x-alexaRank: "2266"
tags: Logging
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/apis.md
specificationVersion: "0.14"
apis:
- name: Fitbit - Post User Foods Log Goal.json
  x-api-slug: userfoodsloggoal-json-post
  description: Update (create) a user's daily calorie consumption goal or Food Plan
    and get a response in the format requested. Food Plan could not be created unless
    user already has active goal (Update-Weight-Goal). Depending on the weight goal
    setup only either MAINTENANCE (in case start weight is close to target weight
    or smaller) or one of the four other "lose" food plans could be created via intensity
    POST parameter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-post-openapi.md
- name: Fitbit - Get User Foods Log Goal.json
  x-api-slug: userfoodsloggoal-json-get
  description: Get a user's current daily calorie consumption goal and/or Food Plan
    in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-get-openapi.md
- name: Fitbit - Delete User Foods Log Water Water Log .json
  x-api-slug: userfoodslogwaterwaterlogid-json-delete
  description: Delete user's water log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterwaterlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterwaterlogid-json-delete-openapi.md
- name: Fitbit - Post User Foods Log Water.json
  x-api-slug: userfoodslogwater-json-post
  description: Create log entry for a water using units in the unit system that corresponds
    to the Accept-Language header provided (or waterUnit) and get a response in the
    format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwater-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwater-json-post-openapi.md
- name: Fitbit - Get User Foods Log Water Date Date .json
  x-api-slug: userfoodslogwaterdatedate-json-get
  description: Get a summary and list of a user's water log entries for a given day
    in the format requested using units in the unit system which corresponds to the
    Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterdatedate-json-get-openapi.md
- name: Fitbit - Delete User Foods Log Favorite .json
  x-api-slug: userfoodslogfavoriteid-json-delete
  description: Delete the food with the given id from user's list of favorite foods.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-delete-openapi.md
- name: Fitbit - Post User Foods Log Favorite .json
  x-api-slug: userfoodslogfavoriteid-json-post
  description: Add the food with the given id to user's list of favorite foods.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-post-openapi.md
- name: Fitbit - Delete User Activities Log Favorite .json
  x-api-slug: useractivitieslogfavoriteid-json-delete
  description: Delete the activity with the given id from user's list of favorite
    activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-openapi.md
- name: Fitbit - Post User Activities Log Favorite .json
  x-api-slug: useractivitieslogfavoriteid-json-post
  description: Adds the activity with the given id to user's list of favorite activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-openapi.md
- name: Fitbit - Get User Foods Log Favorite.json
  x-api-slug: userfoodslogfavorite-json-get
  description: Get a list of a user's favorite foods in the format requested. A user
    marks a food as favorite on the user's Food Tab tab. A favorite food in the list
    provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavorite-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavorite-json-get-openapi.md
- name: Fitbit - Get User Foods Log Frequent.json
  x-api-slug: userfoodslogfrequent-json-get
  description: Get a list of a user's frequent foods in the format requested. A frequent
    food in the list provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfrequent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfrequent-json-get-openapi.md
- name: Fitbit - Get User Foods Log Recent.json
  x-api-slug: userfoodslogrecent-json-get
  description: Get a list of a user's recent foods in the format requested. A recent
    food provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogrecent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogrecent-json-get-openapi.md
- name: Fitbit - Get User User Foods Log Caloriesin Date Start Date Or End Date End
    Date Or Period .json
  x-api-slug: useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiod-json-get
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiod-json-get-openapi.md
- name: Fitbit - Post User Body Log Fat Goal.json
  x-api-slug: userbodylogfatgoal-json-post
  description: Create or updates user's fat goal and get a response in the format
    requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-post-openapi.md
- name: Fitbit - Get User Body Log Fat Goal.json
  x-api-slug: userbodylogfatgoal-json-get
  description: Get a user's current fat goal in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-get-openapi.md
- name: Fitbit - Post User Body Log Weight Goal.json
  x-api-slug: userbodylogweightgoal-json-post
  description: Create or update user's weight goal using units in the unit system
    that corresponds to the Accept-Language header provided and get a response in
    the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-post-openapi.md
- name: Fitbit - Get User Body Log Weight Goal.json
  x-api-slug: userbodylogweightgoal-json-get
  description: Get a user's current weight goal using units in the unit system that
    corresponds to the Accept-Language header provided in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-get-openapi.md
- name: Fitbit - Delete User Body Log Fat Body Fat Log .json
  x-api-slug: userbodylogfatbodyfatlogid-json-delete
  description: Delete user's body fat log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyfatlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyfatlogid-json-delete-openapi.md
- name: Fitbit - Delete User Body Log Fat Body Weight Log .json
  x-api-slug: userbodylogfatbodyweightlogid-json-delete
  description: Delete user's body weight log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyweightlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyweightlogid-json-delete-openapi.md
- name: Fitbit - Post User Body Log Fat.json
  x-api-slug: userbodylogfat-json-post
  description: Create log entry for a body fat and get a response in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfat-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfat-json-post-openapi.md
- name: Fitbit - Post User Body Log Weight.json
  x-api-slug: userbodylogweight-json-post
  description: Create log entry for a body weight using units in the unit system that
    corresponds to the Accept-Language header provided and get a response in the format
    requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweight-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweight-json-post-openapi.md
- name: Fitbit - Delete User Foods Log Food Log .json
  x-api-slug: userfoodslogfoodlogid-json-delete
  description: Delete the user's food log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfoodlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfoodlogid-json-delete-openapi.md
- name: Fitbit - Get User User Foods Log Date Date .json
  x-api-slug: useruseridfoodslogdatedate-json-get
  description: Get a summary and list of a user's food log entries for a given day
    in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogdatedate-json-get-openapi.md
- name: Fitbit - Get User Body Log Fat Date Date .json
  x-api-slug: userbodylogfatdatedate-json-get
  description: Get a list of all user's body fat log entries for a given day in the
    format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatdatedate-json-get-openapi.md
- name: Fitbit - Get User Body Log Weight Date Date .json
  x-api-slug: userbodylogweightdatedate-json-get
  description: Get a list of all user's body weight log entries for a given day in
    the format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightdatedate-json-get-openapi.md
- name: Fitbit - Post User Foods Log.json
  x-api-slug: userfoodslog-json-post
  description: Create log entry for a food. You need to select one of the unit ids
    to create a food log entry. It is possible to fetch unit ids allowed for specific
    food via previous calls to endpoints that retrieve food lists of the user. Each
    unit id maps to a unit in the list returned via the Get Food Units API call.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslog-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslog-json-post-openapi.md
- name: Fitbit - Post User Foods Log Goal.json
  x-api-slug: userfoodsloggoal-json-post
  description: Update (create) a user's daily calorie consumption goal or Food Plan
    and get a response in the format requested. Food Plan could not be created unless
    user already has active goal (Update-Weight-Goal). Depending on the weight goal
    setup only either MAINTENANCE (in case start weight is close to target weight
    or smaller) or one of the four other "lose" food plans could be created via intensity
    POST parameter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-post-openapi.md
- name: Fitbit - Get User Foods Log Goal.json
  x-api-slug: userfoodsloggoal-json-get
  description: Get a user's current daily calorie consumption goal and/or Food Plan
    in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-get-openapi.md
- name: Fitbit - Delete User Foods Log Water Water Log .json
  x-api-slug: userfoodslogwaterwaterlogid-json-delete
  description: Delete user's water log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterwaterlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterwaterlogid-json-delete-openapi.md
- name: Fitbit - Post User Foods Log Water.json
  x-api-slug: userfoodslogwater-json-post
  description: Create log entry for a water using units in the unit system that corresponds
    to the Accept-Language header provided (or waterUnit) and get a response in the
    format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwater-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwater-json-post-openapi.md
- name: Fitbit - Get User Foods Log Water Date Date .json
  x-api-slug: userfoodslogwaterdatedate-json-get
  description: Get a summary and list of a user's water log entries for a given day
    in the format requested using units in the unit system which corresponds to the
    Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterdatedate-json-get-openapi.md
- name: Fitbit - Delete User Foods Log Favorite .json
  x-api-slug: userfoodslogfavoriteid-json-delete
  description: Delete the food with the given id from user's list of favorite foods.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-delete-openapi.md
- name: Fitbit - Post User Foods Log Favorite .json
  x-api-slug: userfoodslogfavoriteid-json-post
  description: Add the food with the given id to user's list of favorite foods.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-post-openapi.md
- name: Fitbit - Delete User Activities Log Favorite .json
  x-api-slug: useractivitieslogfavoriteid-json-delete
  description: Delete the activity with the given id from user's list of favorite
    activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-openapi.md
- name: Fitbit - Post User Activities Log Favorite .json
  x-api-slug: useractivitieslogfavoriteid-json-post
  description: Adds the activity with the given id to user's list of favorite activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-openapi.md
- name: Fitbit - Get User Foods Log Favorite.json
  x-api-slug: userfoodslogfavorite-json-get
  description: Get a list of a user's favorite foods in the format requested. A user
    marks a food as favorite on the user's Food Tab tab. A favorite food in the list
    provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavorite-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavorite-json-get-openapi.md
- name: Fitbit - Get User Foods Log Frequent.json
  x-api-slug: userfoodslogfrequent-json-get
  description: Get a list of a user's frequent foods in the format requested. A frequent
    food in the list provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfrequent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfrequent-json-get-openapi.md
- name: Fitbit - Get User Foods Log Recent.json
  x-api-slug: userfoodslogrecent-json-get
  description: Get a list of a user's recent foods in the format requested. A recent
    food provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogrecent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogrecent-json-get-openapi.md
- name: Fitbit - Get User User Foods Log Caloriesin Date Start Date Or End Date End
    Date Or Period .json
  x-api-slug: useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiod-json-get
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiod-json-get-openapi.md
- name: Fitbit - Post User Body Log Fat Goal.json
  x-api-slug: userbodylogfatgoal-json-post
  description: Create or updates user's fat goal and get a response in the format
    requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-post-openapi.md
- name: Fitbit - Get User Body Log Fat Goal.json
  x-api-slug: userbodylogfatgoal-json-get
  description: Get a user's current fat goal in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-get-openapi.md
- name: Fitbit - Post User Body Log Weight Goal.json
  x-api-slug: userbodylogweightgoal-json-post
  description: Create or update user's weight goal using units in the unit system
    that corresponds to the Accept-Language header provided and get a response in
    the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-post-openapi.md
- name: Fitbit - Get User Body Log Weight Goal.json
  x-api-slug: userbodylogweightgoal-json-get
  description: Get a user's current weight goal using units in the unit system that
    corresponds to the Accept-Language header provided in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-get-openapi.md
- name: Fitbit - Delete User Body Log Fat Body Fat Log .json
  x-api-slug: userbodylogfatbodyfatlogid-json-delete
  description: Delete user's body fat log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyfatlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyfatlogid-json-delete-openapi.md
- name: Fitbit - Delete User Body Log Fat Body Weight Log .json
  x-api-slug: userbodylogfatbodyweightlogid-json-delete
  description: Delete user's body weight log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyweightlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyweightlogid-json-delete-openapi.md
- name: Fitbit - Post User Body Log Fat.json
  x-api-slug: userbodylogfat-json-post
  description: Create log entry for a body fat and get a response in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfat-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfat-json-post-openapi.md
- name: Fitbit - Post User Body Log Weight.json
  x-api-slug: userbodylogweight-json-post
  description: Create log entry for a body weight using units in the unit system that
    corresponds to the Accept-Language header provided and get a response in the format
    requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweight-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweight-json-post-openapi.md
- name: Fitbit - Delete User Foods Log Food Log .json
  x-api-slug: userfoodslogfoodlogid-json-delete
  description: Delete the user's food log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfoodlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfoodlogid-json-delete-openapi.md
- name: Fitbit - Get User User Foods Log Date Date .json
  x-api-slug: useruseridfoodslogdatedate-json-get
  description: Get a summary and list of a user's food log entries for a given day
    in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogdatedate-json-get-openapi.md
- name: Fitbit - Get User Body Log Fat Date Date .json
  x-api-slug: userbodylogfatdatedate-json-get
  description: Get a list of all user's body fat log entries for a given day in the
    format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatdatedate-json-get-openapi.md
- name: Fitbit - Get User Body Log Weight Date Date .json
  x-api-slug: userbodylogweightdatedate-json-get
  description: Get a list of all user's body weight log entries for a given day in
    the format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightdatedate-json-get-openapi.md
- name: Fitbit - Post User Foods Log.json
  x-api-slug: userfoodslog-json-post
  description: Create log entry for a food. You need to select one of the unit ids
    to create a food log entry. It is possible to fetch unit ids allowed for specific
    food via previous calls to endpoints that retrieve food lists of the user. Each
    unit id maps to a unit in the list returned via the Get Food Units API call.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslog-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslog-json-post-openapi.md
- name: Fitbit - Get User Body Log Weight Date Date .json
  x-api-slug: userbodylogweightdatedate-json-get
  description: Get a list of all user's body weight log entries for a given day in
    the format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightdatedate-json-get-openapi.md
- name: Fitbit - Get User Body Log Fat Date Date .json
  x-api-slug: userbodylogfatdatedate-json-get
  description: Get a list of all user's body fat log entries for a given day in the
    format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatdatedate-json-get-openapi.md
- name: Fitbit - Get User User Foods Log Date Date .json
  x-api-slug: useruseridfoodslogdatedate-json-get
  description: Get a summary and list of a user's food log entries for a given day
    in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogdatedate-json-get-openapi.md
- name: Fitbit - Delete User Foods Log Food Log .json
  x-api-slug: userfoodslogfoodlogid-json-delete
  description: Delete the user's food log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfoodlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfoodlogid-json-delete-openapi.md
- name: Fitbit - Post User Body Log Weight.json
  x-api-slug: userbodylogweight-json-post
  description: Create log entry for a body weight using units in the unit system that
    corresponds to the Accept-Language header provided and get a response in the format
    requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweight-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweight-json-post-openapi.md
- name: Fitbit - Post User Body Log Fat.json
  x-api-slug: userbodylogfat-json-post
  description: Create log entry for a body fat and get a response in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfat-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfat-json-post-openapi.md
- name: Fitbit - Delete User Body Log Fat Body Weight Log .json
  x-api-slug: userbodylogfatbodyweightlogid-json-delete
  description: Delete user's body weight log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyweightlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyweightlogid-json-delete-openapi.md
- name: Fitbit - Delete User Body Log Fat Body Fat Log .json
  x-api-slug: userbodylogfatbodyfatlogid-json-delete
  description: Delete user's body fat log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyfatlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatbodyfatlogid-json-delete-openapi.md
- name: Fitbit - Get User Body Log Weight Goal.json
  x-api-slug: userbodylogweightgoal-json-get
  description: Get a user's current weight goal using units in the unit system that
    corresponds to the Accept-Language header provided in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-get-openapi.md
- name: Fitbit - Post User Body Log Weight Goal.json
  x-api-slug: userbodylogweightgoal-json-post
  description: Create or update user's weight goal using units in the unit system
    that corresponds to the Accept-Language header provided and get a response in
    the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogweightgoal-json-post-openapi.md
- name: Fitbit - Get User Body Log Fat Goal.json
  x-api-slug: userbodylogfatgoal-json-get
  description: Get a user's current fat goal in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-get-openapi.md
- name: Fitbit - Post User Body Log Fat Goal.json
  x-api-slug: userbodylogfatgoal-json-post
  description: Create or updates user's fat goal and get a response in the format
    requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userbodylogfatgoal-json-post-openapi.md
- name: Fitbit - Get User User Foods Log Caloriesin Date Start Date Or End Date End
    Date Or Period .json
  x-api-slug: useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiod-json-get
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useruseridfoodslogcaloriesindatestartdateorenddateenddateorperiod-json-get-openapi.md
- name: Fitbit - Get User Foods Log Recent.json
  x-api-slug: userfoodslogrecent-json-get
  description: Get a list of a user's recent foods in the format requested. A recent
    food provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogrecent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogrecent-json-get-openapi.md
- name: Fitbit - Get User Foods Log Frequent.json
  x-api-slug: userfoodslogfrequent-json-get
  description: Get a list of a user's frequent foods in the format requested. A frequent
    food in the list provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfrequent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfrequent-json-get-openapi.md
- name: Fitbit - Get User Foods Log Favorite.json
  x-api-slug: userfoodslogfavorite-json-get
  description: Get a list of a user's favorite foods in the format requested. A user
    marks a food as favorite on the user's Food Tab tab. A favorite food in the list
    provides a quick way to log the food via the Log Food endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavorite-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavorite-json-get-openapi.md
- name: Fitbit - Post User Activities Log Favorite .json
  x-api-slug: useractivitieslogfavoriteid-json-post
  description: Adds the activity with the given id to user's list of favorite activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-openapi.md
- name: Fitbit - Delete User Activities Log Favorite .json
  x-api-slug: useractivitieslogfavoriteid-json-delete
  description: Delete the activity with the given id from user's list of favorite
    activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-openapi.md
- name: Fitbit - Post User Foods Log Favorite .json
  x-api-slug: userfoodslogfavoriteid-json-post
  description: Add the food with the given id to user's list of favorite foods.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-post-openapi.md
- name: Fitbit - Delete User Foods Log Favorite .json
  x-api-slug: userfoodslogfavoriteid-json-delete
  description: Delete the food with the given id from user's list of favorite foods.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogfavoriteid-json-delete-openapi.md
- name: Fitbit - Get User Foods Log Water Date Date .json
  x-api-slug: userfoodslogwaterdatedate-json-get
  description: Get a summary and list of a user's water log entries for a given day
    in the format requested using units in the unit system which corresponds to the
    Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterdatedate-json-get-openapi.md
- name: Fitbit - Post User Foods Log Water.json
  x-api-slug: userfoodslogwater-json-post
  description: Create log entry for a water using units in the unit system that corresponds
    to the Accept-Language header provided (or waterUnit) and get a response in the
    format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwater-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwater-json-post-openapi.md
- name: Fitbit - Delete User Foods Log Water Water Log .json
  x-api-slug: userfoodslogwaterwaterlogid-json-delete
  description: Delete user's water log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterwaterlogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslogwaterwaterlogid-json-delete-openapi.md
- name: Fitbit - Get User Foods Log Goal.json
  x-api-slug: userfoodsloggoal-json-get
  description: Get a user's current daily calorie consumption goal and/or Food Plan
    in the format requested.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-get-openapi.md
- name: Fitbit - Post User Foods Log Goal.json
  x-api-slug: userfoodsloggoal-json-post
  description: Update (create) a user's daily calorie consumption goal or Food Plan
    and get a response in the format requested. Food Plan could not be created unless
    user already has active goal (Update-Weight-Goal). Depending on the weight goal
    setup only either MAINTENANCE (in case start weight is close to target weight
    or smaller) or one of the four other "lose" food plans could be created via intensity
    POST parameter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodsloggoal-json-post-openapi.md
- name: Fitbit - Post User Foods Log.json
  x-api-slug: userfoodslog-json-post
  description: Create log entry for a food. You need to select one of the unit ids
    to create a food log entry. It is possible to fetch unit ids allowed for specific
    food via previous calls to endpoints that retrieve food lists of the user. Each
    unit id maps to a unit in the list returned via the Get Food Units API call.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslog-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/fitbit/userfoodslog-json-post-openapi.md
x-common:
- type: x-api-json--authoritative
  url: https://www.fitbit.com/apis.json
- type: x-openapi
  url: https://dev.fitbit.com/reference/web-api/explore/fitbit-web-api.swagger.json
- type: x-api-gallery
  url: http://first.trust.bank.api.gallery.streamdata.io
- type: x-api-stack
  url: http://fitbit.stack.network
- type: x-apigee-console
  url: https://wiki.fitbit.com/display/API/API+Explorer
- type: x-blog
  url: http://blog.fitbit.com
- type: x-blog-rss
  url: http://blog.fitbit.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/fitbit
- type: x-crunchbase
  url: https://crunchbase.com/organization/fitbit
- type: x-email
  url: privacy@fitbit.com
- type: x-github
  url: https://github.com/fitbit
- type: x-rate-limits
  url: https://wiki.fitbit.com/display/API/Rate+Limit
- type: x-twitter
  url: https://twitter.com/fitbit
- type: x-website
  url: http://fitbit.com
- type: x-website
  url: http://dev.fitbit.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---