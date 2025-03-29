# Instalação de Softwares para Desenvolvedores (Windows)

Este repositório contém um guia para instalar softwares essenciais para desenvolvedores no Windows, utilizando o gerenciador de pacotes `winget`. 

**Observação:** Este guia é baseado na opinião do autor e pode não refletir as necessidades de todos os desenvolvedores. 

## Pacotes "Desnecessários" (Opcionais)

Estes pacotes são considerados "desnecessários" pelo autor, mas podem ser úteis para alguns desenvolvedores. 

* **Microsoft Store Apps:** O autor recomenda evitar a instalação de aplicativos da Microsoft Store, pois eles geralmente são mais pesados e menos eficientes do que alternativas de código aberto. 

## Remoção de Pacotes Nativos

O autor recomenda a remoção dos seguintes pacotes nativos do Windows, pois eles são considerados desnecessários para a maioria dos desenvolvedores.

```bash
winget uninstall Microsoft.OutlookForWindows_8wekyb3d8bbwe
winget uninstall Microsoft.PowerAutomateDesktop_8wekyb3d8bbwe
winget uninstall Microsoft.WindowsFeedbackHub_8wekyb3d8bbwe
winget uninstall Microsoft.WindowsSoundRecorder_8wekyb3d8bbwe
winget uninstall Microsoft.XboxGamingOverlay_8wekyb3d8bbwe
winget uninstall MicrosoftCorporationII.QuickAssist_8wekyb3d8bbwe
winget uninstall Microsoft.Getstarted_8wekyb3d8bbwe
winget uninstall Microsoft.YourPhone_8wekyb3d8bbwe
winget uninstall WindowsCamera_8wekyb3d8bbwe
winget uninstall Microsoft.ZuneVideo_8wekyb3d8bbwe
winget uninstall Microsoft.Todos_8wekyb3d8bbwe
winget uninstall Microsoft.ScreenSketch_8wekyb3d8bbwe
winget uninstall Microsoft.People_8wekyb3d8bbwe
winget uninstall Microsoft.GetHelp_8wekyb3d8bbwe
winget uninstall Microsoft.GamingApp_8wekyb3d8bbwe
winget uninstall Microsoft.BingWeather_8wekyb3d8bbwe
winget uninstall Microsoft.BingNews_8wekyb3d8bbwe
winget uninstall Microsoft.549981C3F5F10_8wekyb3d8bbwe
winget uninstall Clipchamp.Clipchamp_yxz26nhyzhsrt
winget uninstall Microsoft.Windows.Photos_8wekyb3d8bbwe
winget uninstall Microsoft.WindowsAlarms_8wekyb3d8bbwe
winget uninstall microsoft.windowscommunicationsapps_8wekyb3d8bbwe
winget uninstall microsoft.WindowsMaps_8wekyb3d8bbwe
winget uninstall 0microsoft.windowscommunicationsapps_8wekyb3d8bbwe
winget uninstall Microsoft.MicrosoftOfficeHub_8wekyb3d8bbwe
winget uninstall Microsoft.ZuneMusic_8wekyb3d8bbwe
winget uninstall Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe
```

## Instalação de Pacotes Adicionais

O autor recomenda a instalação dos seguintes pacotes adicionais, que podem ser úteis para o desenvolvimento de software:

```bash
winget install -e --id Mozilla.Firefox
winget install -e --id Google.Chrome
winget install -e --id Zoom.Zoom
winget install -e --id Microsoft.Teams
winget install -e --id Foxit.FoxitReader
winget install -e --id RARLab.WinRAR
winget install -e --id AnyDeskSoftwareGmbH.AnyDesk
winget install -e --id RustDesk.RustDesk
winget install -e --id HeidiSQL.HeidiSQL
winget install -e --id PuTTY.PuTTY
winget install -e --id VivaldiTechnologies.Vivaldi
```



## Pacotes "Essencialmente Necessários para programação"

Estes pacotes são considerados essenciais para o desenvolvimento de software no Windows.

* **Visual Studio Code:** Um editor de código leve e poderoso, perfeito para desenvolvimento web, mobile e desktop.
    ```bash
    winget install vscode
    ```
* **Git:** Um sistema de controle de versão essencial para qualquer desenvolvedor.
    ```bash
    winget install git
    ```
* **Node.js:** Um ambiente de execução JavaScript que permite executar código JavaScript fora do navegador.
    ```bash
    winget install nodejs
    ```
* **Python:** Uma linguagem de programação versátil e popular, ideal para desenvolvimento web, ciência de dados e muito mais.
    ```bash
    winget install python
    ```
* **Docker Desktop:** Uma plataforma de contêineres que facilita a criação, implantação e execução de aplicativos.
    ```bash
    winget install docker-desktop
    ```
* **Postman:** Uma ferramenta para testar APIs.
    ```bash
    winget install postman
    ```
* **Chrome:** O navegador web mais popular, com ferramentas de desenvolvimento integradas.
    ```bash
    winget install google-chrome
    ```

## Pacotes "Opcionais"

Estes pacotes são considerados "opcionais" pelo autor, mas podem ser úteis para alguns desenvolvedores.

* **VirtualBox:** Uma ferramenta para criar máquinas virtuais.
    ```bash
    winget install virtualbox
    ```
* **7-Zip:** Um utilitário de compactação de arquivos gratuito e poderoso.
    ```bash
    winget install 7zip
    ```
* **VLC Media Player:** Um reprodutor de mídia multiplataforma gratuito e de código aberto.
    ```bash
    winget install vlc
    ```

