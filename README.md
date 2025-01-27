# Combate a Incêndios Florestais

![FirePrevention](https://github.com/devrictrovato/ForestFirePrevention/assets/66500781/e60017cf-6b58-4469-8a2c-3f35c0901705)

Este repositório apresenta um modelo de Machine Learning baseado em uma base de dados do [INPE](https://queimadas.dgi.inpe.br/queimadas/bdqueimadas), desenvolvido para apoiar a prevenção de incêndios florestais. O projeto segue as etapas principais de desenvolvimento de um modelo de aprendizado de máquina, incluindo **Entendimento do Negócio**, **Análise dos Dados**, **Preparação dos Dados**, **Modelagem**, **Avaliação do Modelo** e **Conclusão**.

## Visão Geral

Os incêndios florestais são um dos desastres naturais mais devastadores que afetam ecossistemas e comunidades. Este projeto pretende fornecer uma solução para reduzir os danos causados por esses incêndios por meio da detecção antecipada.

As principais funcionalidades do sistema são:

1. **Detecção de Fogo:** Utiliza uma análise rápida para constatar presença de fogo a partir de um algoritmo de Machine Learning conforme a entrada dos dados no sistema.

2. **Monitoramento Ambiental:** Coleta dados ambientais em tempo real, como dias sem chuva, precipitação, risco de fogo e frp(fire radiative power), analisando assim as condições propícias para o surgimento de incêndios florestais.

3. **Alerta de Incêndio:** Quando um possível incêndio é detectado ou quando as condições ambientais são propícias para incêndios, o sistema envia alerta para as autoridades responsáveis ofereçendo o local a partir da latitude e longitude.

## Detalhes de cada etapa

1. Entendimento do Negócio: Identificar o problema a ser resolvido e entender como o modelo pode contribuir para a prevenção de incêndios florestais. ([FIT](./Machine_Learning_FIT.ipynb))
2. Análise dos Dados: Procurar e avaliar a qualidade e relevância dos dados disponíveis. ([Analytics](./Machine_Learning_Analytics.ipynb))
3. Preparação dos Dados: Transformar os dados brutos em um formato adequado para a modelagem. ([Dataset](./Machine_Learning_Dataset.ipynb))
4. Modelagem: Treinar modelos que possam prever ou classificar áreas de risco de incêndio. ([Models](./Machine_Learning_Models.ipynb))
5. Avaliação do Modelo: Verificar a eficácia do modelo em prever incêndios e identificar melhorias potenciais. ([Evaluation](./Machine_Learning_Evaluation.ipynb))

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](https://github.com/devrictrovato/Combate-Aos-Incendios-Florestais/blob/main/LICENSE) para obter mais detalhes.

## Contato

Para mais informações sobre o projeto ou para relatar problemas, entre em contato com o desenvolvedor:

E-mail: devrictrovato@gmail.com

LinkedIn: [Ricardo O. Trovato](https://www.linkedin.com/in/ricardo-de-oliveira-trovato/)
