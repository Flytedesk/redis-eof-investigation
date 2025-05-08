# Steps to reproduce

1. Install Redis
2. Start Redis server via `start_redis` script
3. Start test via `ruby test.rb`
4. Start Redis pub/sub message publishing via `publish-messages` script

When the Redis listener experiences EOF, test.rb will crash. 
