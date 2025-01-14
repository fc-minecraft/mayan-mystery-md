### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Navigate the Maze

## Step 1
Navigate the maze using the map unlocked by the beam of light.

#### ~ tutorialhint
Use the projected map to plan your route and use the ``||agent.move||`` navigate the Agent through it.


```ghost
    agent.move()
    agent.destroy()
```
```template
    agent.destroy(UP)
    agent.move(LEFT, 1)
    agent.destroy(FORWARD)
```

```package
\\
```