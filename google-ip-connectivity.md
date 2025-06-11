# The activity that takes place after pressing **google.com**.

This activity goes through a process known an **DNS**
DNS- is the process of translating a website domain <mark>eg,. google.com</mark> into an ip address like (142.231.7.100),its like a phone book for the internet, connecting human-friendly names to numerical addresses.

![Alt text](./asset/DNS-lookup-process-.png)

### How it works:

#### 1. Your browser sends a request:
When you type a domain name into your browser <em>eg. google .com</em>, your computer first checks its own cache to see if the IP address is already stored. If not, it sends a request to your local DNS server.

When the user presses enter on the browser having written <em>https://www.google.com</em> the browser sends diffrent message to the server.

The url is divided into diffent parts

1. The <mark>Get / HTTP/</mark>
- Informs the server that you're requesting the homepage(/) from google using the get method.
2. The <mark>Host: www.google.com</mark>
- Tells the server which domain you're acessibg.
3. Accept,encoding and Accepting language 
- These tells the server what type of content the browser can handle
- What compression the browser can handle
- Indicates the preferred  language for the content.


#### 2. Local DNS server:
This server acts as the first point of contact. It might already have the information in its cache. If not, it will query other DNS servers to find the IP address. 
#### 3. Recursion:
The local DNS server may recursively query other DNS servers (like root nameservers) to locate the IP address. 
#### 4. IP address found:
Once the IP address is found, it is returned to your local DNS server and cached. Your local DNS server then sends the IP address back to your computer. 
#### 5. Connection established:
Your browser uses the IP address to connect to the website. 