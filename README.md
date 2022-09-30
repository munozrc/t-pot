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
curl -o tpot.yml https://raw.githubusercontent.com/munozrc/t-pot/main/compose/industrial.yml
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

![image](https://user-images.githubusercontent.com/47870821/192424321-a4607148-156b-4618-a190-f4a41b1027a4.png)

```bash
sudo nmap --script=s7-enumerate -p 102 <<ip-adress>>
```
