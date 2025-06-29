# Sistema de Gestão de Recursos Humanos da Direção MUnicipal da Educação de Benguela

Bem-vindo ao repositório do **Sistema de Gestão de Recursos Humanos** da **Direção Municipal da Educação de Benguela**. Este sistema foi desenvolvido para otimizar o gerenciamento da Força de Trabalho Activa , Funcionários Covalescentes, bem como a rede escolar do municipio de Benguela, utilizando a potência do Laravel 12.

> **Status do projeto:** 🚀🔧 Em desenvolvimento

---

## Funcionalidades Principais

### ✅ Cadastro de Utilizador

-   Cadastro de Utilizador

### ✅ Relatórios Detalhados

-   Geração de relatórios html dinâmicos.
-   Exportação de dados em formatos PDF e Excel.

### ✅ Segurança e Eficiência

-   Sistema de autenticação robusto.
-   Interface responsiva, garantindo usabilidade em diferentes dispositivos.

---

## Tecnologias Utilizadas

-   **Framework**: Laravel 12
-   **Frontend**: Blade Templates, Bootstrap 5
-   **Banco de Dados**: MySQL
-   **Autenticação**: Laravel UI
-   **Exportação**: Html, Maatwebsite Excel

---

## Instalação e Configuração

1. **Clone o repositório**:

```bash
$ git clone https://github.com/AurelioTec/DME-GRH.git
```

2. **Instale as dependências**:

```bash
$ composer install
```

3. **Configure o arquivo `.env`**:

-   Copie o arquivo de exemplo:

```bash
$ cp .env.example .env
```

-   Configure as credenciais do banco de dados e outras variáveis no arquivo `.env`.

4. **Gere a chave da aplicação**:

```bash
$ php artisan key:generate
```

5. **Execute as migrações e seeders**:

```bash
$ php artisan migrate --seed
```

6. **Inicie o servidor local**:

```bash
$ php artisan serve
```

Acesse o sistema em: `http://localhost:8000`

---

## Layout

### Tela de Login

(<img src="">)

### Painel de Controle

![Painel de Controle]()

---

## Contribuição

Contribuições são bem-vindas! Siga os passos abaixo para colaborar:

1. Crie um fork deste repositório.
2. Crie um branch com a sua funcionalidade: `git checkout -b minha-nova-funcionalidade`.
3. Envie as modificações: `git commit -m 'Adicionei minha funcionalidade'`.
4. Realize um push para o branch: `git push origin minha-nova-funcionalidade`.
5. Crie um pull request.

---

## Contato

📧 Email: [aureliofabio16@gmail.com](mailto:aureliofabio16@gmail.com)  
🌐 Website: [https://www.linkedin.com/in/afonso-aur%C3%A9lio-269aa6227/](https://www.linkedin.com/in/afonso-aur%C3%A9lio-269aa6227/)  
📞 Telefone: +244 939 985 248
📞 Telefone: +244 958 792 104

---

## Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

---

> Simplifique a gestão de recursos humanos com o poder do Laravel 🚀
