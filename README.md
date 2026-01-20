# 📊 Inventário de Computadores – Aplicação Web (PHP + SQL)

## 👤 Identificação
- **Nome do aluno:** Filipe Fernandes Carneiro
- **Turma:** 2I
- **Disciplina:** REDES – M6 – Programação de Sistemas de Informação  
- **Curso:** GPSI – 2.º Ano  

---

## 🎯 Objetivo do Projeto
Este projeto consiste no desenvolvimento de uma aplicação web para gestão e consulta de um inventário de computadores de uma sala informática, utilizando PHP para a lógica da aplicação e SQL para a base de dados.

A aplicação permite não só consultar informações técnicas e software, mas também gerir o estado de saúde dos equipamentos, registar avarias, manutenções preventivas e controlar o fluxo de empréstimos.

---

## 🧱 Estrutura Geral do Projeto
O projeto está organizado da seguinte forma:
- **`config.php`**: Configuração da ligação PDO à base de dados MySQL.
- **`index.php`**: Dashboard principal com listagem, filtros de sala, pesquisa global e contagem de equipamentos.
- **`detalhe.php`**: Ficha técnica detalhada de cada computador, incluindo gestão de estados e históricos.
- **Base de Dados**: Estrutura relacional com tabelas para salas, computadores, software, avarias, manutenções e requisições.

---

## ⚙️ Funcionalidades Desenvolvidas
Implementei todas as funcionalidades obrigatórias e várias de valorização (fora da caixa):

- [x] **Ligação à base de dados (Obrigatória)**: Utilização de PHP PDO com tratamento de exceções.
- [x] **Listagem por sala (Obrigatória)**: Filtro dinâmico que permite ver computadores de uma sala específica ou de todas.
- [x] **Pesquisa Avançada (Fora da caixa)**: Procura global pelo nome de computador ou por software instalado.
- [x] **Página de Detalhe (Obrigatória)**: Visualização completa das características técnicas e software.
- [x] **Indicadores de Saúde (Fora da caixa)**: Sistema visual (Verde/Amarelo/Vermelho) para estado operacional.
- [x] **Gestão de Avarias (Fora da caixa)**: Botão para reportar avarias com descrição e registo automático de data e hora.
- [x] **Histórico de Manutenção (Fora da caixa)**: Registo de intervenções técnicas (limpezas, upgrades, etc.).
- [x] **Interface Responsiva (Fora da caixa)**: Design moderno utilizando Bootstrap 5 e ícones dinâmicos.

---

## 🤖 Utilização da Inteligência Artificial (IA)
Utilizei a IA como ajuda para me dar ideias (fora da caixa) e para me ajudar com o interface gráfico principalmente.

### 🔹 Onde utilizei IA
- **Estruturação de Código**: Apoio na criação da lógica de filtros dinâmicos e transações SQL.
- **Queries Complexas**: Ajuda na criação de `JOINs` para relacionar computadores, software e históricos.
- **Interface Gráfica**: Sugestões de layout utilizando Bootstrap para tornar a aplicação profissional e responsiva.
- **Resolução de Problemas**: Ajuste de fusos horários (Lisboa) e correção de erros de lógica.
- **Ideias "Fora da Caixa"**: Sugestões de funcionalidades como o sistema de saúde e a gestão de avarias.

### 🔹 Como utilizei a IA
A IA forneceu modelos de código e sugestões estruturais que depois foram adaptados por mim.

---

## ✍️ Trabalho Desenvolvido Manualmente
- **Personalização Visual**: Ajuste de cores, ícones e alinhamentos (ex: correção da navbar no detalhe).
- **Lógica de Negócio**: Adaptação dos formulários de reporte de avaria e resolução de problemas.
- **Estruturação da Base de Dados**: Criação e relação das tabelas adicionais para suportar as novas funcionalidades.

---

## 🚧 Dificuldades Encontradas
- **Gestão de Datas**: Sincronizar a hora do servidor com a hora de Portugal (resolvido via PHP).
- **Relações SQL**: Implementar a pesquisa que cruzasse dados de computadores e software simultaneamente.
- **Interface**: Garantir que a barra de navegação e os elementos Bootstrap ficavam perfeitamente alinhados em diferentes resoluções.

---

## 📚 Aprendizagens Realizadas
- Domínio da ligação PHP -> MySQL via PDO.
- Compreensão da importância de transações SQL para manter a integridade dos dados.
- Desenvolvimento de interfaces focadas na experiência do utilizador (UX).
- Utilização da IA como ferramenta de produtividade e não apenas de cópia.
