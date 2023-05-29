# initialization test
## setup
Connected 
```mermaid
flowchart LR
  b004 --> b093 
  b093 --> r[100R between pinns 1 and 10 of J2]
  
```
## results
initialization works on a standard PoE switch.


# current test
## setup
Connected
```mermaid
flowchart LR
  b004 --> b093 
  b093 --> r[ariable resistor between pinns 1 and 10 of J2]
  
```
## results
| current | voltage |
|--|--|
|500mA|5V|
|1A|5V|
|1.4A|5V|

