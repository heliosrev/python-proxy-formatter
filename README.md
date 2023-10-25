# Python Proxy Formatter

A Python script to reformat proxy strings into a consistent format. It can handle various input formats, including HTTP, HTTPS, SOCKS4, SOCKS5, as well as username and password with or without a hostname/IP and port.

## Supported Formats

The Python Proxy Formatter supports the following formats:

    http://hostname:port
    http://username:password@hostname:port
    https://hostname:port (converted to http://)
    https://username:password@hostname:port (converted to http://)
    socks4://hostname:port
    socks4://username:password@hostname:port
    socks5://hostname:port
    socks5://username:password@hostname:port

## Error Handling

If an invalid proxy format is provided, the reformat_proxy function will raise an exception with an error message.

## Contributions

Contributions to improve and expand the functionality of this Python Proxy Formatter are welcome. Feel free to create issues or pull requests.
