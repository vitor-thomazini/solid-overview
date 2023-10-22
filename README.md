# SOLID 

> **[Certificado de conclusão do curso](./assets/certification.pdf)**

## 1 Visão Geral

O termo **SOLID** é um acrônimo de cinco items:

- **SRP (Single Responsibility Principle):** Uma classe deve ter uma única responsabilidade, isto é, um único motivo para existir e/ou para ser modificado.

- **OCP (Open-Closed Principle):** Toda a classe deve ser aberta para extensão e fechada para modificação.

- **LSP (Liskov Substitution Principle):** Subclasses podem ser substituídas por suas classes pais. Seria uma definição oposta a frase "Um não pode viver enquanto o outro estiver vivo".

- **ISP (Interface Segregation Principle):** Uma classe não é obrigada a implementar interfaces com métodos que ela não utiliza.

- **DIP (Dependence Inversion Principle):** Consiste em depender de uma abstração e não de uma implementação, pois toda vez que é instanciado uma classe (A) com implementações dentro de uma outra classe (B) de implementação está sendo criado um forte acoplamento entre as classes, para contornar isto seria necessário criar uma abstração para a classe (B) e assim utiliza-la dentro da classe (A). Normalmente este principio está diretamente relacionado ao Interface Segregation Principle.

