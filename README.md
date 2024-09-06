# Monitoramento de Luminosidade e Controle de LED com ESP32 usando FIWARE

Neste projeto, exploramos o controle de um LED e o monitoramento da luminosidade por meio de um sensor LDR, utilizando a placa ESP32. Integramos tecnologias modernas como FIWARE e Postman para realizar testes e monitoramento de dispositivos.

## Descrição do Projeto

Este projeto demonstra como utilizar a plataforma FIWARE como back-end para uma solução de monitoramento global, aplicável em vinícolas, por exemplo. Utilizamos a placa ESP32 para enviar dados de luminosidade captados pelo sensor LDR e receber comandos para ligar ou desligar o LED embutido, tudo isso usando uma configuração virtual e ferramentas como Docker e Postman.

## Funcionalidades

- Monitoramento em tempo real da luminosidade do ambiente através de um sensor LDR.
- Controle remoto do LED embutido na placa ESP32 (ligar e desligar) via Postman.
- Integração com a plataforma FIWARE para gestão e análise de dados.

## Tecnologias Utilizadas

- **Hardware e Simulação**: ESP32, Sensor LDR, Simulador Wokwi
- **Ambiente de Desenvolvimento**: IDE do Arduino, Postman, Git e GitHub
- **Infraestrutura Virtual**: Máquinas Virtuais (AWS, Azure, etc.), Docker
- **Plataforma de Back-end**: FIWARE

## Passo a Passo para Instalação

1. **Clonar o Repositório**  
   Acesse o [repositório do FIWARE](https://github.com/fabiocabrini/fiware) no GitHub para encontrar o código base e instruções detalhadas.

2. **Instalar o Postman**  
   Baixe e instale o [Postman](https://www.postman.com/downloads/) para enviar requisições e monitorar respostas, facilitando o controle remoto dos dispositivos.

3. **Configurar a Máquina Virtual**  
   - Instale uma máquina virtual utilizando seu provedor de serviços preferido (recomenda-se AWS ou Microsoft Azure).
   - Use a ISO do **Ubuntu Server LTS** para configurar o ambiente.

4. **Liberar as Portas Necessárias**  
   Certifique-se de liberar as seguintes portas para o funcionamento correto do FIWARE: `1026`, `1883`, `4041`, `8666`, `27017`.

5. **Instalar o Git e Docker**  
   - Instale o **Git** para gerenciamento de versão.
   - Instale o **Docker** para rodar containers com os componentes do FIWARE, facilitando a orquestração dos serviços.

6. **Clonar o Repositório do Projeto**  
   Clone o repositório com o comando:  
   ```bash
   git clone https://github.com/fabiocabrini/fiware
   ```

7. **Configurar o Docker**  
   Inicie o Docker como usuário root para evitar problemas de permissão.

8. **Configurar o Postman**  
   Configure as requisições no Postman para o controle do LED e a leitura da luminosidade. Envie comandos para ligar ou desligar o LED e receba informações do sensor de luminosidade em tempo real.

9. **Utilizar o Simulador Wokwi**  
   Acesse o [simulador Wokwi](https://wokwi.com/projects/408215648474161153) para visualizar o circuito do LED e do LDR em um ambiente virtual e realizar ajustes conforme necessário.

## Uso

Com o ambiente configurado, você poderá:

- Monitorar a luminosidade do ambiente utilizando o sensor LDR.
- Controlar remotamente o LED embutido na placa ESP32 por meio de comandos enviados pelo Postman.

## Conclusão

Este projeto é uma ótima demonstração de como integrar diferentes tecnologias para criar soluções IoT, utilizando ferramentas como FIWARE, Docker, Postman e simuladores online.

## Contato

Para mais informações e tutoriais, assista ao vídeo completo em nosso canal do YouTube: [Mindflayers](https://www.youtube.com/@Mindflayers-rk6wq)

Esperamos que este README seja útil para entender como configurar e utilizar o projeto de monitoramento e controle com ESP32, FIWARE e outras ferramentas.
