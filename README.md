## Pomodoro timer

Digital pomodoro style timer designed in Python which works for Linux and Windows. The project uses PySide6 module.

# Installing
Make sure you are inside the repository folder.
### Virtual environment
It is recommended to use a virtual environment, where 'name' is the name you want, without quotes.
```
python -m venv 'name'
```
Activate the virtual environment where 'name' is the name from the previous step.
```
source name/bin/activate
```
### Installing dependencies
Use the `pip install -r` command to install the dependencies of the "requirements.txt" document.
```
pip install -r requirements.txt
```
# Using Pomodoro timer
To run the script simply use `sudo` (make sure you are in a virtual environment):
```
sudo python timer_pyside6.py
```

Remember to use the `deactivate` command when you finish using the timer to exit virtual environment.

# Available functions

In the actual version of Pomodoro timer you can use the following functions:

- Set time between 99:99 and 00:01 minutes
- Set optional break time between 00:00 and 20:00 minutes
- Start timer
- Stop timer
- Resume timer
- Reset timer
- Change color theme

<br/>
<br/>

---

*by José Joaquín Rojas Romero aka tric0 - josrojrom1@alum.us.es*




