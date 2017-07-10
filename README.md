TimeScheduler
=============

Many thank to Zallist
A simple JavaScript Timeline Scheduler library
[Go here for a live demo using the latest version](http://quannda.github.io/TimeScheduler/Calendar.html)


TimeScheduler Init Options
============

| Option   |      Type      |  Default |Description |
|----------|:-------------|:------:|------:|
| Start |  Moment object || Begin of time sheduler |
| Periods |    object array   ||    |
| Element | jQuery object ||    Container to render |
| SelectedPeriod | string ||    Default period |
| AllowDragging | boolean |false|     |
| AllowResizing | boolean |false|     |
| MaxHeight | int | null |     |
|  | ||     |
| Events | object |null| Define array of listeners, see detail below |
| GetSchedule | function ||     |


TimeScheduler Init Event Options
==

| Option   |      Type      |  Default |Description |
|----------|:-------------|------:|------:|
| ItemClicked | function ||     |
| ItemDropped | function ||     |
| ItemResized | function ||     |
| ItemMovement | function ||     |
| ItemMovementStart | function ||     |
| ItemMovementEnd | function ||     |


License
==

The library is made available under the MIT license. 
http://en.m.wikipedia.org/wiki/MIT_License