<h1 align="center">
 <a href="https://www.bovcontrol.com/">
   🐮 BovControl
 </a>
</h1>

Olá, nós somos a Bovcontrol!

E nós estamos revolucionando o agribusiness no mundo!

Somos a 3ª startup mais inovadora, segundo a Startse.

Somos uma startup global que vem conectando todas as vacas e fazendas do planeta numa 'nuvem diferente' (antes do modismo do blockchain) - com o objetivo de erradicar a fome no mundo, empoderando produtores rurais com tecnologia para serem mais eficientes e sustentáveis. Nossas soluções combinam coleta e a análise de dados, para toda a cadeia produtiva.

Os dados são coletados no campo por aplicativos móveis e podem ser analisados por vários meios, por diferentes elos da cadeia (varejo, bancos, processadores de leite, etc).

Alimentar 1 bilhão de pessoas por dia, em 10 anos de existência da empresa, é a nossa meta.

## O que esperamos?

Você deve ser capaz de:

- Estruturar
- Estilizar
- Conectar
- Manipular dados

Estaremos analisando a sua organização de código, a sua perícia em manipular elementos React-Native a nível de estilização e controle de estado por meio de *states* e *props*.

Como estaremos analisando esses requisitos deixamos que o design seja **decidido por você. Capriche :)**

## **Sobre o desafio 🤯**

- O fazendeiro poderá gerenciar seus checklists de forma online ou offline.
- Aplicação deve permitir que checklists sejam criados ou atualizados independente da sua conexão de internet;
- Aplicação deve conter uma tela inicial, contendo todos os checklists (contendo o nome do fazendeiro, nome e cidade da fazenda, além da data de criação do checklist) já cadastrados na API. Uma tela para visualizar todas as informações do checklist selecionado. Outra tela para cadastro do checklist, e por fim, outra tela para atualização dos dados.
- Para criação do checklist será necessário fornecer os seguintes dados: Nome do fazendeiro, nome e cidade da fazenda, nome do supervisor, tipo do checklist (BPA, Antibiótico, BPF), quantidade de leite produzida no mês, quantidade de cabeça de gado e um booleano informando se teve supervisão no mês em curso (na criação deve registrar a data de criação e atualização para histórico).
- Para atualização do checklist será necessário fornecer os seguintes dados: Nome do fazendeiro, nome e cidade da fazenda, nome do supervisor, quantidade de leite produzida no mês, quantidade de cabeça de gado (na atualização deve registrar a data de atualização).
- Caso algum checklist seja atualizado/criado em offline, deverá mostrar o checklist criado/atualizado, ao estabelecer conexão com a internet deve sincronizar os checklists com a API.

## **Requisitos 😇**

- Libraries and patterns
- React-native 0.65 ou superior. (Fique a vontade para utilizar o expo)
- **UTILIZE STYLED COMPONENTS**
- Hooks
- ContextAPI
- Banco de Dados ([RealmDB](https://docs.mongodb.com/realm/sdk/react-native/))

## API do desafio

- Para desenvolver esse desafio, será necessário utilizar o JSON API (link de referência: [https://jsonapi.org/](https://jsonapi.org/)). O mesmo irá simular um backend para realizar CRUD dos checklists.
- Dentro do seu projeto deverá criar um arquivo chamado **db.json** e deverá conter a estrutura inicial abaixo:

```
{
  "checklists": [ // Array de checklists
   {
    "id": "1", // Identificação única
    "type": "BPA", // Tipo de checklist
    "amount_of_milk_produced": "300", // Quantidade de produção de leite
    "number_of_cows_head": "17", // Quantidade de vacas
    "had_supervision": true, // Flag para identificar se teve supervisão
    "farmer": { // Dados da fazenda
     "name": "Fazenda São Rock",
     "city": "São Rock",
    },
    "from": {
     "name": "Luciano Camargo" // Nome do fazendeiro
    },
    "to": {
     "name": "Fernando Siqueira" // Nome do supervisor
    },
    "created_at": "2022-02-01T10:10:21.748Z", // Data de criação
    "updated_at": "2022-02-01T10:10:21.748Z", // Data de atualização
   }
],
}
```

## **Prazo de entrega 🤓**

O desafio deve ser realizado em 72 horas a partir da data de envio do desafio.

Caso tenha algum imprevisto avise com antecedência o encarregado do desafio.

Boa sorte!

> Inteligência é a capacidade de se adaptar a mudança - Stephen Hawking
