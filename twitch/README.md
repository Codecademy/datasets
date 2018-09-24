# Codecademy + Twitch

https://www.codecademy.com/courses/dspath-twitch/articles/twitch-project

[Twitch.tv](www.twitch.tv) is the world's leading video platform and community where millions of people and thousands of interests collide in a beautiful explosion of video games, pop culture, and conversation.

In the Data Science Path Cumulative Project, we have partnered with the [Twitch Science Team](https://science.twitch.tv/) and we were given two related tables that describe user engagmeent with Twitch video and Twitch chat on January 1st, 2015:

- [x] [`stream.csv`](stream.csv)  
- [x] [`chat.csv`](chat.csv)  

The `stream.csv` has the following fields:

Headers | Description |
--- | --- |
`time` | (YYYY-MM-DD HH:MM:SS)
`device_id` | device ID (scrubbed)
`login` | login ID (scrubbed)
`channel` | streamer name
`country` | country name
`player` | streamed device
`game` | game name
`stream_format` | stream quality
`subscriber` | is the viewer a subscriber? (true/false)

The `chat.csv` has the following fields:

Headers | Description |
--- | --- |
`time` | rental ID
`device_id` | building ID
`login` | price of rent ($)
`channel` | number of bedrooms
`country` | number of bathrooms
`player` | size (ft²)
`game` | subway station (min)
`stream_format` | floor number
`subscriber` | building age (year)

---

Thank you Twitch Science Team for this partnership and especially:

- [June Dershewitz](https://twitter.com/jdersh), Head of Data Governance & Analytics, Twitch
- [Sharmeen Browarek](https://www.linkedin.com/in/sharmeenbrowarek/), Product Manager, Twitch
- [Carson Forter](https://twitter.com/carsonforter), Data Scientist, Twitch
