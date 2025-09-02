# WSC-bot

An educational Discord bot that combines the World Spider Catalog and iNaturalist APIs to create an enriched learning experience about some of Earth's most misunderstood creatures.

## 🕷️ Features

- **Species Information**: Get detailed data from the World Spider Catalog
- **Visual Learning**: Enhanced with iNaturalist imagery and observations
- **Educational Focus**: Designed to promote understanding and appreciation of arachnids for researchers and enthusiasts
- **Community Driven**: Expandable alias system for easy species lookup and a user-friendly experience

## 🚀 Getting Started

### Official Bot Server
Join the [Tarantula Addicts](https://discord.gg/ta) Discord server to see the bot in action or add it to your own server.

### Development Status
⚠️ **Code is currently under development** and will be released under the MIT license once ready.

## Contributing

While the main code is still in development, you can contribute by adding species aliases to improve the bot's User Experience.

### Syntax

```json
{
  "alias": {
    "lsid": "urn:lsid:nmbe.ch:spidersp:#",
    "canonical": "Genus species"
  },
  "pmet": {
    "lsid": "urn:lsid:nmbe.ch:spidersp:002352",
    "canonical": "Poecilotheria metallica"
  }
}
```

## 📚 Resources

[WSC Data Resources](https://wsc.nmbe.ch/dataresources)
- API documentation and CSV with LSIDs.

[iNaturalist](https://api.inaturalist.org/v1/docs/)
- API documentation.
