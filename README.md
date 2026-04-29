

# ⚽ ihcux-copa-2026

## 👥 Integrantes

* Victor Teodoro
* Ana Luiza
* Emanuelle Laporte

---

## 🎯 Problema Focado

O principal problema priorizado foi a **perda de lances importantes e o tempo gasto em filas**, especialmente quando o torcedor precisa sair do assento para comprar comida ou se localizar no estádio.

Também consideramos:

* Dificuldade de encontrar setores e portões
* Ambientes cheios, barulhentos e com alta distração

---

## 💡 Justificativa de Design

O design foi pensado para uso em um ambiente caótico (estádio cheio), priorizando:

* **Botões grandes** → fácil clique mesmo distraído
* **Pouco texto e alta clareza visual** → leitura rápida
* **Hierarquia clara** → informações importantes no topo
* **Acesso rápido às funções principais**:

  * Replay
  * Mapa
  * Comida
  * Ingresso

### Decisões importantes:

* O **placar ao vivo fica na tela inicial** → informação mais importante
* O **QR Code do ingresso fica centralizado** → acesso rápido na entrada
* Os **replays mais recentes aparecem primeiro** → evita perder momentos importantes
* O **mapa mostra a localização atual do usuário** → reduz confusão no estádio

---

## 🔄 Fluxo do Usuário

### 🍔 Pedir um lanche:

1. Usuário acessa a **Home**
2. Clica em **"Comida"**
3. Visualiza o **Cardápio**
4. Seleciona os itens
5. Vai para o **Carrinho**
6. Confirma o pedido
7. Recebe notificação quando estiver pronto

---

### 🎥 Ver um replay:

1. Usuário acessa a **Home**
2. Clica em **"Replays"**
3. Visualiza os **lances recentes**
4. Seleciona o vídeo
5. Assiste de diferentes ângulos

---

## 🧠 Reflexão de IHC

Em um estádio, o usuário enfrenta distrações constantes como barulho, emoção e iluminação intensa.

Para garantir que ele não se perca no fluxo:

* O layout utiliza **elementos grandes e bem espaçados**
* A navegação é **simples e direta (máximo 2-3 cliques)**
* As informações críticas são sempre **priorizadas no topo da tela**
* Ícones ajudam no reconhecimento rápido, mesmo sem leitura completa
* O design evita sobrecarga cognitiva, mostrando apenas o essencial

