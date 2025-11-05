# 💱 ConvErt Maney

![HTML Badge](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS Badge](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)
![JavaScript Badge](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/license-livre-green?style=for-the-badge)

Um conversor de moedas simples e funcional desenvolvido em **HTML**, **CSS** e **JavaScript**, que utiliza a **API da AwesomeAPI** para buscar as cotações em tempo real.

---

## 🚀 Funcionalidades

✅ Conversão entre **Real (BRL)** e:

* Dólar Americano (USD)
* Euro (EUR)
* Libra Esterlina (GBP)
* Bitcoin (BTC)

✅ Atualização automática da taxa de câmbio.
✅ Interface responsiva e amigável.
✅ Exibição dos valores formatados com símbolo e padrão monetário corretos.
✅ Alteração dinâmica do nome e bandeira conforme a moeda selecionada.

---

## 🧠 Tecnologias Utilizadas

| Área         | Tecnologias                                                           |
| ------------ | --------------------------------------------------------------------- |
| **Frontend** | HTML5, CSS3, JavaScript (ES6+)                                        |
| **API**      | [AwesomeAPI - Cotações](https://docs.awesomeapi.com.br/api-de-moedas) |
| **Design**   | Google Fonts (Roboto), imagens ilustrativas, ícones de bandeiras      |

---

## 🖥️ Como Usar

1. Clone ou baixe o projeto:

   ```bash
   git clone https://github.com/glaylson87/convert-maney.git
   ```
2. Abra o arquivo `index.html` no navegador.
3. Escolha a moeda desejada e insira o valor em reais.
4. Clique em **“Converter”** para ver o resultado!

---

## 🔗 API Utilizada

A aplicação consome dados da AwesomeAPI através do endpoint:

```
https://economia.awesomeapi.com.br/last/USD-BRL,EUR-BRL,GBP-BRL,BTC-BRL
```

Exemplo de retorno:

```json
{
  "USDBRL": {
    "high": "5.612",
    "low": "5.520",
    "bid": "5.575"
  },
  "EURBRL": { ... },
  "GBPBRL": { ... },
  "BTCBRL": { ... }
}
```

---

## 📱 Layout

| Tela Inicial                             | Conversão Exemplo                            |
| ---------------------------------------- | -------------------------------------------- |
| ![Tela Inicial](./assets/gifprojeto.gif) | ![Conversão](./assets/exemplo-conversao.png) |

---

## 🧑‍💻 Autor

**Glaylson Guedes**
💼 Estudante de Análise e Desenvolvimento de Sistemas
📍 Brasil
📧 [etelvino88@gmail.com](mailto:etelvino88@gmail.com)
🌐 [GitHub - glaylson87](https://github.com/glaylson87)

---

## 🏗️ Melhorias Futuras

* Modo escuro/claro 🌙
* Gráfico de variação da moeda 📊
* Histórico de conversões 💾
* Integração com outras moedas 🌍

---

## 🪙 Licença

Este projeto é de uso livre para fins educacionais.
Créditos das cotações: [AwesomeAPI](https://docs.awesomeapi.com.br/).
