# Make some Random Noises

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

## Step 3 - Randomize the tones

Now insert a ``||math:random||`` block into the ``||music:play tone||`` block. For the first value, enter the lowest tone value and the second is the highest tone value.

```blocks
basic.forever(function() {
    music.playTone(randint(131, 988), music.beat(BeatFraction.Whole))
})
```

```ghost
math.random(0,0)
```

## Step 4 - Tinker!

Play with your code! Adjust the ranges, play with the fraction that the beat is played for.

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>