# ets2-python-telemetry

ETS2 (Euro Truck Simulator 2) python telemetry reader for nlhans' [ets2-sdk-plugin](https://github.com/nlhans/ets2-sdk-plugin "https://github.com/nlhans/ets2-sdk-plugin") based on nlhans' telemetry client for python applications.

## Installation
> 0. Login steam, download [Euro Truck Simulation2](https://eurotrucksimulator2.com/)
> 1. Hit the [link](https://github.com/nlhans/ets2-sdk-plugin "https://github.com/nlhans/ets2-sdk-plugin") above and follow instructions.
> 2. SDK file (DLL file) must be in `<Euro Truck Simulation2>\bin\<win_x64 or win_x86>\plugins`
> > path would be like this: `C:\steam\steamapps\common\Euro Truck Simulation2\bin\win_x64\plugins`
> > if there is no plugins folder inside of win_x64, make "plugins" folder and put a DLL file in it

## Usage 
> 1. clone this repo. type it on terminal.<br>
> ```shell
> $ git clone https://github.com/comeeasy/ets2-python-telemetry.git
> ```
>
> 2. run __Euro Truck Simulation2.exe__
> <br><img src="https://github.com/comeeasy/ets2-python-telemetry/blob/master/imgs/start-sim.png" width="40%" height="30%" title="start ets2" alt="RubberDuck"></img><br>
>
> 3. run code.<br>
> ```shell
> $ cd ets-python-telemetry
> $ python get.py
> ```
> 
> <br><img src="https://github.com/comeeasy/ets2-python-telemetry/blob/master/imgs/run.png" width="40%" height="30%" title="running display" alt="RubberDuck"></img><br>

## details

### If you want other telemetry information
then, see [ets2sdkdata.py](https://github.com/comeeasy/ets2-python-telemetry/blob/master/ets2sdkdata.py)
and also here

> most important code in `get.py` is just like below
```python
data = sm.update()
f.wrtie(data)
```

## Go Get some data from ET2!






