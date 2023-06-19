# Known LED panel configurations

## Daisy chaining or parallel connection?

For 64x32 panels, daisy-chaining is recommended. For 128x64 display, you might try both parallel and daisy-chaining. Parallel connection can slighty reduce the CPU load. This might be helpful in some situations when you see stuttering.
In general, expect a high CPU load on one core when rendering 256x64 pixel resolution. You should not even try this with an old single-core Pi (e.g. Pi Zero).

## Two 64x32 P2.5 panels daisy-chained on LED connector 1

```
rows = 32
cols = 128
```

## Two 128x64 P2 panels daisy-chained on LED connector 1

```
rows = 64
cols = 256
```

## Two 128x64 P2 panels parallel connection to LED connector 1 and 2

```
rows = 64
cols = 128
parallel = 2
pixel-mapper = V-Mapper
```


