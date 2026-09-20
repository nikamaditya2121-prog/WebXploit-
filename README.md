# WebXploit-
**#WAF Architecture **


          HTTP Request
                |
                v
        +---------------+
        |     Nginx     |
        +-------+-------+
                |
                v
        +---------------+
        | ModSecurity   |
        +-------+-------+
                |
          +-----+-----+
          |           |
        BLOCK       ALLOW
          |           |
          v           v
       403        Backend
                      |
                      v
                 Juice Shop
