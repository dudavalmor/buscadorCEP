# 🔎 Buscador de CEP

<p align="center">
  Uma aplicação web simples e direta para consultar endereços brasileiros pelo CEP. <br />
  Powered by <a href="https://viacep.com.br/">ViaCEP API</a>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/feito%20com-JavaScript-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/API-ViaCEP-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-orange?style=flat-square"/>
</p>

---

## 🧭 Sobre o Projeto

O **Buscador de CEP** é uma aplicação front-end que permite ao usuário digitar um CEP e visualizar as informações de endereço correspondentes de forma rápida e limpa. A proposta é oferecer uma interface leve e acessível que consome a [API pública do ViaCEP](https://viacep.com.br/).

> Ideal para estudos, integrações simples ou curiosidades geográficas.

---

## 🖼️ Preview

<img src="https://raw.githubusercontent.com/dudavalmor/buscadorCEP/main/assets/preview.png" alt="Preview da aplicação" width="500">

---

## ⚙️ Funcionalidades

✅ Busca de CEP em tempo real  
✅ Exibição de logradouro, bairro, cidade e estado  
✅ Validação básica para CEPs inválidos ou incompletos  
✅ Interface 100% em HTML, CSS e JS puro (sem frameworks)

---

## 🚀 Como rodar localmente

1. Clone o repositório:

```bash
git clone https://github.com/dudavalmor/buscadorCEP.git
```

2. Acesse a pasta:

```bash
cd buscadorCEP
```

3. Abra o arquivo `index.html` diretamente no seu navegador:

```bash
start index.html   # No Windows
# ou
open index.html    # No macOS
```

> Você também pode usar uma extensão como “Live Server” no VS Code para rodar localmente com auto-reload.

---

## 🌐 Deploy com GitHub Pages

Se quiser hospedar seu fork online:

1. Vá em `Settings` do repositório  
2. Acesse a aba **Pages**  
3. Em **Source**, selecione `main` e a pasta `/root`  
4. Clique em **Save**  
5. O GitHub vai gerar uma URL pública como:
   ```
   https://seu-usuario.github.io/buscadorCEP/
   ```

---

## 🧠 Tecnologias Utilizadas

- **HTML5** – estrutura da página  
- **CSS3** – estilização simples e funcional  
- **JavaScript (Vanilla)** – lógica de busca e consumo da API  
- **[ViaCEP API](https://viacep.com.br/)** – dados oficiais de CEP

---

## 📁 Estrutura

```
buscadorCEP/
├── assets/
│   └── style.css
├── js/
│   └── script.js
├── index.html
└── README.md
```

---

## 💡 Possíveis Melhorias

- 🔄 Autoformatação de CEP com máscara (ex: `12345-678`)  
- ⚠️ Mensagens de erro mais detalhadas  
- 🌓 Suporte a modo escuro  
- 📱 Melhor responsividade mobile  

---

## 🤝 Contribuindo

Sinta-se à vontade para abrir uma issue, enviar sugestões ou fazer um PR. Toda ajuda é bem-vinda!

```bash
# Fork o projeto
# Crie uma nova branch
git checkout -b sua-melhoria

# Faça alterações, commits e envie:
git push origin sua-melhoria
```

---

## 🧑‍💻 Autor

Desenvolvido com 💙 por [Eduarda Valmor](https://github.com/dudavalmor)

---

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<p align="center">✨ Simples, leve e direto ao ponto ✨</p>
