# Sistema de Gerenciamento de Veículos

Este projeto é um sistema básico de gerenciamento de veículos, desenvolvido em Java, que utiliza conceitos de **Orientação a Objetos** como herança, encapsulamento e classes abstratas. O sistema permite gerenciar informações de diferentes tipos de veículos, como carros e motos.

---

## O que é o projeto?

O sistema contém as seguintes funcionalidades:

- **Classe `Veiculo`**: Uma classe abstrata que serve como base para veículos.
- **Classe `Carro`**: Representa carros, com atributos específicos como o número de portas.
- **Classe `Moto`**: Representa motos, com atributos específicos como a cilindrada.
- **Classe `Main`**: Realiza a interação principal do programa, criando instâncias de `Carro` e `Moto`, definindo seus atributos e exibindo suas informações.

---

# Para iniciar o programa:

1. Compile os arquivos:
  javac Veiculo.java Carro.java Moto.java Main.java

2. Execute o programa:
  java Main

# Saída Esperada

   Carro - Marca: Toyota, Modelo: Corolla, Ano: 2020, Número de Portas: 4
   Moto - Marca: Honda, Modelo: CB500, Ano: 2022, Cilindrada: 500cc
