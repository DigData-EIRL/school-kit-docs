
# Activar venv 

source venv/bin/activate

# Desactivar tu virtualenv

Cuando finalices tu trabajo en tu ambiente virtual, puedes desactivarlo corriendo lo siguiente:

[server]$ deactivate

# Eliminar tu ambiente virtual

Para eliminar tu ambiente virtual, simplemente elimina la carpeta del proyecto. Usando el ejemplo anterior, corre el siguiente comando:

[server]$ rm -rf venv


## Freezing dependencies

Pip can export a list of all installed packages and their versions using the freeze command:
Unix/macOS

python3 -m pip freeze

Windows

Which will output a list of package specifiers such as:

cachetools==2.0.1
certifi==2017.7.27.1
chardet==3.0.4
google-auth==1.1.1
idna==2.6
pyasn1==0.3.6
pyasn1-modules==0.1.4
requests==2.18.4
rsa==3.4.2
six==1.11.0
urllib3==1.22

```py
    python3 -m pip install -r requirements.txt
```
# Sensor de Huellas digitales

https://github.com/adafruit/Adafruit-Fingerprint-Sensor-Library

https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2380057.m570.l1313&_nkw=Rugged+Panel+Mount+Fingerprint+Sensor+with+Bi-Color+LED+Ring+-+R503&_sacat=0