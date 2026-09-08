# Network-Scanner-Basic-
It is a high-performance, concurrent (asynchronous) network scanning tool developed using Python's asyncio library and Scapy, designed to detect active devices on a local area network (LAN) and the open ports on those devices.


## ⚙️ Configuration and Customization

For security and privacy reasons, no specific network address has been left as a default in the code. Before running the script, you must define your own local network within the code.

In the project's Python script, navigate to **line 77** inside the `main()` function and update the `target_network` variable to match your own network:

```python
async def main():
    # Enter your local network's IP address here:
    target_network = "Your ip address and /prefix simple ip = 192.168.1.121/24" # <-- Line 77: Set this according to your own network
```
