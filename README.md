![image](https://github.com/Zenox-AI/Teste-Backend-Golang/assets/144921896/480d7d7d-aa5b-4f00-b5a0-b9d4e740fc99)


# Desafio Backend Golang

Olá! Estamos muito felizes por você ter chegado até esta etapa do processo seletivo. Desejamos muito sucesso e esperamos que você tenha uma experiência agradável enquanto trabalha neste desafio. 

**Objetivo:** Implementar um scraper web em Golang para coletar dados da página web "Scrape This Site", estruturar esses dados em JSON, e enviá-los para uma fila Kafka.

**Requisitos:**

**1 - Coleta de Dados:**

Faça o scraping do site https://www.scrapethissite.com/pages/simple/.
Colete os dados de todos os países listados, focando especificamente nos dados de população.
Estruturação dos Dados:

**2 - Estruture os dados coletados em JSON.**

Defina e utilize structs em Golang para representar a estrutura dos dados. A struct deve conter, no mínimo, os campos: "País" e "População".

**3 - Integração com Kafka:**

Envie os dados estruturados para uma fila no Kafka.
Providencie o arquivo Docker (Dockerfile e docker-compose, se aplicável) do Kafka utilizado no teste.

**Diferenciais:**

- Implemente lógicas e algoritmos para evitar o bloqueio do scraper, como:
  - Uso de proxies rotativos.
  - Intervals variáveis entre as requisições.
  - Identificação e manipulação de headers (User-Agent) para simular diferentes browsers ou dispositivos.

**O que será avaliado:**

1. Qualidade do código e organização.
2. Capacidade de definir e utilizar structs em Golang.
3. Integração com Kafka e a correta configuração do ambiente Docker para o Kafka.
4. Implementação dos diferenciais (se aplicável).
5. Documentação do código e instruções para execução.


**Instruções para a entrega:**

1. O candidato deve dar fork neste repositório e após o termino do desenvolvimento, realizar um pull request para análise do time.
2. Inclua um README com instruções claras sobre como executar e testar o projeto.

---
#### LICENSE
```
MIT License

Copyright (c) 2016 ZenoX IA

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
