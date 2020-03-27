## intent:health_check_start
- start a health check
- log my health

## intent:health_check_mood
- [perfect](health_check_mood:happy)
- [very good](health_check_mood:happy)
- [great](health_check_mood:happy)
- [amazing](health_check_mood:happy)
- [wonderful](health_check_mood:happy)
- [I am feeling very good](health_check_mood:happy)
- [I am great](health_check_mood:happy)
- [I'm good](health_check_mood:happy)
- [sad](health_check_mood:unhappy)
- [very sad](health_check_mood:unhappy)
- [unhappy](health_check_mood:unhappy)
- [bad](health_check_mood:unhappy)
- [very bad](health_check_mood:unhappy)
- [awful](health_check_mood:unhappy)
- [terrible](health_check_mood:unhappy)
- [not very good](health_check_mood:unhappy)
- [extremely sad](health_check_mood:unhappy)
- [so sad](health_check_mood:unhappy)
- [i feel sad](health_check_mood:unhappy)
- [help me](health_check_mood:unhappy)

## intent:health_check_sleepyness
- [tired](health_check_sleepyness:sleepy)
- [weary](health_check_sleepyness:sleepy)
- [sleepy](health_check_sleepyness:sleepy)
- i am [tired](health_check_sleepyness:sleepy)
- [alert](health_check_sleepyness:alert)
- [awake](health_check_sleepyness:alert)
- i feel [fine](health_check_sleepyness:alert)

## intent:health_check_aches
- [i hurt](health_check_aches:yes)
- [everything aches](health_check_aches:yes)
- [i feel great](health_check_aches:no)
- [no problems](health_check_aches:no)

## intent:health_check_exercisetoday
- i went for a [run](health_check_exercisetoday)
- i took the [bike](health_check_exercisetoday) up the hill
- i went for a [bike](health_check_exercisetoday) ride
- i went for a [swim](health_check_exercisetoday)
- i went outside for a [walk](health_check_exercisetoday)






## intent:maths_add_numbers
- what is [1](number) plus [2](number)
- what is [1](number) plus [to](number:2)
- what is [1](number) plus [too](number:2)
- what is [1](number) plus [for](number:4)
- what is [1](number) plus [ate](number:8)
- what is [1](number) and [2](number)
- what is the sum of  [3](number) plus [4](number)
- what is the sum of  [6](number) and [5](number)
- add [7](number) to [7](number)
- add [9](number) and [8](number)
- add [7](number) and [2](number) together
- what is [1](number)  [-2](number)
- what is [1](number)  [minus 2](number:-2)
- what is [1](number)  [minus two](number:-2)
- what is [four](number:4) plus [4](number)
- add [five](number:5) and [seven point two](number:7.2)

## intent:maths_subtract_numbers
- what is [1](number) subtract [to](number:2)
- what is [1](number) subtract [too](number:2)
- what is [1](number) subtract [for](number:4)
- what is [1](number) subtract [ate](number:8)
- what is the difference between [1](number) and [2](number)
- what is the difference of  [3](number) minus [4](number)
- what is [6](number) subtract [5](number)
- what is [6](number) take away [5](number)

## intent:maths_multiply_numbers
- what is [1](number) multiplied by [to](number:2)
- what is [1](number) multiplied by [too](number:2)
- what is [1](number) multiplied by [for](number:4)
- what is [1](number) multiplied by [ate](number:8)
- what is [1](number) times [2](number)
- what is [1](number) multiplied by [2](number)
- what is the product of  [3](number) and [4](number)
- what is the multiplication of  [6](number) and [5](number)
- multiply [7](number) to [7](number)
- multiply [9](number) and [8](number)
- multiply [9](number) by [8](number)
- multiply [7](number) and [2](number) together

## intent:maths_divide_numbers
- what is [1](number) divided by [to](number:2)
- what is [1](number) divided by [too](number:2)
- what is [1](number) divided by [for](number:4)
- what is [1](number) divided by [ate](number:8)
- what is [1](number) divided by [2](number)
- what is [1](number) over [2](number)
- what is [1](number) divide [2](number)
- what is [1](number) division [2](number)
- divide [7](number) by [7](number)
- divide [7](number) [by three](number:3)
- divide [9](number) into [8](number)
- what is [five](number:5) divided [by two](number:2)

## intent:hello_world
- hello world
- hello to the world
- hi world
- hello australia
- hi oz

## intent:i_am_user
- i am [steve](username)
- my name is [fred](username)
- call me [jane](username)

## intent:greet
- hey
- hello
- hi
- good morning
- good evening
- hey there

## intent:goodbye
- bye
- goodbye
- see you around
- see you later

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
- i feel sad
- help me

## intent:bot_challenge
- are you a [bot](bottype)?
- are you a [human](bottype)?
- am I talking to a [bot](bottype)?
- am I talking to a [human](bottype)?
- are you a [robot](bottype)?
- am I talking to a [robot](bottype)?

## synonym:-2
- minus 2
- minus two

## synonym:2
- to
- too
- by two

## synonym:3
- by three

## synonym:4
- for

## synonym:5
- five

## synonym:8
- ate

## regex:number
- [0-9]*
