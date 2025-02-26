# 🍼 **Baby Guard** 🎶

Este projeto consiste no desenvolvimento de uma **Babá Eletrônica** utilizando a placa **BitDogLab**. O sistema é capaz de monitorar sons no ambiente e, com base nesses sons, realizar ações específicas, como exibir informações no display OLED, acionar alertas visuais por meio de LEDs RGB e emitir alertas sonoros através de um buzzer.


## 🎯 **Objetivos do Projeto**

O projeto tem como objetivo desenvolver uma **Babá Eletrônica** que proporcione monitoramento eficiente e em tempo real do ambiente, com as seguintes funcionalidades:

1. **Monitoramento de Sons**: 🎤 Detectar sons no ambiente e responder a esses estímulos.
2. **Feedback Visual e Auditivo**: 💡🔊 Fornecer feedback sobre o estado do ambiente monitorado.
3. **Interface de Controle**: 🎛️ Permitir ativar e desativar a detecção de som de maneira simples.
4. **Confiabilidade**: 🛡️ Assegurar a operação contínua e eficiente do sistema.


## 🛠️ **Funcionalidades do Projeto**

### 1. **Detecção de Som** 🎤
- **Identificação de Ruídos**: O sistema utiliza um microfone analógico para monitorar sons no ambiente. Quando detecta ruídos, como o choro de um bebê, o sistema reage imediatamente.
- **Sensibilidade do Microfone**: O microfone é ajustado para garantir que apenas ruídos significativos sejam detectados, minimizando falsos alarmes.

### 2. **Reprodução de Melodia** 🎶
- **Melodia ao Detectar Som**: Quando um som é detectado, o sistema reproduz a melodia "Brilha, Brilha Estrelinha" no buzzer.
- **Qualidade do Som**: O buzzer é calibrado para garantir que a melodia seja audível e agradável.

### 3. **Indicadores Visuais** 💡
- **LEDs RGB**: O sistema utiliza LEDs RGB para fornecer feedback visual:
  - **🔵 Azul**: Indica que o sistema está aguardando ativação.
  - **🟢 Verde**: Indica que o sistema está ativo e monitorando.
  - **🔴 Vermelho**: Indica que um som foi detectado.

### 4. **Controle por Botões** 🎛️
- **Botão A**: Ativa o sistema de detecção de som.
- **Botão B**: Desativa o sistema de detecção de som.

### 5. **Display OLED** 📺
- **Exibição de Informações**: O display OLED exibe mensagens sobre o status do sistema, como "Sistema Ativo" ou "Som Detectado".


## 🧩 **Componentes Utilizados**

- **BitDogLab**: Placa com Raspberry Pi Pico W, microfone, display OLED, LEDs RGB, buzzer e botões.


## 🚀 **Como Executar o Projeto**

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/garccias/baby_guard
   ```
2. **Abra o projeto no VS Code**:
   - Certifique-se de ter o Pico SDK instalado e configurado.
3. **Compile e carregue o código**:
   - Utilize o CMake para compilar o projeto e carregue o firmware na BitDogLab.
4. **Execute o sistema**:
   - Conecte a BitDogLab e observe o funcionamento da babá eletrônica.