## Observações

* Este guia é apenas um ponto de partida, e você pode precisar instalar outros pacotes dependendo de suas necessidades específicas.
* O autor recomenda que você explore outras alternativas de código aberto para os pacotes listados acima, caso deseje.
* É importante manter seu sistema atualizado com as últimas versões dos softwares instalados.

## Lista de IDs de Aplicativos

Caso queira manter algum app nativo, apague o comando referente a ele na seção "Remoção de Pacotes Nativos". Abaixo está a lista da ID de cada aplicativo. (copie a ID e use Ctrl+F para pesquisá-lo na lista acima) 

* **Outlook for Windows:** Microsoft.OutlookForWindows_8wekyb3d8bbwe 
* **Power Automate:** Microsoft.PowerAutomateDesktop_8wekyb3d8bbwe 
* **Hub de Comentários:** Microsoft.WindowsFeedbackHub_8wekyb3d8bbwe 
* **Gravador de Som:** Microsoft.WindowsSoundRecorder_8wekyb3d8bbwe 
* **Game Bar:** Microsoft.XboxGamingOverlay_8wekyb3d8bbwe 
* **Assistência Rápida:** MicrosoftCorporationII.QuickAssist_8wekyb3d8bbwe  
* **Dicas da Microsoft:** Microsoft.Getstarted_8wekyb3d8bbwe 
* **Vincular ao Celular:** Microsoft.YourPhone_8wekyb3d8bbwe 
* **Camera:** WindowsCamera_8wekyb3d8bbwe 
* **Filmes e TV:** Microsoft.ZuneVideo_8wekyb3d8bbwe 
* **Microsoft To Do:** Microsoft.Todos_8wekyb3d8bbwe 
* **Ferramenta de Captura:** Microsoft.ScreenSketch_8wekyb3d8bbwe 
* **Pessoas Microsoft:** Microsoft.People_8wekyb3d8bbwe 
* **Obter Ajuda:** Microsoft.GetHelp_8wekyb3d8bbwe 
* **Xbox:** Microsoft.GamingApp_8wekyb3d8bbwe 
* **MSN Clima:** Microsoft.BingWeather_8wekyb3d8bbwe 
* **Notícias:** Microsoft.BingNews_8wekyb3d8bbwe 
* **Cortana:** Microsoft.549981C3F5F10_8wekyb3d8bbwe 
* **Microsoft Clipchamp:** Clipchamp.Clipchamp_yxz26nhyzhsrt 
* **Fotos Microsoft:** Microsoft.Windows.Photos_8wekyb3d8bbwe 
* **Relógio do Windows:** Microsoft.WindowsAlarms_8wekyb3d8bbwe 
* **Email e Calendário:** microsoft.windowscommunicationsapps_8wekyb3d8bbwe 
* **Mapas do Windows:** Microsoft.WindowsMaps_8wekyb3d8bbwe 
* **Microsoft 365 (Office):** Microsoft.MicrosoftOfficeHub_8wekyb3d8bbwe 
* **Reprodutor Multimídia do Windows:** Microsoft.ZuneMusic_8wekyb3d8bbwe
* **Calculadora:** Microsoft.WindowsCalculator_8wekyb3d8bbwe 
* **Notas autoadesivas:** Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe 

## Vantagens de usar o winget

O `winget` é um gerenciador de pacotes para Windows que oferece diversas vantagens em relação aos métodos tradicionais de instalação de software:

* **Facilidade de uso:** O `winget` simplifica o processo de instalação, atualização e remoção de softwares, com comandos simples e intuitivos.
* **Gerenciamento centralizado:**  O `winget` permite gerenciar todos os seus softwares instalados em um único lugar, facilitando a atualização e a remoção de aplicativos.
* **Segurança:** O `winget` garante a segurança das instalações, baixando softwares apenas de fontes confiáveis.
* **Automação:** O `winget` pode ser utilizado em scripts para automatizar a instalação de softwares, ideal para configurar novos computadores ou para atualizar softwares em massa.

## Instalação do winget

Para instalar o `winget` no Windows 10 e 11, siga os seguintes passos:

1. Abra o Microsoft Store e procure por "Package Manager".
2. Clique no botão "Obter" para instalar o aplicativo.
3. Aguarde a conclusão da instalação.

## Atualização de aplicativos com winget

Para atualizar todos os aplicativos instalados com o `winget`, execute o seguinte comando no prompt de comando ou PowerShell:

```bash
winget upgrade --all
```

## Frequência de atualização

É recomendado atualizar seus aplicativos com frequência para garantir que você tenha as últimas correções de segurança e recursos. Você pode atualizar seus aplicativos semanalmente ou mensalmente, dependendo da sua necessidade.

Para verificar se há atualizações disponíveis para um aplicativo específico, use o comando:

```bash
winget upgrade --id <id_do_aplicativo>
```

Substitua `<id_do_aplicativo>` pelo ID do aplicativo que você deseja atualizar.

## Contribuições

Este repositório está em constante atualização, e você pode contribuir com a lista de softwares! 

* **Envie um Pull Request:** Se você encontrar algum erro, tiver sugestões de novos softwares ou quiser adicionar novas categorias, sinta-se à vontade para enviar um Pull Request!
* **Abra um Issue:** Se você tiver alguma dúvida ou quiser reportar um problema, abra um Issue no repositório.

Volte sempre para verificar as atualizações e novas adições à lista! 😉