# Excel

## Instalação

### Configuração do Excel (Confiança)

No Excel, ir a **File** -> **Options** -> **Trust Center**, clicar em **Trust Center Settings...** -> **Trusted Locations**

![Trust Center](images/trust_center_1.png ':size=900')

ativar **Allow Trusted Locations on my network (not recommended)** e clicar em **Add new location...**

![Trust Center](images/trust_center_2.png ':size=450')

clicar em **Browse...** e selecionar a pasta [C:\\Users\\{username}\\AppData\\Roaming\\Microsoft\\AddIns\\](\ ":disabled") e clicar em **OK**

ativar **Subfolders of this location are also trusted** e clicar em **OK** -> **OK** -> **OK**, e sair do Excel

### Localização dos Addins

 Ir para a pasta do suporte [\\\bysat-tb.local\\partilha\\Operações\\03 FTTH\\06 Suporte\\@@DESENVOLVIMENTO SETLING\\](\ ":disabled") onde estão os addins do Excel:

- FASTFIBER
- SETLING.ExcelAddins
- SETLING.PARCEIROS.ExcelAddins
- SETLING.FINANCE.ExcelAddins
- SETLING.HOTELARIA.ExcelAddins

### Copia dos addins

Ir para a pasta [C:\\Users\\{username}\\AppData\\Roaming\\Microsoft\\AddIns\\](\ ":disabled") e criar pastas para os addins que se deseja instalar, com os nomes:

- FASTFIBER.ExcelAddins
- SETLING.ExcelAddins
- SETLING.PARCEIROS.ExcelAddins
- SETLING.FINANCE.ExcelAddins
- SETLING.HOTELARIA.ExcelAddins

*As pastas podem ter qualquer nome, desde que sejam auto descritivas*

Do suporte, copiar os ficheiros **\*.ExcelAddins32.xll** e **\*.ExcelAddins64.xll**, e as subpastas **configs** e **fac-addins-help**, se existirem, para as pastas respetivas (as criadas anteriormente)

### Configuração do Excel (Addins)

> O próximo passo é feito para cada Addin individualmente

No Excel, ir a **File** -> **Options** -> **Add-ins** e clicar em **Go...**

![Trust Center](images/trust_center_3.png ':size=900')

![Trust Center](images/trust_center_4.png ':size=400')

clicar em **Browse...** e selecionar uma das pasta criadas em [C:\\Users\\{username}\\AppData\\Roaming\\Microsoft\\AddIns\\](\ ":disabled") e clicar em **Open**

ativar o addin respetivo **\*.ExcelAddins Add-In** e clicar em **OK**, e sair do Excel

**Ao iniciar o Excel, aparecem os Toolbars, os addins estão instalados!** :smiley:

![Toolbars](images/toolbars_1.png ':size=1000')

## Atualização

Fechar todas as instâncias do Excel

Do suporte, copiar os ficheiros **\*.ExcelAddins32.xll** e **\*.ExcelAddins64.xll**, e as subpastas **configs** e **fac-addins-help**, se existirem, substituir nas pastas respetivas

Ao iniciar o Excel, os addins estão atualizados! :smiley:
