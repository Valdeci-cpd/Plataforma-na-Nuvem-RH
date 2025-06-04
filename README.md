# Documentação
Nome da Plataforma: Desenvolve RH, Alcance RH.
## 1. Visão Geral:
Uma ferramenta que viabiliza os processos de uma rotina diária de RH. 
Desde a contratação até a demissão do colaborador, cuidando de digitalizar e sistematizar tudo em uma plataforma online na nuvem.

O sistema centraliza informações de colaboradores, automatiza rotinas de RH e fornece ferramentas para tomada de decisões.

## 2. Objetivos:

Otimização de espaço, tempo, agilidade e precisão. Tudo em um só lugar.

## 3. Funcionalidades Principais:

_Em Desenvolvimento..._

## 4. Estrutura do Projeto:

**Backend (Java/Springboot):**

    system-RH/
    ├── src/
    │   └── main/
    │       ├── java/
    │       │   └── com/
    │       │       └── empresa/
    │       │           └── rhsystem/
    │       │               ├── config/
    │       │               ├── controller/
    │       │               ├── dto/
    │       │               ├── exception/
    │       │               ├── model/
    │       │               ├── repository/
    │       │               ├── service/
    │       │               └── RhSystemApplication.java
    │       └── resources/
    │           ├── static/
    │           │   ├── css/
    │           │   └── pages/
    │           │       ├── login.html
    │           │       ├── dashboard.html
    │           │       └── funcionarios.html
    │           ├── templates/ (caso use Thymeleaf futuramente)
    │           ├── application.properties
    │           └── data.sql / schema.sql (opcional para dados iniciais)
    ├── pom.xml
    └── README.md
    
**Front-end (HTML/CSS):**

    src/main/resources/static/
    ├── css/
    │   └── styles.css
    ├── pages/
    │   ├── login.html
    │   ├── dashboard.html
    │   └── funcionarios.html

**Hospedagem Local:**

Ubuntu Server 24.04.2

Acesso via: [http://localhost:5000](http://192.168.1.234:5000)
## 5. Segurança e LGPD:

## 6. Integrações:

## 7. Usuários e Perfis de Acesso:

Administrador: Acesso total ao sistema.

