# QuickInterfaces

### This is currently a WIP(work in progress). Feel free to contribute.

### Motivation
"Hey man I need you to tap out this interface (some model/entity/class/some arbitrary schema)." First get the schema then convert it in some slow, by hand, copy/pasta way etc. Then triple check that you didn't miss any required field or accidentally make an int a string or some other super simple mistake that will happen, don't just give up an put ?: any. Like any reasonable coder, I prefer to keep my workflow at the speed of done with no work at all and still have all my types.

I have more important things to do than grind through boilerplate over and over only to later find out that it was the wrong model(chosen from thousands in a legacy system) to use in the first place. Or perhaps someone changes that same model 6 times this week and I have to parse it all 20 times to make sure the changes are corrected correctly. No more! Just point the config at your api, and spin her up. Convert all the things!

### Description
This is a WIP(work in progress) for getting JSON from your predefined access layers with a simple bash command and generating tedious TS interfaces.

Quick Tsc (Typescript) Interfaces from your chosen data source. Tell the config where to point, and from now on just spin up the cli and tell her which model you want. For now this accepts JSON, but in the future will accept many different schemas.

## Roadmap:

### supported schemas

- [x] json
- [ ] .NET classes
- [ ] .NET models
- [ ] xml
- [ ] SQL schemas

