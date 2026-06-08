### What I'm Working On

#### Python based UIs using the [Reflex.dev](https://github.com/reflex-dev) Framework

- **[Appkit](https://github.com/jenreh/appkit)** Framework with UI components based on [mantine.dev](https://mantine.dev/), 

    - [appkit-commons](https://github.com/jenreh/appkit/tree/main/components/appkit-commons) - Configuration Management, Database convenience, Scheduler, DI with Service Registry
    - [appkit-user](https://github.com/jenreh/appkit/tree/main/components/appkit-user) - Enterprise user management with SSO support, RBAC, Login and Admin UI
    - [appkit-mantine](https://github.com/jenreh/appkit/tree/main/components/appkit-mantine) - Comprehensive [Mantine.dev](https://mantine.dev) UI wrapper for Reflex.dev
    - [appkit-assistant](https://github.com/jenreh/appkit/tree/main/components/appkit-assistant) - AI assistant with MCP server and Skills integration and admin backend
    - [appkit-imagecreator](https://github.com/jenreh/appkit/tree/main/components/appkit-imagecreator) - Multi-AI image generation and admin backend
    - some Appkit based [MCP servers](https://github.com/jenreh/appkit/tree/main/components)
  
    All as components that could be separatly imported in an Appkit based project 

- **[Alloq](https://github.com/jenreh/alloq)** - Resourceplanning and project forecasting for smal teams

#### Graph Databases

- **[Runic](https://github.com/jenreh/runic)** - Graph schema migrations and ORM for Cypher-based graph databases. Currently supports Neo4j, FalkorDB, Memgraph, ArcadeDB and Apache AGE

#### AI Agents and MCP Tools

**[Pantau](https://github.com/jenreh/pantau)** - Voice assistant, currently integrated with 

- [harmonyhub-py](https://github.com/jenreh/harmonyhub-py) - Logitech Harmony Hub
- [huehub-py](https://github.com/jenreh/huehub-py) - Philips Hue
- [sonos-py](https://github.com/jenreh/sonos-py) - Sonos
- [homekit-py](https://github.com/jenreh/homekit-py) - Apple Homekit
- [fritzhome-py](https://github.com/jenreh/fritzhome-py) - AVM Fritz Home (currently thermostates only).

All integrations support **CLI** and **MCP** and are easily integratable into e.g. Claude Code or other LLM Clients that support local MCP servers and skills.

#### Project Templates

- [python-kit](https://github.com/jenreh/python-kit) - for "pure" Python project, pre-configured for Claude and Github Copilot with usefull Skills and MCP servers
- [project-kit](https://github.com/jenreh/project-kit) - template for developing with Appkit.
