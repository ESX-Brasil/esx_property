# esx_property

### Requisitos
- [instance](https://github.com/ESX-Brasil/instance)
- [cron](https://github.com/ESX-Brasil/cron)
- [esx_addonaccount](https://github.com/ESX-Brasil/esx_addonaccount)
- [esx_addoninventory](https://github.com/ESX-Brasil/esx_addoninventory)
- [esx_datastore](https://github.com/ESX-Brasil/esx_datastore)

## Download e Instalação

### Usando [fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=esx ESX-Brasil/esx_property
```

### Usando o Git
```
cd resources
git clone https://github.com/ESX-Brasil/esx_property [esx]/esx_property
```

### Manualmente
- Download https://github.com/ESX-Brasil/esx_property/archive/master.zip
- Coloque-o no diretório `[esx]`

## Instalação
- Importe `esx_property.sql` em seu banco de dados
- Importe `esx_offices.sql` em seu banco de dados se você quiser escritórios (O Arcadius Business Center não está incluído porque realstateagentjob)
- Adicione isto ao seu `server.cfg`:

```
start esx_property
```

# Legal
### License
esx_property - own a property!

Copyright (C) 2015-2018 Jérémie N'gadi

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
