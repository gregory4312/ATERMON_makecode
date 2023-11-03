# Activate the Radio Tower
### @hideIteration false 
### @flyoutOnly 1


``` ghost
    count = 0
    for (let index = 0; index < 4; index++) {
        agent.move(FORWARD, 1)
        agent.turn(RIGHT_TURN)
    }
```



## Step 1

Let's gather some more materials. In order to make our lives easier, you can have the agent perform an activity on repeat. Study the walk pattern and then have the agent gather all the materials in one go.

### ~ Hint 
Use a ``||loops: repeat||`` loop

```  blocks
        for (let index = 0; index < 4; index++) {
        agent.move(FORWARD, 4)
        agent.turn(RIGHT_TURN)
    }
         
})
```


