### A normal week day 😄


```python
from datetime import datetime


class Kwizera:
    def __init__(self):
        self.other_name = 'Papa Mickaël'
        self.work = 'Software Engineer'
        self.home_country = 'Rwanda'
        self.local_time = 'GMT+2'

    def __repr__(self):
        return '{} is a {}. At the moment, he is doing the following: "{}"'. \
            format(self.other_name, self.work, live())


def live():
    start, current, end = 7, datetime.now().hour, 23
    if current < start:
        raise NotImplementedError
    elif start < current < 17:
        return 'Code <-> Meeting <-> StackOverflow <-> YouTube <-> Hydrate and eat...'
    elif 17 <= current < 19:
        return 'Cardiovascular exercise'
    elif 19 <= current < end:
        return 'Family time'
