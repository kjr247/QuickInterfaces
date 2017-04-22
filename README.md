# QuickInterfaces

### This is currently a WIP(work in progress). Feel free to contribute.

### Motivation
Hey man I need you to tap out this interface based on this model/entity/class/some arbitrary schema.
It won't take that long(2 - 20 mins is not long for some people). First get the schema then convert it in some crappy copy/pasta way etc. Then double triple check that you didn't miss a required field or accidentally make an int a string or some other super simple mistake that will happen. Like any reasonable coder, I prefer to keep my workflow at the speed of done with no work at all.

I have more important things to do than grinding through boilerplate only to later find out that it was the wrong model(chosen from thousands in a legacy system) to use in the first place. Or perhaps someone changes that same model 6 times this week and I have to parse it all 20 times to make sure the changes are corrected correctly.

### Description
This is a WIP(work in progress) for getting JSON from predefined access layers with a simple bash command and generating tedious TS interfaces.

Quick Tsc (Typescript) Interfaces from your chosen data source. Tell the config where to point, and from now on just spin up the cli and tell her which model you want. For now this accepts JSON, but in the future will accept many different schemas.

## Roadmap:

### supported schemas
    - [x] json yup
    - [ ] .NET classes not yet
    - [ ] .NET models not yet
    - [ ] xml not yet
    - [ ] SQL schemas not yet

