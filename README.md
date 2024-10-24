# nginx-adventure

Going through nginx capabilities.

## Usage of web servers broken down by ranking

Nginx is the #1 web server at the 100,000 busiest websites in the world.

https://w3techs.com/technologies/cross/web_server/ranking

## Capabilities

- serve static files
- reverse proxy
- load balancing

```
Nginx is a powerful web server and reverse proxy that offers a wide range of capabilities, including:

1. **Load Balancing**: Distributes incoming traffic across multiple servers to ensure reliability and performance. Supports various algorithms like round-robin, least connections, and IP hash.

2. **Reverse Proxy**: Acts as an intermediary for requests from clients seeking resources from servers, enhancing security and performance.

3. **SSL/TLS Termination**: Handles SSL encryption and decryption, offloading this resource-intensive task from backend servers.

4. **Caching**: Improves response times and reduces server load by caching static content and proxying dynamic content.

5. **Content Compression**: Uses gzip and Brotli compression to reduce the size of responses, improving load times and bandwidth usage.

6. **Static File Serving**: Efficiently serves static content like images, CSS, and JavaScript files.

7. **WebSocket Support**: Facilitates real-time communication by supporting WebSocket protocols.

8. **URL Rewriting and Redirection**: Provides flexible URL manipulation and redirection capabilities.

9. **Security Features**: Includes features like access control, rate limiting, and support for various authentication methods.

10. **HTTP/2 and HTTP/3 Support**: Supports modern protocols for improved performance and resource loading.

11. **Monitoring and Logging**: Provides extensive logging capabilities and integration with monitoring tools for performance analysis.

12. **Microservices Support**: Works well in microservices architectures by managing service communication and load balancing.

13. **API Gateway Functionality**: Can act as an API gateway, managing and routing API requests effectively.

14. **GeoIP Support**: Allows geolocation-based routing and content delivery.

15. **Dynamic Module Support**: Offers the ability to extend functionality with custom modules.

These capabilities make Nginx a versatile choice for handling a wide range of web traffic and application architectures.
```
