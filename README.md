# Calculadora em Python

## Descrição

Este projeto consiste em uma calculadora simples desenvolvida em Python. O programa permite ao usuário realizar operações matemáticas básicas por meio de um menu interativo no terminal.

## Funcionalidades

- Adição
- Subtração
- Multiplicação
- Divisão
- Validação para evitar divisão por zero
- Permite realizar várias operações sem reiniciar o programa

## Arquivos do projeto

- `calculadora.py` → Código principal da calculadora.
- `executar.sh` → Arquivo para executar o programa (será criado posteriormente).
- `README.md` → Documentação do projeto.

## Como o código funciona

1. O programa solicita ao usuário dois números.
2. Exibe um menu com as operações disponíveis.
3. O usuário escolhe a operação desejada.
4. O programa realiza o cálculo e mostra o resultado.
5. Ao final, pergunta se o usuário deseja realizar outra operação.
6. Caso a resposta seja **"s"**, uma nova operação é iniciada. Caso contrário, o programa é encerrado.

## Como executar

### Executando diretamente com Python

```bash
python calculadora.py
```

ou, dependendo da instalação do Python:

```bash
python3 calculadora.py
```

### Executando pelo arquivo `.sh`

Após criar o arquivo `executar.sh`, execute:

```bash
chmod +x executar.sh
./executar.sh
```

## Tecnologias utilizadas

- Python 3

## Autor

Daniela Lozada
