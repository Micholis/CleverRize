# Rize
Clever Ev3  Framework

This framework adding a lot of aditional functoins

##Get started
Download [Rize framework](rize.bpi)

Include framework to you project
`include "rize"`

##Docs
###Settings
Framework functions have basic sattings

`CONST_LINE_SENSOR_1_PORT`
`CONST_LINE_SENSOR_2_PORT`
`CONST_COLOR_SENSOR_PORT`
`CONST_ADITIONAL_MOTOR_PORT`

`CONST_LINE_PID_P_COEFFICIENT`
`CONST_LINE_PID_I_COEFFICIENT`
`CONST_LINE_PID_D_COEFFICIENT`
`CONST_LINE_POWER`
`CONST_LINE_CROSS_THRESHOLD`

`CONST_COLOR_RECOGNITION_SPREAD`
`CONST_COLOR_RECOGNITION_RED_VALUE`
`CONST_COLOR_RECOGNITION_YELLOW_VALUE`
`CONST_COLOR_RECOGNITION_GREEN_VALUE`
`CONST_COLOR_RECOGNITION_BLUE_VALUE`

`CONST_CENTIMETRES_MULTIPLIER`
`CONST_MOVE_POWER`
`CONST_MOVE_TURN`
`CONST_ROTATE_POWER`
`CONST_ROTATE_ANGLE`

`CONST_LEVEL_POWER`
`CONST_LEVEL_TIME`
`CONST_LEVEL_DISTANCE`

`CONST_ADITIONAL_MOTOR_POWER`

###Moving
####`Level()`
Aligns the robot from the wall

####`Forward(in number cm)`
Moves forward a robot for `cm` santimetres

####`Backward(in number cm)`
Moves Backward a robot for `cm` santimetres

###Rotating
####`Left()`
Turns a robot left

####`Right()`
Turns a robot right

####`Reversal()`
Turns a robot around
