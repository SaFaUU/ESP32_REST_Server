
# ESP32 Rest Server

This IOT project was done for Placement Day using ESP32.


## API Reference

#### Get all items

```http
  GET Requests
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `/light/off` | `None` | Turns the Light Off|
| `/ac/on` | `None` | Turns the AC On|
| `/light/off` | `None` | Turns the Light Off|
| `/ac/on` | `None` | Turns the AC On|
| `/dust` | `JSON` | Reads the Dust Sensor data and Sends it in JSON|
| `/ledSense` | `JSON` | Reads the LDR data and Sends it in JSON|



## Installation

- Set the Board as ESP32 Dev Module.
- Install Arduino JSON Library from Arduino IDE

    
