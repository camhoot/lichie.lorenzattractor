# lichie.lorenzattractor

### Standalone Chaotic Lorenz Attractor built in gen~ and MaxMSP 

![image](https://user-images.githubusercontent.com/77128423/124222029-d5e17800-daf8-11eb-84be-57e05103cb75.png)

A chaotic modulation source for synthesizers
standalone version of the attractor found in my granular synth patch. This tool will be maintained and improved via this repository.

## Details

Based on three linear equations: 

```
dx = a * (y - x) * dt
dy = (x * (b - z)) - y * dt
dz = (x * y) - (z * c) * dt
```

There is control over variables a, b and c and the speed of the attractor. Small changes to these values produces vastly different results. 

*The patch only displays the dx and dy on the [scope~] object however, all three outputs are available as modulation sources.*

![image](https://user-images.githubusercontent.com/77128423/124315289-a750b500-db6b-11eb-8124-d03efdcc8985.png)

![image](https://user-images.githubusercontent.com/77128423/124221437-b269fd80-daf7-11eb-9866-a40718998b69.png)

