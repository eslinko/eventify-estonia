# EventiZeya OpenAI Schema Descriptions

## /add-event-post
Imagine you’re creating a post for Instagram. Think of all the key aspects of the event, the experience it offers, and the audience it targets. Now, create hashtags that capture these ideas. Separate them with commas, and ensure they encompass all possible dimensions of the event, from practical details to the emotional resonance it might evoke.

## /name
The name of the event.

## /start_time
Start date and time of the event.

## /end_time
End date and time of the event (optional).

## /place
Details about the location where the event is held.

### /place/name
Name of the venue.

### /place/city
City of the venue.

### /place/country
Country of the venue.

### /place/street
Street address of the venue.

## /format
The format of the event. The format can be one of the following, each tailored to different aspects of personal development, learning, healing, and mental health:
- Masterclass: An intensive learning session led by an expert, focusing on hands-on practice and skill development. Ideal for participants seeking in-depth, practical experience and personal feedback in a focused setting.
- Regular: Ongoing or recurring events designed for continuous skill development or mental health maintenance. These events help establish long-term habits and provide consistent support for personal growth.
- Performance: A public presentation that emphasizes emotional impact and cultural enrichment. Performances often inspire, entertain, and can serve as a form of group therapy through artistic expression.
- Exhibition: A display or demonstration of works, aimed at inspiring, educating, or fostering discussion. Exhibitions often include visual presentations and interactive elements to engage participants in learning and reflection.
- Festival: A large-scale event that combines multiple activities, focusing on social interaction and cultural exchange. Festivals are ideal for broadening one’s cultural horizons and experiencing a variety of formats in a communal setting.
- Dance: Physical activities centered around movement and emotional expression, promoting physical and mental well-being. Dance events enhance group interaction, relaxation, and mood elevation through various dance styles.
- Sound Healing: Sessions that use sound vibrations for healing and meditation, focusing on both mental and physical recovery. Sound healing events often incorporate gongs, bowls, and nature sounds to facilitate deep relaxation and meditative states.
- Sacred Ceremony: Spiritual practices that often involve rituals, focusing on deep emotional and spiritual experiences. Sacred ceremonies utilize sacred objects, collective rituals, and meditative practices to foster profound spiritual connections.

## /contact_info
Information about how to contact the event organizer.

### /contact_info/phone
Phone number for contacting the organizer.

### /contact_info/email
Email address for contacting the organizer.

### /contact_info/telegram
Telegram handle for contacting the organizer.

### /contact_info/deso_alias
DeSo alias for contacting the organizer.

## /crypto_wallet
Information about the crypto wallet for payments.

### /crypto_wallet/wallet_address
The crypto wallet address for receiving payments.

### /crypto_wallet/network
The blockchain network on which the wallet is based (e.g., Ethereum, Binance Smart Chain).

## /external_links
Links to external sites that provide additional details about the event.

## /event_added_success
Event added successfully.

## /event_id
The unique identifier of the event in the database.

## /bad_request
Bad request, typically due to missing or incorrect parameters.

## /bad_request_message
Bad request: missing required fields.
