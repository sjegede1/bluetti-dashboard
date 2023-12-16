### First create a virtual env
```python -m venv [ENVIRONMENT NAME]```

### Then activate the environment 
```source [ENVIRONMENT NAME]/Scripts/activate```

### Install bluetti_mqtt from my fork
```pip install -r requirements.txt```


### When you update the bluetti_mqtt fork and you want to update your virtualenv do this.
```
pip install git+https://github.com/sjegede1/bluetti_mqtt#egg=bluetti_mqtt --upgrade
pip freeze > requirements.txt
```