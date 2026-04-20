# 🚖 No Caminho Certo — Calculadora de Corridas

Ferramenta inteligente criada para motoristas que desejam calcular, de forma rápida e precisa, os **custos reais de uma corrida**. O sistema utiliza mapas gratuitos, rotas automáticas, reconhecimento de voz e cálculos completos de custos e lucros, tudo diretamente no navegador.

---

## 🚧 Status do Projeto

⚠️ **Este projeto está em desenvolvimento.**

A ferramenta está sendo **melhorada continuamente**, com novos recursos e ajustes sendo adicionados regularmente.
Embora **ainda não esteja 100% finalizada**, a aplicação **já pode ser utilizada normalmente** para cálculos de corridas e testes.

Sugestões, melhorias e feedback são sempre bem-vindos para ajudar na evolução do projeto.

---

## ✨ Funcionalidades

* Cálculo automático de rota usando **OpenStreetMap + OSRM**
* Distância total **ida e volta** medida no mapa
* Geocodificação de endereços com **Nominatim**
* Reconhecimento de voz nos campos de **origem** e **destino**
* Cálculo completo de:

  * Litros consumidos
  * Custo total da corrida
  * Custo por quilômetro
  * Valor cobrado
  * Valor cobrado por quilômetro
  * Lucro ou prejuízo
* Botão para limpar rota
* Botão para limpar todos os campos
* Interface **responsiva**, otimizada para celular
* Funciona **sem servidor** e sem backend

---

## 🗺️ Tecnologias Utilizadas

* HTML
* CSS
* JavaScript
* **Leaflet** para exibição do mapa
* **OpenStreetMap** para os tiles
* **OSRM** para cálculo de rotas
* **Nominatim** para conversão de texto em coordenadas
* Reconhecimento de voz com `webkitSpeechRecognition`

---

## 🚀 Como Funciona o Cálculo

1. O usuário digita ou fala a origem e o destino
2. O sistema:

   * Converte os endereços em coordenadas
   * Calcula a rota automaticamente
   * Soma a distância de ida e volta
   * Calcula litros consumidos, custos e resultado final

Todo o processamento acontece **localmente no navegador**, sem envio de dados para servidores próprios.

---

## 🌐 Versão Online

O sistema pode ser utilizado diretamente no navegador:

👉 (https://calculadoradcorridas.netlify.app/)

---

## 📦 Como Usar Localmente

1. Baixe ou clone este repositório
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. Pronto. O sistema já estará funcionando

---

## 📁 Estrutura do Projeto

```
calculadora-corridas/
│ index.html
│ README.md
│ (demais arquivos serão adicionados futuramente)
```

Atualmente, o projeto funciona em **um único arquivo HTML integrado**.

---

## 📣 Aviso Importante

Os valores apresentados são **estimativas**, pois dependem das informações fornecidas pelo usuário, como:

* Média de consumo do veículo
* Preço do combustível

Para maior precisão, mantenha esses dados sempre atualizados.

---

## 👤 Autor

**Claudio Almeida.CAAS**

Ferramenta criada para ajudar motoristas a entender melhor seus custos, tomar decisões mais conscientes e organizar sua rotina de trabalho.

> *Use com responsabilidade e ética.*
