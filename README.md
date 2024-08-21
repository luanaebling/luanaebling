graph TD
    A[Você realmente precisa comprar esse item?] -->|Sim| B[Compre]
    A -->|Não| C[Alerta: O que estou sentindo nesse momento que me faz querer comprar?]
    C --> D[Reflita sobre a necessidade emocional ou circunstancial]
    D -->|Após reflexão: Ainda sinto que é necessário| B
    D -->|Após reflexão: Não sinto mais a necessidade| E[Não compre]

    B --> F[Você tem dinheiro para comprar esse item?]
    F -->|Sim| G[Compre]
    F -->|Não| H[Alerta: O que estou sentindo nesse momento que me faz querer comprar?]
    H --> I[Reflita sobre a possível influência de fatores emocionais ou pressões externas]
    I -->|Após reflexão: Ainda sinto que é necessário e posso parcelar ou economizar| J[Planeje uma compra futura]
    I -->|Após reflexão: Não sinto mais a necessidade| E

    G --> K[É uma necessidade ou um desejo?]
    K -->|Necessidade| G
    K -->|Desejo| L[Reflita se o desejo justifica o gasto e se é financeiramente viável]
    L -->|Justifica| G
    L -->|Não justifica| E

