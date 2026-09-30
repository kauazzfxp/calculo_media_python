Sistema simples desenvolvido em Python para calcular a média de um aluno e informar se ele foi aprovado ou reprovado.

## Tecnologias Utilizadas

- Python 3
- Função calcular_media()
- Estrutura condicional if/else
- Entrada de dados com input()

## Como Instalar e Executar

### 1. Instale o Python

Baixe e instale o Python 3 no computador.

### 2. Crie o arquivo

Crie um arquivo chamado:

notas.py

### 3. Adicione o código

```python
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2

print("=== Sistema de Notas do Aluno ===")
n1 = float(input("Digite a primeira nota: "))
n2 = float(input("Digite a segunda nota: "))

media = calcular_media(n1, n2)
print(f"Média final: {media:.2f}")

if media >= 7.0:
    print("Status: APROVADO!")
else:
    print("Status: REPROVADO.")

    ### 3. Exemplo de Uso

=== Sistema de Notas do Aluno ===
Digite a primeira nota: 8
Digite a segunda nota: 6

Média final: 7.00
Status: APROVADO!


### 4. Autor e Contato

## Autor e Contato

*Kauã Trindade Lima*
E-mail: kauanzinbr.canal@gmail.com  
