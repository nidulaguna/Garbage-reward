# Garbage-reward

## Check the node mcu file to get the code for node mcu
 also in there two parts to upload to the database and read from data base
 put them in the place where you want in your code

This ensures whether device is connected to wifi or not

```
    if (WiFi.status() != WL_CONNECTED) {
      WiFiManager wifiManager;

      wifiManager.autoConnect("Garbage Reward");

      Serial.println("connected :)");
      wifiManager.setBreakAfterConfig(true);
    }
```
in these places assign the mobile and the reward need to be added
```
    String mobile = "0778482017";  // Enter mobile number here
    float reward = 150.50;         // enter reward here
```

 ### **Put the setup and other libraries and defined codes as it is.**