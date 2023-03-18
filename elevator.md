## Diyagram
```
+--------------+       +--------------+
|    Building  |       |     Elevator |
+--------------+       +--------------+
| -num_floors  |       | -capacity    |
| -num_elevators |     | -current_floor|
| -elevators   |       | -destination_floor|
| -call_buttons|       | -door_open   |
+--------------+       | -direction  |
                        +--------------+
                        | +move()     |
                        | +open_door()|
                        | +close_door()|
                        +--------------+

+--------------+        +--------------+
|     Floor    |        |  CallButton  |
+--------------+        +--------------+
| -floor_number|     v  | -direction  |
| -elevator_doors |     | -is_lit     |
| -arrival_lights |     | +press()    |
| -up_button    |       |              |
| -down_button  |       |              |
+--------------+       +--------------+
                       


```