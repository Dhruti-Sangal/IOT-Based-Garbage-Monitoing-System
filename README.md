
IOT based smart dustbin

Aim:
To Segregate the dust between dry and wet and notify the concerned authorities of
the dustbin, if’s full and give them the location of the dustbin via SMS so that they would
be able to locate it and replace it.


Working:
The main concept behind the IOT Based Smart Dustbin using Arduino project is
Object Detection. IOT Based Smart Dustbin it is an automatic dustbin, it works like when
you come in front of this dustbin it will open automatically with the help of a servo
motor. So, there is some sensor work to detect the object in front of the dustbin.
We have a top sensor so that it would be able to sense garbage/dust when it’s within
the range of 100cm, and accordingly it would be sent to Arduino so that the servo motor can
rotate and the lid would be opened accordingly. Then we have another top sensor so that we
would be able to increase the range from which the person can send the garbage/dustinside
the automatic dustbin. Then we have 2 sensors, so when the garbage would be inserted and
the lid would be closed the sensors would start to segregate the garbage into wet and dry
with the help of the soil moisture sensor, which would help in determining the amount of
water content that is present in the garbage inserted within the bin. The process of
segregation of waste starts only after the garbage has been inserted and the lid is closed,which gets displayed on the LCD as well. Then we use a GPS Sensor so that we would be able to tell us accurately the position of the bin which is full, so that it could be replaced by the
concerned authorities.
