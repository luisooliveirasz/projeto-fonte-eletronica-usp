# Projeto Fonte de Tensão Ajustável - 3V a 12V; 100mA;

> Projeto desenvolvido para a disciplina de Eletrônica — [Instituição] · [Semestre/Ano]

---

## Integrantes

| Nome | NUSP |
|------|------|
| Nome do Aluno 1 | xxxxxxx |
| Nome do Aluno 2 | xxxxxxx |
| Nome do Aluno 3 | xxxxxxx |

---

## Descrição do Projeto

Breve descrição da fonte: tensão de entrada, tensão de saída, corrente máxima, tipo de regulação (linear, chaveada etc.) e objetivo do projeto.

> **Exemplo:** Fonte de tensão ajustável de 3V a 12V com corrente máxima de 1A, a partir de uma entrada AC de 127V/60Hz.

---

## Diagrama da Fonte

![Diagrama do Circuito](./imagens/diagrama_fonte.png)

> _Substitua pela imagem do seu diagrama com os valores dos componentes indicados._

---

## Lista de Componentes

| Qtd | Componente | Valor / Especificação | Preço Unitário | Preço Total |
|-----|------------|----------------------|----------------|-------------|
| 1 | Transformador | 127V → 24V / 1A | R$ 00,00 | R$ 00,00 |
| 4 | Diodo retificador | 1N4007 | R$ 00,00 | R$ 00,00 |
| 1 | Capacitor eletrolítico | 1000 µF / 50V | R$ 00,00 | R$ 00,00 |
| 1 | Capacitor cerâmico | 100 nF | R$ 00,00 | R$ 00,00 |
| 1 | Regulador de tensão | LM7812 / LM317 | R$ 00,00 | R$ 00,00 |
| 1 | Resistor | 220 Ω / ½W | R$ 00,00 | R$ 00,00 |
| 1 | Resistor | 1 kΩ / ½W | R$ 00,00 | R$ 00,00 |
| 1 | LED indicador | Vermelho 5mm | R$ 00,00 | R$ 00,00 |
| ... | ... | ... | ... | ... |
| | | | **Total** | **R$ 00,00** |

---

## Justificativa dos Valores Escolhidos

Explique aqui o raciocínio por trás da escolha de cada componente principal:

- **Transformador:** _Por que essa relação de transformação? Qual a tensão de pico esperada?_
- **Capacitor de filtro:** _Como foi calculada a capacitância mínima? Qual o ripple aceito?_
- **Regulador:** _Por que esse CI? Quais os limites de tensão/corrente?_
- **Resistores:** _Como foram calculados os valores para o ajuste de tensão?_

---

## Simulação no Falstad

Acesse o circuito simulado clicando no link abaixo:

🔗 **[Abrir simulação no Falstad](https://www.falstad.com/circuit/circuitjs.html?ctz=COLE_SEU_LINK_AQUI)**

> _Para gerar o link: no Falstad, vá em **File → Export as Link** e cole aqui._

---

## Projeto no EAGLE

Os arquivos do esquemático e da PCB estão disponíveis na pasta [`/eagle`](./eagle/):

```
eagle/
├── fonte.sch        # Esquemático
├── fonte.brd        # Layout da PCB
└── fonte.pdf        # Exportação em PDF
```

### Esquemático

![Esquemático EAGLE](./imagens/esquematico_eagle.png)

### Layout da PCB

![PCB EAGLE](./imagens/pcb_eagle.png)

---

## 📸 Fotos do Circuito Montado

### Protoboard

![Protoboard 1](./imagens/protoboard_01.jpg)

![Protoboard 2](./imagens/protoboard_02.jpg)

### Placa Final (PCB)

![PCB montada](./imagens/placa_montada.jpg)

> _Adicione quantas fotos achar necessário. Recomendado: frente, verso, e detalhe dos componentes._

---

## Vídeo do Projeto

Assista ao vídeo de apresentação do projeto, onde explicamos o funcionamento, a simulação e a justificativa dos valores escolhidos:

[![Thumbnail do Vídeo](./imagens/thumbnail_video.png)](https://www.youtube.com/watch?v=SEU_LINK_AQUI)

🔗 **[Assistir no YouTube](https://www.youtube.com/watch?v=SEU_LINK_AQUI)**  
_(ou [Google Drive](https://drive.google.com/SEU_LINK_AQUI) caso prefira)_

**O vídeo cobre:**
- Demonstração da simulação no Falstad
- Explicação dos cálculos e escolha dos componentes
- Funcionamento do circuito real na protoboard/placa
- Medições com multímetro

---

## Estrutura do Repositório

```
/
├── README.md
├── eagle/
│   ├── fonte.sch
│   ├── fonte.brd
│   └── fonte.pdf
└── imagens/
    ├── diagrama_fonte.png
    ├── esquematico_eagle.png
    ├── pcb_eagle.png
    ├── protoboard_01.jpg
    ├── protoboard_02.jpg
    ├── placa_montada.jpg
    └── thumbnail_video.png
```

---

## 📚 Referências

- [Datasheet — LM317](https://www.ti.com/product/LM317)
- [Datasheet — 1N4007](https://www.vishay.com/docs/88503/1n4001.pdf)
- [Simulador Falstad](https://www.falstad.com/circuit/)
- [EAGLE — Autodesk](https://www.autodesk.com/products/eagle/overview)
- _Adicione livros, slides da disciplina ou outros materiais consultados_
