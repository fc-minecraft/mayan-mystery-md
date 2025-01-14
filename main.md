### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Navigate the Maze

## Step 1
Use the projected map to plan your route and use the ``||mayanMystery:agent move||`` block to navigate the Agent through it.

#### ~ tutorialhint
You won't be able to see the Agent after it enters the maze, so make sure to watch the projected map while your code is running.


```ghost
    mayanMystery.agent_move()
```
```template
    mayanMystery.agent_move(Three_Axis.Forward, 2)
    mayanMystery.agent_move(Three_Axis.Right, 3)
```

```package
mayan-mystery-ts=github:ReWrite-Media/mayan-mystery-ts
```