# Usage tips
When using settings specific to a project, we can use `WORKSPACE SETTINGS` instead
of `USER SETTINGS`.

## 1. Debug with arguments

- Use sys.args
```
import sys
sys.args.append('args')
```
or
```
sys.args.extend(['args1', 'args2'])
```
- Set launch configurations

Add [`args`](./settings.json#L56) to `configurations` of `launch`:
```
"args": [
  "args1",
  "args2",
  ...
],
```
## 2. Debug with PYTHON environments

Add [`env`](./settings.json#L73) to `configurations` of `launch`:
```
"env": {
  "PYTHONPATH": "~/caffe2/build:~/caffe2"
},
```
