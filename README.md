# T-Pot Config

```bash
sudo su
```

```bash
systemctl stop tpot
```

```bash
cd /opt/tpot/etc/
```

```bash
curl -o tpot.yml https://raw.githubusercontent.com/munozrc/t-pot/main/compose/conpot.yml
```

```bash
systemctl start tpot
```

Para restablecer a la configuración inicial ejecutamos el siguiente comando

```bash
cp compose/standard.yml ./tpot.yml
```
[https://github.com/telekom-security/tpotce#network-interface-fails]()
