# TCP vs UDP

## TCP (Transmission Control Protocol)

### Characteristics
- Connection-oriented
- Reliable
- Error checking
- Ordered delivery

### Common Uses
- Web browsing (HTTP/HTTPS)
- Email
- File transfers

### Advantages
- Reliable delivery
- Data arrives in order

### Disadvantages
- Slower than UDP

---

## UDP (User Datagram Protocol)

### Characteristics
- Connectionless
- Faster
- No guaranteed delivery
- No packet ordering

### Common Uses
- Video streaming
- Online gaming
- VoIP

### Advantages
- Low latency
- Fast

### Disadvantages
- Packets may be lost

---

## Interview Question

When would you choose TCP over UDP?

TCP is preferred when reliability is more important than speed, such as file transfers and web traffic.

UDP is preferred when speed is more important than perfect delivery, such as streaming and gaming.

## Quick Memory Trick

TCP = Accuracy

- Reliable
  
- Ordered
  
- Error checking

UDP = Speed

- Faster
  
- Lower latency
  
- Some packets can be lost
