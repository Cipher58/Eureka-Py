# Eureka-Py

Library for interaction with the Eureka API.

## Installation

``` bash
pip install EurekaPy
```

## Usage

``` python

from EurekaPy import *


# Replace YOUR_API_KEY with your actual API key

Agent = Eureka_Agent("YOUR_API_KEY")

# Send a message to the API

request_response = Agent.say("Hello, world!")

# JSONify the response (Makes it more readable)

response = request_response.json()

# Print the response JSON

print(response)

# Extract the text response

text_response = response.get("response")

print(text_response)

```
