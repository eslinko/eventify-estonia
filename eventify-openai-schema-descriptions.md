# OpenAPI Schema Descriptions

## paths.post.description
This endpoint processes the event's description text and generates structured outputs that emphasize the event's alignment with key psychological and neurobiological criteria relevant to personal growth, socialization, and mental health improvement. It stores the event data in the vector database for efficient retrieval.

## paths.post.requestBody.content.application_json.schema.properties.event_data.description
Data related to the event being added. Users can upload PDFs, screenshots, provide links, or manually input text data. Process all input data together.

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.name.description
The name of the event.

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.desc_4_semantic.description
The semantic description of the event. For detailed structuring guidelines, please refer to the external [documentation](https://github.com/eslinko/eventify-estonia/blob/main/semantic-description-guidelines.md).

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.desc_4_euclidean.description
The normalized description of the event for Euclidean search, focusing on practical details and structured for vector-based search algorithms.

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.start_time.description
Start date and time of the event.

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.end_time.description
End date and time of the event (optional).

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.place.description
Location where the event is held.

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.place.properties.name.description
Name of the venue.

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.place.properties.location.properties.city.description
City of the venue.

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.place.properties.location.properties.country.description
Country of the venue.

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.place.properties.location.properties.street.description
Street address of the venue.

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.ticket_uri.description
Link to the ticketing service.

## paths.post.requestBody.content.application_json.schema.properties.event_data.properties.external_links.description
Links to external sites mentioned in the details.

## paths.post.responses.200.description
Successful addition of the event to the database.

## paths.post.responses.400.description
Bad request, typically due to missing or incorrect parameters.
