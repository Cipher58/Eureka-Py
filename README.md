# Eureka-Py: Library for interaction with the Eureka API.

## Installation

``` bash
pip install Eureka-py
```

## Usage

``` python

from eurekapy import Eureka


# Replace YOUR_API_KEY with your actual API key

eureka = Eureka("YOUR_API_KEY", "YOUR_AGENTS_NAME")

# Send a message to the API

response = eureka.say("Hello, world!", "player123")

# Print the response text

print(response)

```

In reference to the original work done by LazyLyrics, the license agreement remains constant under the MIT License.
