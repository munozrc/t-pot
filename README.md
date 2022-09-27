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
[Error Network Service](https://github.com/telekom-security/tpotce#network-interface-fails)   
[User Types](https://github.com/telekom-security/tpotce#required-ports)

### Users

| Type        | Name        | Password    |
| ----------- | ----------- | ----------- |
| OS          | tsect       | 1234        |
| Admin Web   | tsect       | 1234        |
| Tools Ngix  | tuser       | 1234        |

