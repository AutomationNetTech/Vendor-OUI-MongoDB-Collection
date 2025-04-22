# Vendor-OUI-MongoDB-Collection

This MongoDB collection is designed for ultra-fast OUI lookups, leveraging the _id field as the normalized OUI prefix for efficient querying. The database contains vendor OUI data as of 21 April 2025. 

While this dataset is not actively maintained, I will provide a lookup function which is designed to handle missing entries by querying an external API for the latest OUI data. Upon receiving new data from the API, the MongoDB collection is automatically updated with the new entry, ensuring future lookups benefit from the expanded dataset. This approach combines the speed of local database queries with the flexibility of real-time API integration for missing records.
