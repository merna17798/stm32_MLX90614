# stm32_MLX90614
## Last meeting, we told you that we have issue in understanding part of hal function in i2c protocol.
* In that function, when we recieve data we check if it was 1 or 2 or 3 byte and we don't understande the way we recieve 3 bytes
> Code line starts at 1331 to 1405 in t/drivers/Src/stm32f1xx_hal_i2c.c


![4](/imgs/4.jpg)

## We tried to connect mlx90614 with stm32 but we face some issues. we try to debug our code and found ourselves stuck at HAL_Init(). we try to but counter to further clarification and found our counter only increments once then stuck. there are too little resources for dealing with that sensor so if you know how to solve our problem we will be glad. 
> Code in t/Core/Src/main.c (you will check main function). you will also need to check t/drivers/Src/stm32f1xx_hal.c for HAL_Init function.
## Where we stuck
![1](imgs/1.jpg)
## brief of HAL_Init()
![2](imgs/2.jpg)
## HAL_Init() 
![3](imgs/3.jpg)
