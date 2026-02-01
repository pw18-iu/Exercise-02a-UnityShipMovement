# Exercise-02a-Ship

Exercise for MSCH-C220

A user-controlled ship for a space-shooter game. Created in Unity.

## Implementation
The tutorial video don't provide the specific input rules for key S. I try to copye the events/boxes from key W and then modifying them for S. I change "currentSpeed ​​+ (accelPerSecond * deltaTime)" to "currentSpeed ​​- (accelPerSecond * deltaTime)". I also change "clamp.min" to "-maxSpeed". And I disconnect the "if.false" of both key W and key Y, if not do that, it cannot work. 

## References
- https://www.youtube.com/watch?v=bOhIdLjlsYk
- https://www.youtube.com/watch?v=_RTKPxrNo5o

## Future Development
The first attempt is interesting, but also complex. In the future, I will try to translate these events into sentences or formulas that I can understand, otherwise, just looking at the images made it difficult for me to understand what's these chains and events do.

## Created by
Peiwen Wanf