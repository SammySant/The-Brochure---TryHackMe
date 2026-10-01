![thebrochure](thebrochure.png)

# 🚩 TryHackMe | Desafio OSINT: Byte Lotus Resorts

Mais um desafio TryHackMe concluído! Dessa vez, o desafio foi bem mais simples, mas introduziu conceitos interessantes que agregam valor, como **OSINT**, **análise de redes sociais** e **análise de imagem**.

## 📌 Ponto de partida

O desafio começa com uma imagem de um post do resort. Nela aparece a frase:

> "Find us on Instagram or not"

Essa frase funciona como a pista inicial para onde seguir.

## 🔎 Investigação

Ao buscar por **Byte Lotus Resorts** no Instagram, encontrei o perfil oficial do resort com alguns posts. O perfil segue apenas **uma conta**: a da **VERA**, a IA da Lotus.

## 🧩 Resolução

No perfil da VERA, havia exatamente **três fotos**, cada uma contendo um texto codificado em **Base64**.

1. Utilizei uma ferramenta online de decodificação ([topster.pt](http://topster.pt)) para converter cada trecho.
2. Cada foto revelou uma parte da flag.
3. Bastou juntar as três partes, na ordem, para obter a flag completa.

> 💡 **Nota técnica:** Base64 é uma **codificação**, não uma criptografia. Ela não protege a informação, apenas a converte para outro formato, e por isso pode ser revertida facilmente.

## ✅ Conclusão

Flag enviada e desafio validado!

Apesar de simples, foi um ótimo exercício para reforçar conceitos de:

- OSINT
- Redes sociais como fonte de informação
- Análise de imagem
- Codificação e decodificação em Base64

---

`#TryHackMe` `#OSINT` `#CyberSecurity` `#CTF` `#Base64`
