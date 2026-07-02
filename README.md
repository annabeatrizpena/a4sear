# Stable Diffusion - Geração de Imagens com Inteligência Artificial

## 📖 Sobre o projeto

Este projeto demonstra a utilização do modelo **Stable Diffusion** para geração de imagens a partir de descrições em linguagem natural (prompts), utilizando o **Google Colab** e a biblioteca **Diffusers**, da Hugging Face.

O objetivo da prática foi avaliar a eficiência do modelo por meio da execução de **seis prompts diferentes**, analisando a qualidade, a coerência e o tempo necessário para gerar cada imagem.

## 🎯 Objetivos

* Implementar o Stable Diffusion no Google Colab;
* Gerar imagens a partir de diferentes prompts;
* Comparar os resultados obtidos em cada geração;
* Medir o tempo de inferência do modelo;
* Explorar aplicações da geração de imagens em cenários relacionados à inteligência artificial e robótica.

## 🛠️ Tecnologias utilizadas

* Python
* Google Colab
* PyTorch
* Diffusers
* Transformers
* Stable Diffusion v1.5

## ▶️ Como executar

1. Abra o notebook no Google Colab.
2. Instale as dependências:

```python
!pip install diffusers transformers
```

3. Execute todas as células do notebook.
4. Altere o conteúdo da variável `prompt` para testar diferentes descrições.
5. Ao final da execução serão exibidos:

   * A imagem gerada;
   * O arquivo salvo (`generated_image.png`);
   * O tempo de geração da imagem.

## 📊 Resultados

Foram realizados testes utilizando seis prompts distintos. Para cada execução foram observados:

* Qualidade visual da imagem;
* Fidelidade ao prompt informado;
* Nível de detalhamento;
* Tempo de geração.

Os resultados demonstram a capacidade do Stable Diffusion de produzir imagens realistas e coerentes com diferentes descrições textuais, mantendo um bom desempenho computacional quando executado em GPU.



## 📚 Referências

* Google Colab: https://colab.research.google.com/

## 👨‍💻 Autor
* Anna Beatriz Pena

Projeto desenvolvido como atividade prática da disciplina de Inteligência Artificial, explorando a geração de imagens por meio do modelo Stable Diffusion utilizando o Google Colab.
