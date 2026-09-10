# ChargeGrid Intelligence

Análise e protótipo simulado de um sistema de recarga inteligente de veículos elétricos, integrando geração de energia solar (GoodWe) com gestão de pontos de recarga (ChargeGrid).

## Equipe

- Felipe Mitsuo
- Laura Godoy
- Letícia Espindola
- Mariana Dreset
- Milena de Aguiar

## Sobre o projeto

O trabalho analisa como a integração entre inversores solares (GoodWe) e uma plataforma open source de gestão de recarga (ChargeGrid) pode tornar o uso de energia mais eficiente e sustentável, tanto em ambientes residenciais quanto comerciais.

A solução se apoia em 4 pilares:

1. **Controle de demanda** —> balanceamento inteligente de carga entre carregadores, evitando sobrecarga da rede.
2. **Protocolos abertos (OCPP/OCPI)** —> comunicação padronizada entre carregadores, softwares e sistemas de pagamento, independente do fabricante.
3. **Tarifação e pagamento** —> cobrança dinâmica conforme horário/demanda, com integração a diferentes meios de pagamento.
4. **Inteligência artificial** —> previsão de demanda e detecção de anomalias a partir de dados históricos de uso.

## Protótipo (dashboard.html)

O arquivo `dashboard.html` é um protótipo simulado, funcional no navegador, que demonstra os 4 pilares em ação:

- **Balanceamento de carga**: redistribui a energia entre carregadores quando o sistema entra em sobrecarga.
- **Tarifação dinâmica**: o valor cobrado muda automaticamente conforme o horário (off-peak / normal / pico).
- **IA preditiva**: usa regressão linear para prever a demanda de energia em +1h e +3h, e detecção de anomalias por Z-score.
- **Simulação de protocolo OCPP 1.6**: exibe dados de uma transação de recarga simulada (kWh, status).

### Como usar

1. Baixe ou clone este repositório.
2. Abra o arquivo `dashboard.html` diretamente no navegador (não precisa de servidor ou instalação).
3. Use os botões de cenário (normal, pico, sobrecarga, off-peak) para observar como o sistema reage em cada situação.

## Conexão com a disciplina

O protótipo aplica, de forma prática, os conceitos discutidos sobre integração de energia renovável, automação e comunicação entre sistemas, mostrando como controle de demanda, protocolos abertos, tarifação inteligente e IA se conectam para formar um ecossistema energético mais eficiente.
