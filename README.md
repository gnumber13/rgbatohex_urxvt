# rgbatohex_urxvt
A table of values for your URxvt config file using the rgba option wich enables the alpha channel for tranparency.

from https://ctkarch.org/documentation/tutorials/tuto.php?page=urxvt-transpa.xml

#### you can configure:

I asume bit depth:
`URxvt*depth: 32`
Background color:
`URxvt*background: rgba:"hex value red"/"hex value green"/"hex value blue"/"hexvalue tranparency"`

#### Example:

  CSS/HEX Color for a grey background(from the nord color palett): `#2E3440`

   -> Converted into rgb (use any css/hex to rgb online converter): `rgb(46,52,64)`

  Choose your transparency level, for example: 0.9 or 90%

From the table you can read the transparency level in 5% increments.

  0.9 or 90% => E665

From the table you can read the RGB values from 0 to 255

  R: 46 => 2E2E

  G: 52 => 3434

  B: 64 => 4040

Which results in:

  `rgba:2E2E/3434/4040/E665`
  
In your .Xdefaults config file:

  `URxvt*background: rgba:2E2E/3434/4040/E665`
