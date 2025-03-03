# Validate Reports
### Link abaixo para testar
[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/adeiltonmsantos/ReportValidator/blob/main/validate_reports.ipynb)

Uma aplicação desenvolvida no Google Colab para auxiliar IPEMs, órgãos delegados do INMETRO, quanto à necessidade de apreensão de produtos pré-embalados examinados e que foram reprovados. Critérios específicos quando não atendidos levam à apreensão de produtos pré-embalados:

- Quando mais de 30% das medições de um exame quantitativo apresenta erro tipo T1 (conteúdo efetivo abaixo do limite previsto em Regulamento Técnico).
- Quando pelo menos uma das medições de um exame quantitativo apresenta erro tipo T3 (conteúdo efetivo com deficit três vezes superior ao limite previsto em Regulamento Técnico).

A depender da quantidade de exames e/ou do número de medições, a avaliação dos resultados frente aos critérios listados acima pode demandar tempo considerável.

Esta aplicação possibilita que um agente metrológico de qualquer IPEM faça upload de quantos laudos quiser em PDF, os quais são analisados e os produtos que apresentarem motivos para apreensão são listados em uma folha de despacho, com as devidas justificativas, para ser anexa no respectivo processo administrativo.

A aplicação ainda permite que imagens com marca d'água, assinatura do responsável e dados de identificação do IPEM possam ser salvos em uma conta Google Drive para compor a folha de despacho.
