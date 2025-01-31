---
description: NeuronCLI API documentation.
---

# API Reference

NeuronCLI allows developers to create and extend AI agents using its modular API.

#### Example API Usage

```
from neuroncli import Agent

class CustomAgent(Agent):
    def respond(self, query):
        return "Hello, this is a custom response!"
```

You can register new agents and extend NeuronCLI’s functionalities through this API.
