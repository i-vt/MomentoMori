# MomentoMori
Tracker of time left or until a specific event (ex.: end of day/week/month/year/specific date/etc.)

## Usage
```
$ pip3 install tqdm
Successfully installed tqdm-4.66.4

$ python3 MomentoMori.py 



---------------------------------------------------------------------------

    ___  ___                           _         ___  ___           _ 
    |  \/  |                          | |        |  \/  |          (_)
    | .  . | ___  _ __ ___   ___ _ __ | |_ ___   | .  . | ___  _ __ _ 
    | |\/| |/ _ \| '_ ` _ \ / _ \ '_ \| __/ _ \  | |\/| |/ _ \| '__| |
    | |  | | (_) | | | | | |  __/ | | | || (_) | | |  | | (_) | |  | |
    \_|  |_/\___/|_| |_| |_|\___|_| |_|\__\___/  \_|  |_/\___/|_|  |_|
                                                                      
                                                                      

    [ Do not waste time, live and enjoy life now. ]


https://github.com/i-vt
---------------------------------------------------------------------------


Time left until the end of:

Day: █▌                                                   215/7440 [03:35/2:00:33]
```

Goals and milestones can be adjusted in the main section, by modifying the contents of the section below:
```
    banner()
    timers = {
        "Day": 60 * minutes_until_end_of_day(),
        #"Week": 60 * minutes_until_end_of_week(), 
        #"Month": 60 * minutes_until_end_of_month(),
        #"Year": 60 * minutes_until_end_of_year(),
        #"Your 90s": 60 * minutes_until_specific_date('2150-01-01 00:00:00'),
        #Don't forget to customize this for yourself :)

    }
```
