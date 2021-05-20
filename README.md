# Bible Planner

Generate a Bible reading plan to your liking! This project makes it possible to generate a reading plan
from simply three things:

- A list of books of the Bible
- The duration
- The start date

Clone the project, modify the `config.json` file with your desired settings, and generate your own custom Bible reading plan.
Some examples are provided in the `samples` directory.

\*Note: The project scrapes metadata from the [API.Bible API](https://scripture.api.bible/). In order to do this, you must store the API key in a `secrets.py` file in the root of the project directory. For example, my `secrets.py` file looks like the following:

```python
"""
This file stores project secrets. DO NOT COMMIT THIS FILE.

Copyright 2021 David Kim. All rights reserved.
"""

# API key for this project -> Bible API
API_KEY = "cccf6b6a21d55a0582dca22359******"
```

Obtaining an API key is extremely easy. Simply visit their [website](https://docs.api.bible/getting-started/setup-an-account) and sign up for a developer account. Then, you should have a default API key you can use for any app, including this one.

However, if you do not wish to go through all this hassle, you can just use the pre-fetched data in the `cache` directory. I've already scraped the API for you ;)
