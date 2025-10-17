## Overview

This is a simple web application that simulates a captcha solver. It takes a URL parameter `url` for the captcha image, displays the image, and then displays a "solved" captcha after a short delay. This version uses a dummy solver.  The solution is displayed after 2 seconds.

## Setup

1.  Save the `index.html` file to your local machine.
2.  (Optional) Place the `sample.png` (or your own captcha image) in the same directory as the `index.html` file, or specify an absolute URL.

## Usage

1.  Open the `index.html` file in your web browser.
2.  To use a specific captcha image, pass the `url` parameter in the URL.  For example:
    `index.html?url=https://example.com/image.png`
3. If no `url` parameter is given it defaults to `sample.png`.
4.  The solved captcha will be displayed after a short delay (2 seconds).