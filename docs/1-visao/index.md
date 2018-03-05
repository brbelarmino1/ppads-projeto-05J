# Documento de Visão do Projeto "Aplicativo de utilidades"

Este documento apresenta uma solução de software para o projeto Utilidade, solicitado pelo cliente Tomaz Mikio Sasaki, apresentando os problemas a serem solucionados, as necessidades dos principais envolvidos, o alcance do projeto e as funcionalidades esperadas do sistema.

## Objetivos

O sistema tem por objetivo integrar de forma inteligente qualquer pessoa que esteja precisando de algum tipo de serviço de utilidades em geral e o profissional a executar esta demanda, visando estreitar a comunicação entre contratante e contratado, garantir transparência durante todo o decorrer do processo, desde a escolha do profissional até a finalização do serviço prestado por este, e assegurar a qualidade do serviço prestado.

## Problema

* Descrição do problema: Necessidade de encontrar um profissional que presta serviços de utilidade e contratar alguém confiável. Da mesma forma, um profissional desta categoria, encontrar algum cliente.
* Quem é afetado pelo problema: Pessoas que de repente estejam precisando de algum serviço dentre os disponiveis no aplicativo.
* Impacto no negócio: Busca por um profissional, contratação, mão de obra, pagamento, indicação.
* Benefícios de uma boa solução: Praticidade, facilitador ao buscar o serviço desejado, ajuda a promover o trabalho do profissional.

## Definições, abreviações e outros termos do domínio do problema

* Serviços de utilidade: Chaveiro, encanador, eletricista, marceneiro, pedreiro, etc.
* Estreitar a comunicação: oferecer o serviço, negociar, planejar, monitorar execução dos serviços específicos, avisar ao cliente do andamento, controlar compras de materiais, emitir nota fiscal, controlar recebimentos e pagamentos, justificar avaliação. 
* Processo: Refere-se ao tempo cronológico de execução do serviço contratado, desde o momento da escolha do profissional até a interação final, a avaliação. 

## Integração com outros sistemas

* O Aplicativo de Utilidades não tem integração com outros sistemas.
 
## Interessados

* Analista de Requisitos: Profissional que levanta quais são as regras necessárias para o funcionamento da aplicação.
É responsável por entender do cenário como um todo e sobre isso aplicar sua visão técnica como analista. 
É envolvido por:	
. Entender o caso;
. Definir cenário;
. Definir e escrever regras;
. Criar funcionalidades;
. Pode atuar como gestor da ferramenta.

* Desenvolvedor: Profissional que atua na criação efetiva da aplicação.
É responsável por escrever o código de toda a lógica do funcionamento em linguagem de programação, utilizando as tecnologias disponíveis neste mercado:
É envolvido por:
. Atribuir para o código a regra descrita na especificação;
. Implementar as soluções;
. Integrar componentes necessários;
. Responsável pela base de dados.

* Profissional que faz a validação das funcionalidades da aplicação. 
É responsável por validar se de fato tudo o que foi descrito na especificação foi implementado no código. 
É envolvido por:
. Verificar a correlação entre especificação e desenvolvimento;
. Encontrar falhas, erros, possiveis melhorias;
. Apontar correção nas regras;
. Apontar correções no código;
. Assegurar qualidade no funcionamento. 

* Analista de Produção
Linha de comunicação e frente direta com o usuário, intermediador do contato com parte técnica (analista de requisitos, desenvolvedor, analista de teste)
É responsável por assegurar o funcionamento da aplicação em ambiente de produção, sendo este o que efetivamente o cliente utiliza.
É envolvido por:
. Configurar o funcionamento em ambiente de produção;
. Primeira comunicação quando o cliente entra em contato;
. Monitora o ambiente;
. Conhecimento também da parte técnica.

## Usuários

* Cliente: Quem necessita do serviço
. Cliente faz a escolha do tipo de serviço que precisa;
. Escolhe profissional;
. Acompanha  o andamento do serviço;
. Faz pagamento;
. Avalia profissional.

* Profissional: Aquele que oferece seu trabalho como forma de auxílio ao cliente. 
. Prestar serviço solicitado;
. Seguir cronograma;
. Ser pontual;
. Buscar excelência, visando boa avaliação. 

## Funcionalidades do produto

* Cadastro: Permite cadastrar na base de dados da aplicação clientes e profissionais.

* Busca: Permite que um cliente possa buscar um profissional que atenda sua necessidade em um serviço de utilidade, e permite que o profissional busque um cliente que necessite dos serviços que ele tem à oferecer.

* Contato: São informados dados do profissional para que possa ser feito contato entre ambas as partes.

* Monitoramento: Permite que o cliente monitore o contratado durante todo o processo de execução do seu trabalho.

* Pagamento: Formaliza o pagamento pelo serviço prestado.

* Avaliação: Funcionalidade onde o cliente pode atribuir uma nota ao profissional que lhe prestou serviço.

## Restrições do projeto

* Prazo: 6 meses.
* Sistema Operacional: Android, Windows.
* Hardware: smartphone.
* Permitir acessar câmera, imagens.
* Obrigatória conexão com internet para busca do profissional.
* Consultar acompanhamento poderá ser off-line.

## Protótipos de tela

### Protótipos para funcionalidade Cadastro

![](Tela02Cadastro.png)
![](Tela03Perfis.png)
![](Tela04Menu.png)

### Protótipos para funcionalidade Busca

![](Tela05Cliente.png)
![](Tela06BuscarProfissional.png)

### Protótipos para funcionalidade Contato

![](Tela07ContatoProfissional.png)

### Protótipos para funcionalidade Monitoramento

![](Tela08Acompanhamento.png)
![](Tela11Fornecedor.png)
![](Tela12RegistroDeAtividades.png)

### Protótipos para funcionalidade Pagamento

![](Tela09Pagamento.png)
![](Tela10Confirmação.png)
![](Tela13ConfirmarComprovante.png)
![](Tela14ServiçoFinalizado.png)

### Protótipos para funcionalidade Avaliação

![](Tela10Confirmação.png)
![](Tela14ServiçoFinalizado.png)
