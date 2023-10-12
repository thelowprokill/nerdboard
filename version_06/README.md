# Version 6

## Introduction
This is the sixth version of the project and first to de shared with others.
This is a 29 key split keyboard with integrated trackball.

## Hardware
29 diodes
29 switches
29 hot swap sockets
29 keycaps
2  arduino pro micros
2  female usb cables
1  usb c female to micro usb adapter
6  m2x8 screws
14 m3x6 screws
2  m2 thraded inserts
14 m3 thraded inserts
1  PMW 3360 sensor
1  34mm trackball
1  usb c male to usb c male cable
1  usb c male to computer
   jumper cables

## Build
### Print
Print all the parts.
1x left
1x right
1x small_parts

either
1x upper_plate_l
1x upper_plate_r
1x lower_plate_l
1x lower_plate_r
2x kickstand
for the tented version
or
2x plate
for the non-tented version

all the small parts print together.

Remove the supports

### Post proccessing
sand and paint as desired (optional, but recommended)
Install heat inserts into the cases and palm rests.

### Assembly
Diodes:
Solder diodes to the hot swap sockets not the polarity.
One diode per socket.
I try to make the diodes all on the same side of the column.
For one of the rows it will be on the other side.

Sockets:
Insert a socket into each hole in the keyboard.
I recomend using a switch to help hold the socket in place.

Rows:
Start at one end and solder the tail of that diode to the tail of the next diode.
This needs to be done after the diode not before.

Columns:
Use a jumper cable.
Cut off one side.
Use wire strippers to cut the shielding near the uncut side of the jumper cable.
Hold the cut up to one of the sockets I start at the top row.
Mark where it meets the next socket.
Cut the shielding there.
When you get to all the sockets in that column pull the shielding away to reveal about 5mm of the wire underneeth.
Cut the extra wire.
Cut the other side of the jumper cable.
Tin all the joints with the soldering iron.
Solder each wire to the sockets.

USB C link between keyboard halves:
Cut the usb c female cable.
Solder a jumper to VCC(red), GND(black), and Data +-(green white).
To clerify I soldered green and white together to the third jumer.

Insert the usb c female side into the prited case.
I use the hole that is closest to the other side.

USB link from keyboard to computer:
Insert the usb c to micro usb adapter into the other hole in the case.

OLED:
Verify the OLED is working by connecting to the pro micro and plugging the pro micro into a computer.
Remove the film frm the OLED screen.
Attach 4 jumper cables to the OLED note which one goes where.
Gently place the OLED in the hole in the right side of the keyboard.
Hot glue in place.

Pro Micros:
Flash the firmware on the pro micro.
Go to QMK for instructions.
Solder header pins to the pro micro.

Hot glue the pro micro to the table like stand. (Optional but recommended)
Plug in the pro micro to the adapter in the case.
Run wires for the rows or columns that go to the other side of the pro micro accross the keyboard. (Optional but recommended)
Hot glue the four corners of the table.
Place the pro micro table in the case stadleing the wires lain across the keyboard. (It is hard to get them under once the pro micro is glued down)

Matrix:
solder one jumper to each row and one to each column.
Connect to the pro micro using the wiring diagram.

Mouse sensor:
Solder the headers onto the PMW 3360 sensor.
Use two m2x8 screws to attach the sensor to the case.
Connect to the pro micro using the wiring diagram.
