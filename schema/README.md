This repository contains JSON-Schema definitions for all of the IPC messages
sent between the WebThings Gateway and add-ons.

**WARNING**: this is an actual copy of:
    - repo: https://github.com/WebThingsIO/gateway-addon-ipc-schema.git schema
    - version: v0.12.0
    - **MAKE SURE THE SCHEMA VERSION IS IN SYNC WITH THIS RPMA REPO'S (`GATEWAY-ADDON-NODE`) VERSION**

> NOTE: previosly `schema` was a git module, but we're trying to use `yarn` instead of `npm` (firmware build time down from 85m to 40minutes) and `yarn` has known issues with git modules.