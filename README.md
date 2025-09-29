# Fundamentos Jetpack Compose Listas Lazy

Este projeto é um aplicativo Android desenvolvido em **Kotlin**, utilizando **Jetpack Compose** para a construção de interfaces modernas e reativas.  
O objetivo principal é demonstrar o uso de **listas Lazy** (`LazyColumn` e `LazyRow`) para exibir e filtrar jogos favoritos por estúdio.

---

## 👥 Integrantes da Equipe
- Gustavo Matos – RM: 551268
- Leonardo Franco – RM: 552528
- Heitor Novaes – RM: 98342

---

## Funcionalidades

- Exibição de uma lista de jogos favoritos (`LazyColumn`).
- Filtro de jogos por **nome do estúdio** via campo de texto.
- Filtro de jogos por **seleção de estúdio** em lista horizontal (`LazyRow`).
- Exibição de botão **“Limpar filtro”** sempre que um filtro estiver ativo.
- Ao clicar no botão **“Limpar filtro”**, o filtro aplicado é removido.
- Interface construída com **Material 3**.

## 🧱 Estrutura (resumo)
- `app/src/main/java/.../MainActivity.kt` – ponto de entrada / composição da tela  
- `components/GameCard.kt` – card de jogo  
- `components/StudioCard.kt` – card de estúdio (usado na LazyRow)  
- `model/Game.kt` – data class  
- `repository/GameRepository.kt` – dados + filtro  
- `ui/theme/` – tema Material 3

---

## Como funciona

- A tela principal exibe uma lista de jogos e uma lista horizontal de estúdios.
- O usuário pode filtrar os jogos digitando o nome do estúdio ou clicando em um StudioCard.
- O filtro pode ser limpo facilmente com o botão "Limpar filtro".

## Como rodar o projeto

1. Clone este repositório:
   ```sh
   git clone <url-do-repositorio>
   ```
2. Abra o projeto no Android Studio.
3. Execute em um emulador ou dispositivo físico Android.

> 💡 Caso utilize o Android Studio, instale a versão mais recente (estável ou preview que suporte AGP 8.12.x) e use **“Sync Project with Gradle Files”** após abrir o projeto.

## Tecnologias utilizadas
- **Kotlin**
- **Jetpack Compose**
- **Material 3**
- **Gradle Kotlin DSL**

## 📸 Demonstração (prints/telas)

1. **Lista inicial sem filtro**  
   <img width="786" height="967" alt="Captura de tela tela inicial " src="https://github.com/user-attachments/assets/3af73bda-f9ee-4cc8-953e-4c69f1ca132c" />


2. **Filtro ativo por texto (campo de busca)**  
   <img width="793" height="975" alt="Captura de tela filtro de busca" src="https://github.com/user-attachments/assets/fcc8521d-8568-4280-9ad5-39e4576a7d4e" />


3. **Filtro ativo por clique em estúdio (LazyRow)**  
  <img width="787" height="970" alt="Captura de tela filtro por clique" src="https://github.com/user-attachments/assets/2367a7ab-b466-41a1-b465-771e74a8fdf8" />


4. **Gif de funcionamento da aplicação**  
   ![gif_funcionamento da aplicação](https://github.com/user-attachments/assets/5f0574c5-7156-4edd-83fb-de57fc065554)


---

## Créditos:
- Desenvolvido por Ewerton Carreira.

---

Este projeto é um exemplo didático para estudos de Jetpack Compose e listas dinâmicas no Android.

