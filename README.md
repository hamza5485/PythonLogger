# Python Logger
Python logger for color encoded logs based on Scott Punshon's logger.js.

Colors are based on message severity

![looks like](./screenshot.jpeg "looks like")
## Usage
```python
from logger import Logger
import os

log = Logger(os.path.basename(__file__))
log.info("This is an info log")
log.warn("This is a warning log")
log.error("This is an error log")
log.success("This is a success message")

``` 
