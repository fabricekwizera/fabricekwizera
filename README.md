### Short bio 😄

```python

class Kwizera:
    def __init__(self):
        self.other_name = 'Papa Mickaël'
        self.work = 'Software Engineer'
        self.home_country = 'Rwanda'
        self.local_time = 'GMT+2'

    def __repr__(self):
        return 'I am also called {}, I am a {} living in {} ({})'. \
            format(self.other_name, self.work, self.home_country,
                   self.local_time)
