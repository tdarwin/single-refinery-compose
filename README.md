# Single Instance Refinery in Docker-Compose

Just update the compose.yml file with your Honeycomb API key and what you want your query auth token to be, and you should be able to `docker-compose up` to get Refinery running happily.

Once Refinery is online (or before you compose up), edit the rules.toml file in the conf directory to match your needed rules for your traffic.
