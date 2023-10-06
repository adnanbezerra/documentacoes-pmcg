# Tutorial simples de instalação do Token e do PJe

## Parte 1: Desativar o firewall

Essa etapa é padrão, dado que o firewall do Windows, via de regra, mais atrapalha que ajuda. Para fazê-lo, basta pesquisar no dispositivo pelo firewall e desativar tudo o que estiver ativado. Normalmente ele vai pedir autenticação de nível de administrador caso a máquina seja institucional.

## Parte 2: Instalação do Token

O token é uma espécie de pen-drive que cumpre a função de certificado digital. É um dispositivo que serve para, após configurado, comprovar a autenticidade de uma tentativa de acesso. Com isso, aquele que porta o token de um serviço tem uma espécie de *RG digital*, recebendo acesso a algumas plataformas.

No ambiente da prefeitura, o token é muito utilizado pelos advogados para o acesso à plataforma do PJe, onde as tramitações dos processos são disponibilizadas. Portanto, o **bom funcionamento do token é crucial para o bom andamento de toda a prefeitura.**

- Para instalá-lo, de início, é preciso encontrar o modelo do seu token. Os mais comuns são os da [CertiSign](https://www.certisign.com.br/duvidas-suporte/downloads/tokens), então é bastante provável que o que você quer instalar também seja deles. 
  - Uma coisa a se notar de imediato é que **o certificado não tem suporte para Linux**, então, caso você queira fazer uso em uma máquina com esse sistema, desista.
- De seguida, selecione o S.O. da máquina: Windows ou MacOS. Você vai notar que, ao fazer a sua escolha, uma tabela vai abrir, onde você vai poder escolher o modelo do dispositivo em questão e também decidir se seu S.O. é de 32 ou de 64 bits. 
- Após fazer download do arquivo certo, respeitando o modelo do seu dispositivo e o seu sistema operacional, basta clicar no arquivo aberto e seguir o passo-a-passo dado no processo.
- Para saber se a instalação deu certo, você deve conectar o aparelho à sua máquina e ver se o dispositivo foi corretamente reconhecido.

## Parte 3: Instalação do PJe Office

- Certifique-se de já ter a versão mais recente do Java instalada no seu dispositivo. Do contrário, o programa ***não funcionará***.
  - Para instalar, basta acessar a página de [download do Java](https://www.oracle.com/java/technologies/downloads/#jdk21-windows) na Oracle e selecionar a versão mais recente para o seu sistema operacional. Sugerimos escolher a que tiver Installer no nome
- Navegue até a página da [wiki do PJe](https://www.pje.jus.br/wiki/index.php/PJeOffice) e faça o download da versão apropriada para o seu S.O. Note que o PJe funciona no Linux, embora o token não.
- De seguido, clique no arquivo baixado e siga os passos para a instalação.
- Após o fim da instalação, caso queira, você pode clicar em iniciar PJe, caso queira.
  - Note que ele não vai abrir nada de imediato. Você vai saber se o PJe está funcionando ou não olhando na barra de tarefas do seu aparelho, **na parte inferior direita**, onde o ícone do aplicativo vai aparecer.
- Após isso, conecte o seu certificado e se certifique do funcionamento da plataforma.

## Parte 4: Lidando com erros

Note que, como o PJe é programado em Java, uma linguagem que tem infinitas versões diferentes, com frequência ele encontra algum erro. Muitas das vezes nem vai fazer sentido.

Pela nossa experiência até agora, o melhor a se fazer em caso de falhas é simplesmente desinstalar tudo e reinstalar de volta. Isso inclui remover os drivers do token, a versão do Java, o PJe e tudo o mais que for relacionado.

De seguida, ao reinstalar _todas_ as aplicações, normalmente o PJe volta a funcionar.