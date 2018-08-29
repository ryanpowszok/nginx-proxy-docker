Docker Nginx Proxy
============================

* Version: 1.0.0
* Developer: Ryan Powszok
* Website: [ryanpowszok.com](https://ryanpowszok.com)
* Copyright: (c) 2018 Ryan Powszok / Juke Labs, Inc.

## Get Started

This repo contains a docker setup for using the JWilder Nginx Proxy. See https://github.com/jwilder/nginx-proxy for more info.

Make sure you have docker installed and running. Also make sure you don't have any running containers using port 80 or 443.

## Commands

```
Git clone repo and cd into project folder. Run the following commands:
$ docker network create proxy
$ docker-compose up -d
```

License
-------------------------------------

Copyright © 2018 Ryan Powszok / Juke Labs, Inc. All Rights Reserved.

Released under the MIT License: [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)

	The MIT License

	Permission is hereby granted, free of charge, to any person obtaining a copy of this software and
	associated documentation files (the “Software”), to deal in the Software without restriction,
	including without limitation the rights to use, copy, modify, merge, publish, distribute,
	sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in all copies or
	substantial portions of the Software.

	THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING
	BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
	NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
	DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
