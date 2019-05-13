# Web Crawler
>Bot web crowler criado com objetivo de coletar e armazenar especificações de hardware de máquinas oferecidas por serviços de cloud.

## Descrição
O objetivo do projeto é fazer um app que acesse o site da [Vultr](https://www.vultr.com/pricing/) e da [DigitalOcean](https://www.digitalocean.com/pricing/#droplet) via Scrapy, acesse os valores de **Memória**, **CPU**, **Armazenamento** e **Preço**(/mês) de maneira limpa, salve esses dados em arquivos **.JSON** e **.CSV**.

## Features
* Acessa o site da Vultr e exibe os dados no terminal
* Salva os dados em formato Json

## Dependências
As depêndencias utilizadas estão no arquivo `static/requirements.txt`, o aplicativo só foi testado em ambiente Linux (Kernel 4.19.36-1).

## Instalação
Siga os seguintes passos:
1. Crie uma pasta para o app na sua máquina.
1. Execute `virtualenv .venv` para criar um ambiente virtual e `source ./venv/bin/activate` para ativá-la.
1. Baixe o aplicativo rodando `git clone https://github.com/filipedeschamps/video-maker.git`.
1. Execute `pip install -r requirements.txt` para baixar as dependências.
1. Dê permissão de execução ao arquivo `main.py` rodando `sudo chmod 777 main.py`

Agora está tudo pronto para rodar o aplicativo, execute `./main.py`.

Sua saída será semelhante a essa:
![](https://raw.githubusercontent.com/tamercuba/Web-Crawler/master/static/output_print.png)
A saída também está salva no arquivo `static/maquinas.json`

## Histórico de versões

* v0.2 - ATUAL
* [v0.1](https://github.com/tamercuba/Web-Crawler/tree/v0.1)

## Contato
* [LinkedIn](https://linkedin.com/in/tamercuba)
* [Facebook](https://www.fb.com/tamercuba)
* E-mail: `tamercuba@gmail.com`
