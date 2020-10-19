# Home-Automation
# Code for BoltIoT

<!DOCTYPE html>
<html>
    <head>
        <title>Home Automation</title>
        <script type="text/javascript" src="https://cloud.boltiot.com/static/js/boltCommands.js"></script>
        <script>

        setKey('{{ApiKey}}','{{Name}}');

        </script>
    </head>
    <body>
        <center>

        <button onclick="digitalWrite(1, 'LOW');">LED 1 ON</button>
        <button onclick="digitalWrite(1, 'HIGH');">LED 1 OFF</button>  <br><br>        
        
        <button onclick="digitalWrite(2, 'LOW');">LED 2 ON</button>
        <button onclick="digitalWrite(2, 'HIGH');">LED 2 OFF</button>  <br><br> 
        
        <button onclick="digitalWrite(3, 'LOW');">FAN ON</button>
        <button onclick="digitalWrite(3, 'HIGH');">FAN OFF</button>  <br><br>        
        
        <button onclick="digitalWrite(4, 'LOW');">PLUG ON</button>
        <button onclick="digitalWrite(4, 'HIGH');">PLUG OFF</button>  <br><br>
        
        </center>
    </body>
</html>
