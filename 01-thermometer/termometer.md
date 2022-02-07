# mengkonversi semua suhu menjadi celcius

BEGIN
DECLARE type = "fahrenheit, kelvin, celcius"
DECLARE temp = "N" integer any value

INPUT type any
INPUT temp any

IF type = "fahrenheit"
    DO "convert = (temp - 32) * (5/9)"
    PRINT convert

ELSE IF type = "kelvin'
    DO "convert = (temp - 273.15)
    PRINT convert

ELSE
    PRINT temp
    PRINT type

END