#### A Python Azure serverless funtion that queries an API based on an event timer, checks if entries have been added or updated since last event trigger. If so, it makes a list of member IDs added or updated, makes revursive calls to API to get updates and additions, updates the data, writes out CSV binary as an IO stream and commits it to Azure Blob storage. 