Instagram Post Scheduler
========
<a href="https://www.instagram.com/sinha.py/"><img src="https://miro.medium.com/max/1400/1*zR-cuwIFJOpQjLHExqrFkA.png" alt="Auto Post"/></a>

## Before Running `scheduler.py`

* Open scheduler.py File and Edit The Following Lines:

1) `username = 'USERNAME'  # Enter your username here` [line:23]

2) `password = 'PASSWORD'  # Enter your password here` [line:24]

3) `file_path = r"C:\Users\P Sinha\Desktop\Capture.png"  # File Path Where Pic/Vid is Stored That You Want To Upload` [line:25]

Ensure that you have Chrome installed and the
[`chromedriver` ](https://chromedriver.chromium.org/downloads) that matches
your Chrome version available on your `$PATH`. You may have to update this from time to time.

## Requirements
 
* [Python](https://www.python.org/)
* `python` on the PATH
* [The Requests Library](http://python-requests.org) for Python: `pip install requests`
* Install Selenium:

```bash
pip install selenium
```
* Install Schedule:

```bash
pip install schedule
```
* Install pyautogui:

```bash
pip install PyAutoGUI
```

## Run

* Run the programme using:

```bash
python scheduler.py
```