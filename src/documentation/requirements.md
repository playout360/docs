# Project Requirements

## Key Requirements



* Multiple vendor solution - The playout should not be restricted for a single user. It should support multiple organizations so that the software can be hosted as SAAS (Software as a service) in a cloud platform
* AWS / Cloud friendly - We should plan the design so that the storage of the media files can be anywhere like in S3, Google cloud storage ...etc
* Encoding and Media Management - We should support AWS online encoding & ffmpeg encoding in the same server / different server. Some automation should be there for copying files back and forth from cloud storage, encoding machines and playout machine...etc
* The whole design should be micro service architecture. All the services are independent services those can run standalone independent of this project. For example File Storage service (It should be like S3 and its API), Encoding service, Playout service ...etc
* Licensing, product registration, usage restrictions and expiration - We should have some control and best in-class licensing model so that we can provide in-house installations even without internet connection.



## General Requirements



* Media file ingestion - Nice file management feature with categories and grouping of media should be there for better media organization
* Channels - Support for multiple channels
* Playlists - List of video files in a priority basis
* Media Trim - Can be able to specify start time and end time in a media file while adding it to playlist.
* Scheduling - To start a playlist at a specific time and repeat on specific days feature should be there. Schedule can be a live stream for a specific duration or a playlist.
* Fallback playlist - If no schedule found, then the system will play the fallback playlist.
* Overalys - Logo overlay and banner ads should be supported.
* Commercial insertion - Ad insertion feature via our own REST API. And also support for general standards for ad insertion tags and ad exchanges ...etc. We should design the structure by considering these features.
* Schedule type: Image and Text for a specific duration
* Prior notifications about issues
* Single server installation compatible
* Configurable user types for signing in and restrictions
* EPG entry and serve using a seprate API for user
* A separte API for user which includes required features
* User management and API keys should be there for provide communication API for the user to our system. User permissions should be there.
* Pricing related feature restriction should be kept in mind while designing the architecture.
