# Integration Testing Repository
This is integration testing repository, used for testing summarization integration.

# 2026.01.12T22:46:00
First test trying to sync, did not work. The pipeline failed with wrong accesses. The backfill worked tho.

# 2026.01.12T22:52:00
Seems like the previous entry was caused by a bug due to incorrect deletion of uninstalled apps. Testing push 
events for commits instead of the polling.

# 2026.01.12T23:06:00
Previous attempt did not work due to the incorrect subscriptions. This is redeployed app with subscription for pushes to repos.