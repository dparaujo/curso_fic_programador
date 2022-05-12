# curso_fic_programador
Descrição do Sistema

# Descrição

Este repositório contém um script desenvolvido utilizando a linguagem de programação Python para fazer a previsão da próxima palavra no idioma em português usando o modelo pré-treinado BERT e treinado na língua portuguesa. Esse script pode ser executado utilizando o Google Colab ou terminal linux com as devidas configurações descritas abaixo. O código do script está no arquivo nomeado: `Next_Word_Prediction_with_Transformers.ipynb`.

O modelo BERTimbau disponibilizado pela a Neuralmind, segue o link do github para mais informações: https://github.com/neuralmind-ai/portuguese-bert ou https://neuralmind.ai/sobre/, possui dois modelos pré-treinados BERT-Base e BERT-Large Cased e foram treinadas no BrWaC (Brazilian Web as Corpus). O BrWaC é um grande corpus português, por 1.000.000 de palavras, usando máscara de palavras inteiras.

---

# Instalação das dependências

O script com o modelo pré-treinado é baseado na biblioteca HuggingFace Transformers. E para o correto funcionamento das dependências do script será necessário a instalação da biblioteca com o seguinte comando, caso utilize o Google Colab: `!pip3 install transformers`

Se for usar o um terminal linux, dentro da sua virtual env pode ser executado o comando: `pip3 install transformers`

# Instalação Preliminar

Recomendamos criar um ambiente virtual com python 3.6+ e PyTorch.
