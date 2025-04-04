# terraform-dynamic

Welcome to the terraform-dynamic backend plugin!

_This plugin was created through the Backstage CLI_

## Getting started

Your plugin has been added to the example app in this repository, meaning you'll be able to access it by running `yarn
start` in the root directory, and then navigating to [/terraform-dynamic/health](http://localhost:7007/api/terraform-dynamic/health).

You can also serve the plugin in isolation by running `yarn start` in the plugin directory.
This method of serving the plugin provides quicker iteration speed and a faster startup and hot reloads.
It is only meant for local development, and the setup for it can be found inside the [/dev](./dev) directory.

## Compile for Dynamic plugin
```
      yarn tsc
      yarn build
      yarn export-dynamic
```
### Packing and  Getting SHA Integrity

      ```
            npm pack --json > ./npminfo.json 
      ``` 
After we execute this command the file `npminfo.json` will have integrity : SHA         

### Publish the plugin

      ```
            npm publish
      ```