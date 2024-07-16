# Projeto de Acompanhamento de Horários de Missas e Atendimentos Paroquiais

Este projeto visa fornecer um sistema para acompanhar os horários de missas e atendimentos paroquiais na Arquidiocese de Fortaleza-CE. Ele envolve várias etapas, desde a extração de dados de PDFs até a visualização desses dados em um dashboard interativo.

## Índice

- [Descrição do Projeto](#descrição-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Etapas do Projeto](#etapas-do-projeto)
  - [Reconhecimento Óptico de Caracteres (OCR)](#reconhecimento-óptico-de-caracteres-ocr)
  - [Limpeza de Dados](#limpeza-de-dados)
  - [Criação de Dashboard](#criação-de-dashboard)
- [Próximos Passos](#próximos-passos)
- [Como Contribuir](#como-contribuir)
- [Licença](#licença)

## Descrição do Projeto

Este projeto foi desenvolvido para facilitar o acesso e a gestão dos horários de missas e atendimentos paroquiais na Arquidiocese de Fortaleza-CE. Utilizando diversas tecnologias e bibliotecas de Python, os dados são extraídos de PDFs, limpos e visualizados em um dashboard interativo.

## Tecnologias Utilizadas

- **Python**: Linguagem principal utilizada no projeto.
- **Tika**: Biblioteca utilizada para OCR (Reconhecimento Óptico de Caracteres).
- **Numpy e Pandas**: Bibliotecas utilizadas para limpeza e manipulação de dados.
- **Looker Studio**: Ferramenta utilizada para a criação do dashboard interativo.

## Etapas do Projeto

### Reconhecimento Óptico de Caracteres (OCR)

Utilizamos a biblioteca [Tika](https://tika.apache.org/) para realizar o reconhecimento óptico de caracteres a partir de arquivos PDF contendo os horários das missas e atendimentos. A Tika permite extrair texto de diversos formatos de arquivo, facilitando a análise posterior.

### Limpeza de Dados

Após a extração dos dados, utilizamos as bibliotecas [Numpy](https://numpy.org/) e [Pandas](https://pandas.pydata.org/) para realizar a limpeza e estruturação dos dados. Esse processo inclui a remoção de inconsistências, preenchimento de valores faltantes e formatação dos dados para análise.

### Criação de Dashboard

Com os dados limpos, criamos um dashboard interativo no [Looker Studio](https://lookerstudio.google.com/reporting/89fd43e0-247f-491e-9311-5fbbfd995702). O dashboard permite aos usuários visualizar os horários de missas e atendimentos de forma intuitiva e acessível.

## Próximos Passos

- Implementação de uma funcionalidade para medir a distância até as missas mais próximas, considerando localização e horário.

## Como Contribuir

Contribuições são bem-vindas! Se você deseja contribuir com este projeto, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch para a sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Faça o push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
