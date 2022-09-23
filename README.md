# First-Steps

Estos son los primeros pasos en Python, si quieres acompañarme en este camino te invito:

## Sobre mi

<p align="center">
<img src="https://user-images.githubusercontent.com/1339349/191783230-5b506457-677b-49a2-a816-de538fe80c82.png" width="150px">
</p>

Este documento está hecho para aquellas personas que tengan interés en aprender Python desde un nivel básico hasta niveles más avanzados con pequeños proyectos que se harán poco a poco a mendida que vayamos avanzando

Puedes empezar pinchando en los siguientes enlaces:

- [Primero](https://www.python.org/downloads/)
 
# Second-Steps


```python
		
>>> city = "Tokyo"
>>> ctiy
Traceback (most recent call last):
File "<stdin>", line 1, in <module>
NameError: name 'ctiy' is not defined

```

```
		
menu.py
		
```	

```python
		
<details><summary>CLICK ME</summary>
<p>

#### We can hide anything, even code!

	```ruby
   	puts "Hello World"
	```

</p>
</details>
		
```	


<details><summary>CLICK ME</summary>
<p>

#### We can hide anything, even code!

```ruby
   puts "Hello World"
```

</p>
</details>


### CodeQL for Visual Studio Code

You can install the [CodeQL for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-codeql) extension to get syntax highlighting, IntelliSense, and code navigation for the QL language, as well as unit test support for testing CodeQL libraries and queries.

### Tasks

The `.vscode/tasks.json` file defines custom tasks specific to working in this repository. To invoke one of these tasks, select the `Terminal | Run Task...` menu option, and then select the desired task from the dropdown. You can also invoke the `Tasks: Run Task` command from the command palette.



.. code-block:: python

    >>> import psutil
    >>>
    >>> psutil.cpu_times()
    scputimes(user=3961.46, nice=169.729, system=2150.659, idle=16900.540, iowait=629.59, irq=0.0, softirq=19.42, steal=0.0, guest=0, nice=0.0)
    >>>
    >>> for x in range(3):
    ...     psutil.cpu_percent(interval=1)
    ...
    4.0
    5.9
    3.8
    >>>
    >>> for x in range(3):
    ...     psutil.cpu_percent(interval=1, percpu=True)
    ...
    [4.0, 6.9, 3.7, 9.2]
    [7.0, 8.5, 2.4, 2.1]
    [1.2, 9.0, 9.9, 7.2]
    >>>
    >>> for x in range(3):
    ...     psutil.cpu_times_percent(interval=1, percpu=False)
    ...
    scputimes(user=1.5, nice=0.0, system=0.5, idle=96.5, iowait=1.5, irq=0.0, softirq=0.0, steal=0.0, guest=0.0, guest_nice=0.0)
    scputimes(user=1.0, nice=0.0, system=0.0, idle=99.0, iowait=0.0, irq=0.0, softirq=0.0, steal=0.0, guest=0.0, guest_nice=0.0)
    scputimes(user=2.0, nice=0.0, system=0.0, idle=98.0, iowait=0.0, irq=0.0, softirq=0.0, steal=0.0, guest=0.0, guest_nice=0.0)
    >>>
    >>> psutil.cpu_count()
    4
    >>> psutil.cpu_count(logical=False)
    2
    >>>
    >>> psutil.cpu_stats()
    scpustats(ctx_switches=20455687, interrupts=6598984, soft_interrupts=2134212, syscalls=0)
    >>>
    >>> psutil.cpu_freq()
    scpufreq(current=931.42925, min=800.0, max=3500.0)
    >>>
    >>> psutil.getloadavg()  # also on Windows (emulated)
    (3.14, 3.89, 4.67)
