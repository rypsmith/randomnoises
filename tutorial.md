# tutorial

## Step 1 - Sound block

Get a ``||music:play tone||`` block and place it inside of the ``||basic:forever||`` block.
    
```blocks
basic.forever(function() {
    music.playTone(Note.C, music.beat())
})
```

```ghost
music.playTone(Note.C, music.beat())
```

## Step 2 - Find the range

Click on the value (after ``||music:play tone||``) to check the number value for the highest pitch tone and the lowest pitch tone. Write each of these down.

![Find the high and low tone values](https://raw.githubusercontent.com/rypsmith/randomnoises/master/toneinfo.png)