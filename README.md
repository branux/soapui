# SOAP UI - Configuração e uso

  Vamos explicar como acessar o InfoConv utilizando a ferramenta [SoapUI].

### Instalar o SOAP UI

  Baixe o aplicativo na página do [SoapUI](https://www.soapui.org/) e siga as instruções para a sua plataforma.

### Configurar o Soap UI para utilizar o Certificado Digital

![settings](https://36.media.tumblr.com/e39e268bd6b0099053ebbefc69159642/tumblr_o5ovjoFi9f1vrh3lho1_1280.png)

  - Ir no menu File->Preferences  ou teclar Ctr+Alt+P  (Sets global SoapUI preferences)
  - Procurar as propriedade de SSL Settings 
  - Informar o caminho do KeyStore
  - Informar a senha 123456 ( trocar por sua senha)
  - Checar a propriedade: Client Authentication:  [X] requires client authentication
  - Dar um OK 

### Importar o projeto do Infoconv-ConsultarCPF no SoapUI

  - Ir no menu File->Import ou teclar Ctrl+I
  - Selecionar o arquivo Infoconv-ConsultarCPF-soapui-project.xml


### Testar as consultas de CPF

  - Abrir o Binding ConsultarCPFSoap
  - Abrir a operação: ConsultarCPFP3 
  - Testar o Request1 inserindo um CPF para consulta e o seu CPF como usuário.
