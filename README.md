# Engineering Application Form
This is an experiment to make applying for a job a better process. It provides a low barier technical challenge to allow submission of the application. Upon successful submission, an email is sent to the applicant and the collector of the applications for futher review.

## Getting started locally
```bash
$ bundle install
$ puma
```

ENV variables:
EMAIL_TO => Who is receiving the emails?
EMAIL_FROM => Who should the FROM address be for notifications set to the applicant?
RECAPTCHA_KEY => Google Recaptcha key

Deployment Keys
SENDGRID_USERNAME
SENDGRID_PASSWORD
REDIS_URL
MEMCACHIER_USERNAME
MEMCACHIER_PASSWORD


## License
The MIT License (MIT)

Copyright (c) 2015 Daniel Westendorf

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.