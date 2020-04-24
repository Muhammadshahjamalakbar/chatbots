## intent:greet
- AOA
- Assalamualaikum
- hi
- good morning
- good evening
- hey there

## intent:goodbye
- bye
- goodbye
- see you around
- see you later

## intent:inform
- [Sitka](location)
- [Janeau](location)
- [Virginia](location)
- [Cusseta](location)
- [Chicago](location)
- [nursing home](facility_type)

## intent:search_provider
- tell me the [hospital](facility_type) in [San francisco](location)
- i need a [hospital](facility_type:xubh-q36u)
- show me [hospitals](facility_type:xubh-q36u)
- find a nearby[hospital] my zip code is [10119](location)
- i need a [hospital](facility_type) my zip code is [77494](location)
- hi i am in [Chicago](location) i need a [nursing home](facility_type:b27b-2uc7)
- hi i am in [Chicago](location) i need a [nursing house](facility_type:b27b-2uc7)
- find a nearby ho

## intent:affirm
- yes
- indeed
- of course
- that sounds good
- correct

## intent:deny
- no
- never
- I don't think so
- don't like that
- no way
- not really

## intent:mood_great
- perfect
- very good
- great
- amazing
- wonderful
- I am feeling very good
- I am great
- I'm good

## intent:mood_unhappy
- sad
- very sad
- unhappy
- bad
- very bad
- awful
- terrible
- not very good
- extremely sad
- so sad

## intent:bot_challenge
- are you a bot?
- are you a human?
- am I talking to a bot?
- am I talking to a human?

## regex:location
- [0-9]{5}

## synonym:b27b-2uc7
- nursing home
- nursing house

## synonym:xubh-q36u
- hospital
- hospitals