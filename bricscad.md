# BricsCad

## Instalação

### Localização dos Addins

 Ir para a pasta do suporte [\\\bysat-tb.local\\partilha\\Operações\\03 FTTH\\06 Suporte\\@@DESENVOLVIMENTO SETLING\\](\ ":disabled") onde estão os addins do BricsCad:

- FASTFIBER
- SETLING.BricsCadAddins

### Copia dos addins

Ir para a pasta [C:\\Users\\{username}\\Documents\BricsCAD\\](\ ":disabled") e criar pastas para os addins que se deseja instalar, com os nomes:

- 00-Temporário
- FASTFIBER.BricsCadAddins
- SETLING.BricsCadAddins

*As pastas podem ter qualquer nome, desde que sejam auto descritivas*

Do suporte, copiar a pasta **toolbars**, para a pasta **SETLING.BricsCadAddins** (criada anteriormente)

> O próximo passo é feito para cada Addin individualmente

Do suporte, copiar os ficheiros **\*.BricsCadAddins.zip**, para a pasta **00-Temporário** (criada anteriormente)

clicar com o botão direito no **\*.zip**, clicar em **Properties**

![Properties](images/bricscad_1.png ':size=300')

ativar **Desbloquear** e clicar em **Aplicar** -> **OK**

Extrair o **\*.zip**, copiar os ficheiros extraidos para as pastas respetivas (as criadas anteriormente)

### Configuração do BricsCad (Toolbars)

No BricsCad, escrever o comando **cuiload**

![Toolbars](images/bricscad_2.png ':size=400')

clicar em **...**, selecionar o ficheiro **SETLINGToolbars1.cuix** na pasta **toolbars** copiada anteiormente, e clicar em **Load**, pode ser necessário alterar o **Files of type:** para **CUIX files (\*.cuix)**

![Toolbars](images/bricscad_3.png ':size=300')

Se a caixa anterior aparecer, ativar **Don't show this again (always overwrite)** e clicar em **Overwrite**

> repetir para **SETLINGToolbars2.cuix**

**No BricsCad, aparecem os Toolbars!**

![Toolbars](images/toolbars_2.png ':size=1000')

### Configuração do BricsCad (Addins)

No BricsCad, escrever o comando **appload**

![Addins](images/bricscad_4.png ':size=800')

clicar em **+**, selecionar os ficheiros **\*BricsCadAddins.dll** nas pastas criadas, clicar em **AutoLoad** emcada um deles e clicar em **Close**, e sair do BricsCad

**Ao iniciar o BricsCad, os addins estão instalados!** :smiley:

## Atualização

Fechar todas as instâncias do BricsCad

Do suporte, copiar os ficheiros **\*.BricsCadAddins.zip**, para a pasta **00-Temporário** (criada anteriormente)

clicar com o botão direito no **\*.zip**, clicar em **Properties**

![Properties](images/bricscad_1.png ':size=300')

ativar **Desbloquear** e clicar em **Aplicar** -> **OK**

Extrair o **\*.zip**, copiar os ficheiros extraidos e substituir nas pastas respetivas (as criadas anteriormente)

Ao iniciar o BricsCad, os addins estão atualizados! :smiley:
