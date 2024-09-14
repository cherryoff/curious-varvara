## Curious Varvara

Tiny package to check website availability

### Installation

```bash
pip install curious-varvara
```

### Usage

```python
from curious_varvara import is_live, body_md5

url = 'https://www.google.com'

is_live(url) # returns True if website is available, False otherwise

body_md5(url) # returns md5 hash of website body
```
