# rinnai-control-panel-sigrok-pd

Sigrok Protocol Decoder for the internal protocol of a Rinnai gas heater control panel

Please also see https://github.com/ayavilevich/rinnai-wifi/ for an example of an ESP32 firmware that implements this protocol

![Decoder example](https://blog.yavilevich.com/wp-content/uploads/2020/08/Capture-packets-with-decoder.png "Decoder example")


-------
Sigrok is a portable, cross-platform, free open source signal analysis software suite  
https://sigrok.org/

PulseView is the UI for Sigrok  
https://sigrok.org/wiki/PulseView

Rinnai is a Japanese company making gas heaters and other equipment  
https://www.rinnai.us/

Rinnai makes various control panels for their devices  
https://www.google.com/search?q=rinnai+control+panel

For example  
https://www.alpinehomeair.com/viewproduct.cfm?productid=453059509

The control panel is wired over two wires which supply both power and data. This is known as Power Line Communication (PLC).

The decoder decodes the protocol between the MCU and the custom TI PLC chip in the control panel.
