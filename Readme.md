### Teme

Teme is a small program to send push messages to my telegram from anywhere.

````
pip install teme
````

usage:

```
python -m teme -m "hello"
```

This will send me a message on my telegram

you can also send message to yourself using another token..

````
python -m teme -m "hello" -t <your-token-here>
````

To use inside script:
````
import teme

teme.send_message("hello", token="<your-token-here>")
````
Resource: https://fopina.github.io/tgbot-pushitbot/#api-docs

