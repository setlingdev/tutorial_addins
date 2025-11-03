# BricsCad

## Instalação

### Localização dos Addins

 Ir para a pasta do suporte [\\\bysat-tb.local\\partilha\\Operações\\03 FTTH\\06 Suporte\\@@DESENVOLVIMENTO SETLING\\](\ ':disabled') onde estão os addins do BricsCad:

- FASTFIBER
- SETLING.BricsCadAddins

### Copia dos addins

Ir para a pasta [C:\\Users\\{username}\\Documents\BricsCAD\\](\ ':disabled') e criar pastas para os addins que se deseja instalar, com os nomes:

- 00-Temporário
- FASTFIBER.BricsCadAddins
- SETLING.BricsCadAddins

*As pastas podem ter qualquer nome, desde que sejam auto descritivas*

Do suporte, copiar a pasta **toolbars**, para a pasta **SETLING.BricsCadAddins** (criada anteriormente)

> O próximo passo é feito para cada Addin individualmente

Do suporte, copiar os ficheiros **\*.BricsCadAddins.zip**, para a pasta **00-Temporário** (criada anteriormente)

clicar com o botão direito no **\*.zip**, clicar em **Properties**

![Properties](img/bricscad_1.png ':size=300')

ativar **Desbloquear** e clicar em **Aplicar** -> **OK**

Extrair o **\*.zip**, copiar os ficheiros extraidos para as pastas respetivas (as criadas anteriormente)

### Configuração do BricsCad (Toolbars)

No BricsCad, escrever o comando **cuiload**

![Toolbars](img/bricscad_2.png ':size=400')

clicar em **...**, selecionar o ficheiro **SETLINGToolbars1.cuix** na pasta **toolbars** copiada anteiormente, e clicar em **Load**, pode ser necessário alterar o **Files of type:** para **CUIX files (\*.cuix)**

![Toolbars](img/bricscad_3.png ':size=300')

Se a caixa anterior aparecer, ativar **Don't show this again (always overwrite)** e clicar em **Overwrite**

> repetir para **SETLINGToolbars2.cuix**

**No BricsCad, aparecem os Toolbars!**

![Toolbars](img/toolbars_2.png ':size=1000')

### Configuração do BricsCad (Addins)

No BricsCad, escrever o comando **appload**

![Addins](img/bricscad_4.png ':size=800')

clicar em **+**, selecionar os ficheiros **\*BricsCadAddins.dll** nas pastas criadas, clicar em **AutoLoad** em cada um deles e clicar em **Close**, e sair do BricsCad

**Ao iniciar o BricsCad, os addins estão instalados!** :smiley:

## Atualização

Fechar todas as instâncias do BricsCad

Do suporte, copiar os ficheiros **\*.BricsCadAddins.zip**, para a pasta **00-Temporário** (criada anteriormente)

clicar com o botão direito no **\*.zip**, clicar em **Properties**

![Properties](img/bricscad_1.png ':size=300')

ativar **Desbloquear** e clicar em **Aplicar** -> **OK**

Extrair o **\*.zip**, copiar os ficheiros extraidos e substituir nas pastas respetivas (as criadas anteriormente)

Ao iniciar o BricsCad, os addins estão atualizados! :smiley:

## Lista de comandos

Lista de todos os comandos de descrição, por módulos/operadores

| Comando | Descrição | Grupo | Toolbar |
| :- | :- | :- | :- |
| [pal](#) | Mostra e/ou esconde a palete do addin | Geral | SETLING TOOLBARS 1 |
| [gmcs](#) | Lê o sistema de coordenadas associado ao desenho | Geral | SETLING TOOLBARS 1 |
| [smcs](#) | Atribui o sistema de coordenadas do desenho | Geral | SETLING TOOLBARS 1 |
| [gmview](#) | Abre o Google Maps no ponto selecionado | Geral | SETLING TOOLBARS 1 |
| [gmimages](#) | Insere imagens do Google Maps na área e com o estilo selecionados | Geral | SETLING TOOLBARS 1 |
| [gsview](#) | Abre o Google Streetview no ponto e direção selecionados | Geral | SETLING TOOLBARS 1 |
| [gemview](#) | Abre o Google Earth no ponto selecionado | Geral | SETLING TOOLBARS 1 |
| [gesview](#) | Abre o Google Maps em mode de streetview no ponto e direção selecionados | Geral | SETLING TOOLBARS 1 |
| [limsel](#) | Seleciona todos os blocos do tipo selecionado, dentro ou fora do limite selecionado | Geral | SETLING TOOLBARS 1 |
| [totl](#) | Calcula o comprimento das polilinhas selecionadas ou a selecionar, por layer | Geral | SETLING TOOLBARS 1 |
| [uasnos](#) | Contar UAs dentro do limite selecionado | NOS Validação | SETLING TOOLBARS 1 |
| [epcnosproj](#) | Exporta para PNI, com uma distância mínima aos cabos | NOS Validação | SETLING TOOLBARS 1 |
| [valnosproj](#) | Valida projecto NOS | NOS Validação | SETLING TOOLBARS 1 |
| [esinopnosval](#) | Exporta o sinóptico dentro de um ou mais limites, para a folha de Validação | NOS Validação | SETLING TOOLBARS 1 |
| [emapanosval](#) | Exporta o mapa de rede dentro de um ou mais limites, para a folha de Validação | NOS Validação | SETLING TOOLBARS 1 |
| [udsnosproj](#) | Faz o upgrade ou o downgrade das especificações do PNI | NOS Validação | SETLING TOOLBARS 1 |
| [facxmlnos](#) | Exporta o projecto para o formato XML do PNI (copia a ferramenta da NOS para esta exportação) | NOS Validação | SETLING TOOLBARS 1 |
| [cmd](#) | --- | NOS | SETLING TOOLBARS 2 |
| [cmd](#) | --- | NOS projecto | SETLING TOOLBARS 2 |
| [cmd](#) | --- | Belgica | SETLING TOOLBARS 2 |
| [cmd](#) | --- | DIGI | SETLING TOOLBARS 2 |
| [cmd](#) | --- | Geral | NO TOOLBARS |
