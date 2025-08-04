# 📦 Buscador de CEP - Java

Aplicação simples desenvolvida em **Java** para consultar dados de endereço a partir de um CEP, utilizando a API pública do [ViaCEP](https://viacep.com.br/).

---

## 📌 Sobre o projeto

Este é um programa de linha de comando em Java que faz uma requisição HTTP à API do ViaCEP e retorna informações como:

- Logradouro
- Bairro
- Localidade (Cidade)
- UF (Estado)

Ideal para quem está aprendendo sobre consumo de APIs REST com Java e bibliotecas como `HttpURLConnection`, `Gson`, ou `HttpClient`.

---

## 🎯 Funcionalidades

✔ Consulta de endereço via CEP  
✔ Tratamento de erros para CEP inválido  
✔ Saída formatada no terminal  
✔ Integração com API pública (sem necessidade de autenticação)

---

## 🛠 Tecnologias e Bibliotecas

- **Java 11+**
- **[ViaCEP API](https://viacep.com.br/)**
- `java.net.HttpURLConnection` ou `java.net.http.HttpClient` (dependendo da versão usada)
- `com.google.gson.Gson` para desserializar JSON (opcional)

---

## ▶️ Como executar

1. Clone o repositório:
```bash
git clone https://github.com/dudavalmor/buscadorCEP.git
cd buscadorCEP
```

2. Compile o código:
```bash
javac Main.java
```

3. Execute a aplicação:
```bash
java Main
```

> O programa irá pedir para você digitar um CEP, fará a consulta e exibirá os dados no terminal.

---

## 🧠 Exemplo de uso

```text
Digite um CEP: 01001000

Resultado:
Logradouro: Praça da Sé
Bairro: Sé
Cidade: São Paulo
Estado: SP
```

---

## 📂 Estrutura do Projeto

```
buscadorCEP/
├── Main.java         # Arquivo principal com a lógica de busca
├── ViaCepResponse.java # (opcional) Classe para mapear resposta JSON
├── utils/            # (opcional) Funções auxiliares
└── README.md         # Este arquivo
```

---

## 💡 Melhorias futuras

- Interface gráfica com JavaFX ou Swing  
- Validação de entrada com regex  
- Suporte a múltiplas consultas  
- Exportar resultado para `.txt` ou `.json`

---

## 🧑‍💻 Autor

Desenvolvido por [Duda Valmor](https://github.com/dudavalmor) com foco educacional e aprendizado em Java.

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
