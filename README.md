# TB6612FNG MotorDriver

## Description:
An DC motor driver made with the TB6612FNG driver IC. It contains an adittional optional MT3608 voltage boost-up converter to boost the battery voltage higher for the mottors.
If all the components are solldered, you can chose between the battery boltage and the boosted voltage by making the wanted solder bridge.
To choose the output voltage, the board has 2 additional DNP resistor pads used for an larger reach of precise voltages.

> [!CAUTION]
> By connecting all 3 pads of the solder bridge, the input and the output of the boost-up converter are connected, witch is not recommended and may have an unexpected outcome including the IC being unusable.

<table>
  <tr>
    <td><img src="https://github.com/Tonikiller10000/MotorDriver_1/blob/main/LineFollowerDriver_Pictures/u2.png" ></td>
    <td><img src="https://github.com/Tonikiller10000/MotorDriver_1/blob/main/LineFollowerDriver_Pictures/f1.png" ></td>
    <td><img src="https://github.com/Tonikiller10000/MotorDriver_1/blob/main/LineFollowerDriver_Pictures/b1.png" ></td>
  </tr>
</table>

### Board Schematic:
<img src="https://github.com/Tonikiller10000/MotorDriver_1/blob/main/LineFollowerDriver_Pictures/ss.png" >

## The motor driver without VBC:
<table>
  <tr>
    <td><img src="https://github.com/Tonikiller10000/MotorDriver_1/blob/main/LineFollowerDriver_Pictures/b1.png" ></td>
    <td><img src="https://github.com/Tonikiller10000/MotorDriver_1/blob/main/LineFollowerDriver_Pictures/b2.png" ></td>
    <td><img src="https://github.com/Tonikiller10000/MotorDriver_1/blob/main/LineFollowerDriver_Pictures/ppp.png" ></td>
  </tr>
</table>

### Links: 
- TB6612FNG (Motor driver): https://www.alldatasheet.com/datasheet-pdf/pdf/807693/TOSHIBA/TB6612FNG.html
- MT3608 (BoostUp voltage converter): https://pdf1.alldatasheet.com/datasheet-pdf/view/1131968/ETC1/MT3608.html
- Driver schematic: https://github.com/Tonikiller10000/MotorDriver_1/blob/main/LineFollowerDriver_Pictures/d1.jpg
- Schematic (no VBC): https://github.com/Tonikiller10000/MotorDriver_1/blob/main/LineFollowerDriver_Pictures/sss.png



