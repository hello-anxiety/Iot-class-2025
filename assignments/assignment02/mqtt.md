# Exploring MQTT QoS Levels

Experiment with QoS 0, 1, and 2.
Observe how message delivery changes based on QoS settings.

## Publisher_qos.py output

```
(.venv) PS C:\Users\pitpi\Desktop\Iot-class-2025-gateway> & C:/Users/pitpi/Desktop/Iot-class-2025-gateway/.venv/Scripts/python.exe c:/Users/pitpi/Desktop/Iot-class-2025-gateway/app/publisher_qos.py
c:\Users\pitpi\Desktop\Iot-class-2025-gateway\app\publisher_qos.py:20: DeprecationWarning: Callback API version 1 is deprecated, update to latest version
  client = mqtt.Client()
[14:57:29] DEBUG | Sending CONNECT (u0, p0, wr0, wq0, wf0, c1, k60) client_id=b''
Enter message to publish: [14:57:29] DEBUG | Received CONNACK (0, 0)
hello
Enter QoS level (0, 1, 2): 2
[14:57:35] DEBUG | Sending PUBLISH (d0, q2, r0, m1), 'b'test/qos/6510301016/temperature'', ... (5 bytes)
[14:57:35] PUBLISH REQUESTED | QoS=2 | Message='hello' | msgid=1
Enter message to publish: [14:57:35] DEBUG | Received PUBREC (Mid: 1)
[14:57:35] DEBUG | Sending PUBREL (Mid: 1)
[14:57:35] DEBUG | Received PUBCOMP (Mid: 1)
[14:57:35] PUBLISHED | msgid=1
```

## Subscriber_qos.py Output

```
[14:50:41] DEBUG | Sending CONNECT (u0, p0, wr0, wq0, wf0, c1, k60) client_id=b''
[14:50:41] DEBUG | Received CONNACK (0, 0)
[14:50:41] Connected with result code 0
[14:50:41] DEBUG | Sending SUBSCRIBE (d0, m1) [(b'test/qos/6510301016', 2)]
[14:50:41] DEBUG | Received SUBACK
```