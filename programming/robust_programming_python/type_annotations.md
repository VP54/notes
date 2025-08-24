# Type Annotations

## What to consider
    - more specific types such as:
Example:
```python
from typing import Dict
import polars as pl


Tables: Dict[str, pl.DataFrame] = {}


def read_tables(paths: str) -> Tables:
    pass
```

## When to use
    - When longer scripts
    - When knowing that part of the code will have to be maintained

## Interesting types
    - defaultdict - dict with default value
    - Counter (from collections import Counter)
    - OrderedDict (dictionaries with ordered entries as they were added)
    - namedtuple (dictionary with values and name), immutable
