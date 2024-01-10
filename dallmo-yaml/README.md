# dallmo-yaml

- a simple yaml file reader
- re-written to base only on deno standard libraries

## dependencies

all of deno standard library.

- `Deno.readTextFile`
- https://deno.land/std/yaml


## usage

```
import { dallmo_yaml } from "[path to]/mod.ts";

const config_file = "config.yaml";
const config_obj = await dallmo_yaml( config_file );
  console.log( config_obj );
```

## test
to run test codes : 

1. switch to the folder "test" ; 
1. run `deno test --allow-read` ; 
