# Sistema de Meios de Transporte

Este projeto implementa um sistema para gerenciar o aluguel de meios de transporte individuais utilizando o padrão de projeto **Abstract Factory**. O objetivo do sistema é permitir a criação de diferentes meios de transporte classificados em duas categorias: **movidos a bateria** e **movidos pelo esforço humano**.


## Visão Geral

Este sistema gerencia diferentes meios de transporte e foi implementado utilizando o padrão de projeto **Abstract Factory**. O sistema é dividido em duas categorias de transporte:

- **Movidos a Bateria**: Patinetes elétricos, bicicletas elétricas.
- **Movidos pelo Esforço Humano**: Bicicletas convencionais, patins, skates.

Através do padrão **Abstract Factory**, o código permite criar objetos de transporte sem precisar se preocupar com a implementação de cada tipo específico. O sistema faz uso de fábricas concretas para produzir transportes de acordo com sua categoria de propulsão.

## Estrutura do Projeto

O projeto segue a estrutura padrão para código Java, com uma separação clara entre interfaces, classes concretas e fábricas. Abaixo está a estrutura de diretórios do projeto:

        / ├── src/ │
        └── com/ │ └── example/ │ └── transport/ │
          
          │ ├── Transport.java 
          
          ├── ElectricScooter.java
          
          │ ├── ElectricBike.java 
          
          ├── Bicycle.java 
          
          │ ├── RollerSkates.java
          
          │ ├── Skateboard.java 
          
          │ ├── TransportFactory.java 
          
          │ ├── ElectricTransportFactory.java 
          
          │ ├── HumanPoweredTransportFactory.java 
          
          │ └── Main.java 


# Execução do codigo no terminal
![Captura de tela de 2024-11-27 16-36-25](https://github.com/user-attachments/assets/4814093a-d70f-459b-8493-2e05ef0eed2a)

          
