# 🔐 Glossário de Criptografia

Este repositório contém um glossário introdutório sobre criptografia, com explicações simples sobre os principais conceitos e sobre o uso de chaves simétricas e assimétricas.

## 🛡 O que é Criptografia?

Criptografia é a prática de proteger informações através da transformação de dados legíveis (texto simples) em dados cifrados (texto cifrado), de modo que apenas pessoas autorizadas possam acessar a informação original.

Ela é utilizada para garantir:
-  **Confidencialidade**: apenas pessoas autorizadas podem ler a informação.
-  **Integridade**: garante que a informação não foi alterada.
-  **Autenticidade**: garante que a informação realmente veio de quem diz ter vindo.
-  **Não-repúdio**: impede que alguém negue ter enviado uma mensagem.

---

## 🔑 Chave Simétrica

### O que é?
Criptografia de chave simétrica é um método no qual **a mesma chave é usada tanto para cifrar quanto para decifrar a informação**.

### 📌 Características:
-  Mais rápida e eficiente.
-  Necessidade de manter a chave secreta entre as partes.
-  Dificuldade na distribuição segura da chave.

### 🛠 Exemplos de algoritmos:
- AES (Advanced Encryption Standard)
- DES (Data Encryption Standard)
- Blowfish
- ChaCha20 🔥

### 💡 Para que serve?
É muito utilizada em ambientes controlados onde as partes podem compartilhar a chave com segurança.  
Exemplo: criptografia de arquivos locais, VPNs, backups.

---

## 🔐 Chave Assimétrica

### O que é?
Criptografia de chave assimétrica utiliza **um par de chaves: uma pública e uma privada**. O que é cifrado com uma chave só pode ser decifrado com a outra.

### 📌 Características:
-  Chave pública pode ser compartilhada abertamente.
-  Chave privada deve ser mantida em segredo.
-  Mais lenta que a criptografia simétrica.
-  Resolve o problema de distribuição segura das chaves.

### 🛠 Exemplos de algoritmos:
- RSA (Rivest-Shamir-Adleman)
- ECC (Elliptic Curve Cryptography)
- ElGamal 🔑

### 💡 Para que serve?
Muito utilizada em:
-  Comunicação segura na internet (SSL/TLS).
-  Assinaturas digitais.
-  Certificados digitais.
-  Troca segura de chaves simétricas.

---

## 🤝 Contribuições

Contribuições são bem-vindas!  
Sinta-se livre para abrir issues ou pull requests para expandir o glossário.

## 📄 Licença

Este projeto está licenciado sob a licença MIT.
