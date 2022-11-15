# LicensePro

Built with JavaScript and using jQuery

## Usage

- Set your API on <a href="https://apiary.io" target="_blank">apiary.io</a>
- Make API and add this following params on your response (POST)

```
  {
    "const_t": "Invalid",
    "const_st": "Purchase Code or Unauthorized Domain",
    "const_bl": "Blocked by testing.id",
    "const_sup": "contact support",
    "const_api": "https://api.whatsapp.com/send/?phone=621234567891",
    "const_font": "https://fonts.googleapis.com/css?family=IBM+Plex+Mono|Sedgwick+Ave+Display",
    "lisc":[
        {
            "pscode": "IA829ZjXBMSr6dpowexddfr7kHxJv4NdhRt0ugD8bM=",
            "host": "127.0.0.1:8000",
            "name": "Localhost",
            "number": "000000000000"
        },{
            "pscode": "dFyi3casd34!&0npmiu/KPJxZ+AAOkLmocYCJrOBdI=",
            "host": "0.0.0.0:8000",
            "name": "Localhost",
            "number": "000000000000"
        }
    ]
}
```

- Blend <b>enc.js</b> on your JS script (above jQuery script)

## Lisence
```
MIT License

Copyright (c) 2022 Aditya Rizqi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
