# Steps to reproduce

1. Install Valkey
2. Start Valkey server via `start-valkey` script
3. Start test via `ruby test.rb`
4. Start Valkey pub/sub message publishing via `publish-messages` script

When the Valkey listener experiences EOF, test.rb will crash. 
